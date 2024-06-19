# Annotations
One of the flagship features of Material for MkDocs is the ability to inject annotations – little markers that can be added almost anywhere in a document and expand a tooltip containing arbitrary Markdown on click or keyboard focus.
#### Using Annotation
Annotations consist of two parts: a marker, which can be placed anywhere in a block marked with the ```annotate``` class, and content located in a list below the block containing the marker:

Click the arrow, (1) to learn more information.
{ .annotate }

1.  :man_raising_hand: I'm an annotation! I can contain `code`, __formatted
    text__, images, ... basically anything that can be expressed in Markdown.
2.  ```markdown_extensions:
        - attr_list
        - md_in_html
        - pymdownx.superfences
    ```