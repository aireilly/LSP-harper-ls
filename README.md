# LSP-harper-ls

LSP-harper-ls is a helper package that automatically installs and updates [`harper-ls`][1] for [Sublime Text][4].

Read more about [Harper English grammar checker][5]. 

## Requirements

To use this package, you must have the [LSP][3] package installed.

> It's recommended, but not required, to install the [LSP-json][2] package which will provide auto-completion and validation for this package's settings.

## Configuration

There are multiple ways to configure the package and the language server.

- Global configuration: `Preferences > Package Settings > LSP > Servers > LSP-harper-ls`
- Project-specific configuration:
  From the Command Palette run `Project: Edit Project` and add your settings in:

    ```js
    {
        "settings": {
            "LSP": {
                "LSP-harper-ls": {
                    "initializationOptions": {
                        // Put your settings here
                    }
                }
            }
        }
    }
    ```

## Installation

Add `https://github.com/aireilly/LSP-harper-ls` using `Package control: Add repository` in Sublime Text, and then install `LSP-harper-ls` using Package control.

[1]: https://github.com/elijah-potter/harper/tree/master/harper-ls
[2]: https://packagecontrol.io/packages/LSP-json
[3]: https://packagecontrol.io/packages/LSP
[4]: https://www.sublimetext.com/
[5]: https://github.com/elijah-potter/harper
