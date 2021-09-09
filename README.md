# hashtagchris-simple-extension README

For basic VS Code testing

## Features

1. Writes `PATH` to the `hashtagchris-simple-extension` output channel.
1. Writes all environment variables to the output channel.
1. Executes `dotnet --info` and logs output to the output channel.

## Installing the extension

https://code.visualstudio.com/api/working-with-extensions/publishing-extension

1. `npm install -g vsce`
1. `vsce package`
1. Find the vsix in the side bar, right-click and select "Install Extension VSIX"

## Requirements

You can optionally install dotnet.

## Extension Settings

None

## Known Issues

None

## Release Notes

### 0.0.1

Initial release