# Code Blocks
Code blocks and examples are an essential part of technical project documentation. Material for MkDocs provides different ways to set up syntax highlighting for code blocks, either during build time using Pygments or during runtime using a JavaScript syntax highlighter.
## Configuration
This configuration enables syntax highlighting on code blocks and inline code blocks, and allows to include source code directly from other files. Add the following lines to ```mkdocs.yml:```
``` py
markdown_extensions:
  - pymdownx.highlight:
      anchor_linenums: true
      line_spans: __span
      pygments_lang_class: true
  - pymdownx.inlinehilite
  - pymdownx.snippets
  - pymdownx.superfences
```