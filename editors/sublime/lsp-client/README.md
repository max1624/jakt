# LSP client

Some basic LSP support that probably needs plent of work for Sublime Text.

## Install

1. Apply the syntax file as per parent directory instructions
2. symlink this directory into the same package directory with folder name `LSP-jakt`
3. Restart

## Configuration

Open configuration file using command palette with `Preferences: LSP-jakt Settings` command or opening it from the Sublime menu (`Preferences > Package Settings > LSP > Servers > LSP-jakt`).

Set `jaktLanguageServer.compiler.executablePath` with the path to your yakt executable
For example `~/.cargo/bin/jakt`

This currently includes a compiled version of the LSP server under `vscode/server/src/server.ts`
This can be regenerated by running `tsc` in this directory