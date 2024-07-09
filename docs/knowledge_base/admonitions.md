# Admonitions
* Admonitions
* Code Block
* Product Design 
* Backend codes
* QA Testing path 
??? Info
        markdown_extensions:
          - pymdownx.highlight:
                anchor_linenums: true
                line_spans: __span
                pygments_lang_class: true
          - pymdownx.inlinehilite
          - pymdownx.snippets
          - pymdownx.superfences

#### Inline Blocks
Admonitions can also be rendered as inline blocks (e.g., for sidebars), placing them to the right using the ```inline``` + ```end``` modifiers, or to the left using only the ```inline``` modifier:

!!! warning inline end "warning"

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et
    euismod nulla. Curabitur feugiat, tortor non consequat finibus, justo
    purus auctor massa, nec semper lorem quam in massa.

``` markdown
!!! info inline end "Lorem ipsum"

    Lorem ipsum dolor sit amet, consectetur
    adipiscing elit. Nulla et euismod nulla.
    Curabitur feugiat, tortor non consequat
    finibus, justo purus auctor massa, nec
    semper lorem quam in massa.
```

Use `inline end` to align to the right (left for rtl languages).