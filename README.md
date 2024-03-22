# Setup Powerpipe for GitHub Actions

<p align="center">
  <a href="https://github.com/turbot/powerpipe-action-setup/actions"><img alt="powerpipe-action status" src="https://github.com/turbot/powerpipe-action-setup/workflows/units-test/badge.svg"></a>
</p>

This action installs [Powerpipe](https://github.com/turbot/powerpipe/).

## Usage

See [action.yml](action.yml).

## Examples

### Install the latest version Powerpipe

```yaml
- name: Install Powerpipe
  uses: turbot/powerpipe-action-setup@v1
```

### Install a specific version of Powerpipe

```yaml
- name: Install Powerpipe v0.1.3
  uses: turbot/powerpipe-action-setup@v1
  with:
    powerpipe-version: 0.1.3
```

> For available Powerpipe versions refer to [Powerpipe Releases](https://github.com/turbot/powerpipe/releases).


## Helpful Links

- [Powerpipe docs](https://powerpipe.io/docs)
