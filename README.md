# @grafbase/install-grafbase-cli

A simple GitHub Action to install the [Grafbase CLI](https://grafbase.com/cli).

## Usage

Install the latest version of the Grafbase CLI:

```yaml
- name: Install Grafbase CLI
  uses: grafbase/install-grafbase-cli@v1
```

Install a specific version:

```yaml
- name: Install Grafbase CLI
  uses: grafbase/install-grafbase-cli@v1
  with:
    version: 0.82.4
```
