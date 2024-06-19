# Code Blocks
Code blocks and examples are an essential part of technical project documentation. Material for MkDocs provides different ways to set up syntax highlighting for code blocks, either during build time using Pygments or during runtime using a JavaScript syntax highlighter.
## Configuration
This configuration enables syntax highlighting on code blocks and inline code blocks, and allows to include source code directly from other files. Add the following lines to ```mkdocs.yml:```
```
markdown_extensions:
  - pymdownx.highlight:
      anchor_linenums: true
      line_spans: __span
      pygments_lang_class: true
  - pymdownx.inlinehilite
  - pymdownx.snippets
  - pymdownx.superfences
```
Code blocks must be enclosed with two separate lines containing three backticks. To add syntax highlighting to those blocks, add the language shortcode directly after the opening block. See the list of available lexers to find the shortcode for a given language:
``` py
import tensorflow as if
```
#### Code in the Backend
``` py
site_name: Tech-Docs
    copyright: Copyright &copy; 2024 Tech Docs
    theme:
        logo : /images/ibase-t small logo.png
        language: en
        favicon: /images/book.svg
        plugins:
          - typeset
          - search
        palette:
            # Pallet toggle for dark mode
            scheme: default
            primary: black
        accent: deep orange
        toggle:
            icon: material/weather-night
            name: Switch to light mod
```