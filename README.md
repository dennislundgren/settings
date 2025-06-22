# Settings

Code setup for consistency, speed, and cross-environment productivity.

## VS Codeq

### Plugins
- [Bearded Theme](https://marketplace.visualstudio.com/items?itemName=BeardedBear.beardedtheme)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
- [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)
- [GitHub Copilot Chat](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot-chat)
- [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
- [multi-command](https://marketplace.visualstudio.com/items?itemName=ryuta46.multi-command)

### User settings
1. Open the Command Palette (`Cmd+Shift+P`)
2. Search for `Open User Settings (JSON)`
3. Replace content with [settings.json](/settings.json)

### Key bindings
1. Open the Command Palette (`Cmd+Shift+P`)
2. Search for `Open Keyboard Shortcuts (JSON)`
3. Replace content with [keybindings.json](/keybindings.json)

## RayCast

### Installation
1. Download from [raycast.com](https://www.raycast.com)
2. Set up and override Spotlight (`Cmd+Space`) if prompted

### Extensions
1. Open RayCast (`Cmd+Space`) → Settings (`Cmd+,`) → Extensions → `+` → Install from Store
2. Search and install:
   - `brew` (requires [Homebrew](https://brew.sh))

Using `brew` via RayCast, install casks:
- `hiddenbar`
- `rectangle`

### Script commands
1. Create a scripts directory, e.g. `~/.scripts`
2. In RayCast: Settings → Extensions → `+` → Add Script Directory
3. Create a new script command

Example script to open the directory:

```bash
#!/bin/bash
# @raycast.schemaVersion 1
# @raycast.title Code scripts
# @raycast.mode compact
# @raycast.icon 🤖
# @raycast.description Open scripts directory
# @raycast.author <your name>

code /Users/<your name>/.scripts
```
