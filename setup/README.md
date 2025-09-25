# setup
An action to setup Node with `pnpm` and caching.

## Usage

The following example yaml code will setup Node 20.x environment with pnpm and caching `pnpm-lock.yaml`.

```yaml
- name: Setup Node
  uses: actions-ext/node/setup@v1
  with:
    version: '20.x'
    js_folder: 'js'
```
