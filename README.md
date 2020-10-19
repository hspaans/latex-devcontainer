# Devcontainer for Latex

## Using within you project

Add `.devcontainer/devcontainer.json` to your repository.

```json
{
  "name": "LaTeX",
  "image": "ghcr.io/hspaans/latex-devcontainer:latest",
  "settings": {
    "terminal.integrated.shell.linux": "/bin/bash"
  },
  "appPort": [],
  "postCreateCommand": "",
  "remoteUser": "vscode",
  "extensions": [
    "editorconfig.editorconfig",
    "github.vscode-pull-request-github",
    "redhat.vscode-yaml",
    "james-yu.latex-workshop"
  ]
}
```
