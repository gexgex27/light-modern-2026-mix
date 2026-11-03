# Light Modern 2026 (AI Mix)

A standalone Visual Studio Code color theme combining the built-in **Light Modern** workbench with the **Light 2026** editor canvas, editor widgets, diff/minimap colors, and syntax highlighting.

> This theme was combined with AI assistance. The final package and color mapping were checked before release.

## Install

1. Open this folder in VS Code.
2. Run **Extensions: Install from VSIX...** after packaging, or use `npx @vscode/vsce package` in this directory to create the `.vsix`.
3. Choose **Light Modern 2026 (AI Mix)** from **Preferences: Color Theme**.

Requires VS Code 1.143 or newer.

## Palette

| Role | Color |
| --- | --- |
| Editor and tab canvas | `#FFFFFF` |
| Main text | `#202020` |
| Light Modern panels and workbench surfaces | `#F8F8F8` |
| Borders and separators | `#E5E5E5` |
| Primary accent, focus and cursor | `#005FB8` |
| Light 2026 selection | `#0069CC40` |
| Syntax keyword | `#CF222E` |
| Syntax control flow | `#AF00DB` |
| Syntax strings | `#A31515` |
| Syntax types | `#267F99` |
| Syntax functions | `#795E26` |
| Syntax comments | `#6E7781` |
| Added content | `#116329` |
| Deleted content / errors | `#82071E` |

The theme JSON is flattened and self-contained: it does not depend on VS Code's built-in theme files at runtime.

## Source and attribution

The workbench palette is based on VS Code's built-in Light Modern theme; editor-area colors and token rules are based on the built-in Light 2026 theme. The combination and this extension package were prepared with AI assistance. VS Code source is licensed under the MIT License; see [LICENSE.txt](LICENSE.txt).
