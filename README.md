# MC Assistant

[![Npm](https://img.shields.io/npm/v/mc-assistant.svg)](https://www.npmjs.com/package/mc-assistant) [![CircleCI](https://circleci.com/gh/mattlubner/mc-assistant.svg?style=shield)](https://circleci.com/gh/mattlubner/mc-assistant) [![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)

MC is a command-line assistant for developers.

## Getting Started

Use yarn to globally install, via:

```bash
yarn global add mc-assistant
```

## Commands

#### `mc hi <project_name> <project_path>`
Registers a new project path and name with mc-assistant.

#### `mc in <project_name> <shell_commands>`
Runs any arbitrary shell commands within the registered project's directory, without changing the shell's current working directory.

#### `. mc go <project_name>`
Change the shell's current working directory to the registered project's directory. Useful in combination with `cd -` (to change back).

## Contributing

Contributors welcome! Please feel free to fork and submit pull requests to fix issues. Feature requests should be submitted as issues initially, to vet whether they make sense to add to `mc-assistant`.

All contributors are expected to abide by the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/).

Run `yarn link` to get in-development local binaries into your shell (remember to `yarn unlink` afterwards 😛).

_**IMPORTANT!** All commits must adhere to the [semantic-release naming convention](https://semantic-release.gitbooks.io/semantic-release/content/#commit-message-format), in order to properly calculate the npm version increment and auto-publish to the npm registry._

## License

[MIT](https://github.com/mattlubner/mc-assistant/blob/master/LICENSE)
