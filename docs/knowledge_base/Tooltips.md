## Tooltips
Technical documentation often incurs the usage of many acronyms, which may need additional explanation, especially for new user of your project. For these matters, Material for MkDocs uses a combination of Markdown extensions to enable site-wide glossaries.
This configuration enables abbreviations and allows to build a simple project-wide glossary, sourcing definitions from a central location. Add the following line to `mkdocs.yml`.

```
markdown_extensions:
    - abbr
    - attr_list
    - pymdownx.snippets
```
### Adding Tooltips
The Markdown syntax allows to specify a title for each link, which will render as a beautiful tooltip when improved tooltips are enabled. Add a tooltip to a link with the following lines:

[Hover me](https://example.com "I'm a tooltip!")
