# Neovim Projector VSCode Loader

Extension for [nvim-projector](https://github.com/kndndrj/nvim-projector) that adds 2 additional loaders for:
- tasks.json
- launch.json

## tasks.json
  - module: `tasksjson`
  - opt:  `string`
    - `string`: path to `tasks.json` - default: `./.vscode/tasks.json`
  - variable expansion: VsCode like variables (e.g. `${file}`)

## launch.json
  - module: `launchjson`
  - opt:  `string`
    - `string`: path to `launch.json` - default: `./.vscode/launch.json`
  - variable expansion: VsCode like variables (e.g. `${file}`)