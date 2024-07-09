
Material for MkDocs makes it easy to deploy multiple versions of your project documentation by integrating with external utilities that add those capabilities to MkDocs, i.e. [mike](https://github.com/jimporter/mike). When deploying a new version, older versions of your documentation remain untouched.
## Configuration
#### Versioning
[Mike](https://github.com/jimporter/mike) makes it easy to deploy multiple versions of your project documentation. It integrates natively with Material for MkDocs and can be enabled via mkdocs.yml:

```yaml
extra:
  version:
    provider: mike
```