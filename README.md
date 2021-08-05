# dosh

> Drop into a Docker container shell anywhere

`dosh` drops you into a temporary Docker container shell at any time with the hosts current working directory mapped to the containers current working directory.

While all execution is sandboxed in the temporary container, changes in the filesystem of the current working directory will be persisted on the host.

This gives you a safe temporary environment to execute untrusted code. Perfect for installing project dependencies during development, executing suspicious binaries, or doing anything you don't want to give full access to your system.

## Usage

TODO

## License

MIT © Umbrel, Inc
