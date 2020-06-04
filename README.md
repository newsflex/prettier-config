# `@newsflex/prettier-config`

> NewsFlex [Prettier](https://prettier.io) config.

## Usage

**Install**:

```bash
$ npm i --save-dev newsflex/prettier-config
```

**Edit `package.json`**:

```jsonc
{
  // ...
  "prettier": "@newsflex/prettier-config
}
```


## Visual Studio Code Integration

In the workspace file `.vscode/settings.json` set:

```json
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": true
```

or for more control over which files try: 

```json
    "[javascript]": {
        "editor.formatOnSave": true
    },
    "[typescript]": {
        "editor.formatOnSave": true
    },
    "[json]": {
        "editor.formatOnSave": true
    },
    "[yaml]": {
        "editor.formatOnSave": true
    },
    "[html]": {
        "editor.formatOnSave": true
    },
    "[scss]": {
        "editor.formatOnSave": true
    },
```