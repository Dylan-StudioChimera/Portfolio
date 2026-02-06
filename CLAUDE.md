# Portfolio Project

## Figma MCP Integration

This project uses the [Figma MCP server](https://developers.figma.com/docs/figma-mcp-server/) to bridge design and code.

### Available MCP Tools

- **get_design_context** - Extract layout, components, and styling from a Figma frame or selection
- **get_variable_defs** - Retrieve design tokens (colors, spacing, typography) as variables
- **get_code_connect_map** - Map Figma components to codebase implementations
- **get_screenshot** - Capture visual references of frames/layers

### Workflow

1. Share a Figma frame link or select a frame in the Figma desktop app
2. Use `get_design_context` to extract the design structure
3. Use `get_variable_defs` to pull design tokens for consistent styling
4. Implement the design using the extracted context

### Design-to-Code Guidelines

- Extract design tokens before implementing components to ensure consistency
- Use semantic variable names from Figma when creating CSS custom properties or theme values
- Match Figma component hierarchy when structuring React/HTML components
- Preserve spacing, typography, and color values exactly as defined in the design system
