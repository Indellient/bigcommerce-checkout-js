# Devcontainer

Creates the environment in a development container, and allows you to install features.

## Current Implementation

1. node v16.20.0
2. npm 8.19.4
3. Debian GNU/Linux 11 (bullseye)

## Important Information

In order for the remote-containers extension to read the devcontainer definition, the `.devcontainer` folder must be unique and in the root of the VSCode workspace.

## How to use the devcontainer

1. Open the repository folder in VSCode.
2. Install the remote-containers extension: `ms-vscode-remote.remote-containers`.
3. Click bottom left corner `><`.
4. Select "Reopen in Container".
5. Wait for the build, click "see logs" at the bottom right to watch the build.

## Aditional Information

1. For features maintained by Microsoft, see [features](https://github.com/devcontainers/features).
2. To install features not supported by the devcontainer/features repository, use the "postStartCommand" attribute in `devcontainer.json`
3. To understand the capabilities of the `devcontainer.json` spec, check the [devcontainer schema](https://containers.dev/implementors/json_schema/)
