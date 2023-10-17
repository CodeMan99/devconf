# devconf

Create and manage devcontainer configuration.

## Usage

The to see help on input flags.

```shell
$ devconf --help
```

All of the commands depend on a local copy of the _generated_ [collection index](https://github.com/devcontainers/devcontainers.github.io/blob/gh-pages/_data/collection-index.yml). This is downloaded by [oras](https://github.com/oras-project/oras) and saved in the system-dependant data directory.

```shell
$ devconf --pull-index
```

### Features

...

#### devconf init

Use to start a new project. Provide no arguments for the default interactive experience. Use `--help` to learn what can be provided as arguments.

#### devconf inspect

Describe all details of a specific template or feature. The `id` is a required argument. Use as an aid when editing an existing `devcontainer.json`.

#### devconf list

List collections overview. With `--collection-id` option display all features or templates for the given collection.

#### devconf search

Find a template or feature from the official [collections](https://containers.dev/collections).

### Non-Features

This project avoids interop with docker or any editor.

## Contributing

...

## Related Tools

- `devcontainer` - [Official CLI](https://github.com/devcontainers/cli) tool. Primary use is building and executing containers.
- `vscli` - A CLI tool to [launch vscode projects](https://github.com/michidk/vscli), which supports devcontainers.
- `devcon` - [Start devcontainers without vscode](https://github.com/guitsaru/devcon).
- As well as other [supporting tools](https://containers.dev/supporting) in the devcontainer ecosystem.
