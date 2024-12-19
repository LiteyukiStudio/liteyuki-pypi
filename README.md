# Publish your Python package to gitea software registry

## Usage

```yaml
- name: Publish Python Package to Gitea
  uses: LiteyukiStudio/liteyuki-pypi
    owner: LiteyukiStudio
    username: ${{ secrets.GITEA_USERNAME }}
    token: ${{ secrets.GITEA_TOKEN }}
    endpoint: https://git.liteyuki.icu/api/packages/{owner}/pypi    # This is the default value
    files: /path/to/files/*   
```
