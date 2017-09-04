# IDE Configurations

Clone this repo on your local and enjoy the benefits of many integrations which will help you test, debug and prettify on the fly!

## Web Configuration

### WebStorm

#### Getting started

1. Go to `File | Import Settings`
2. Select the `settings.jar` inside `web/webstorm`
3. Copy the `runConfigurations` folder from `web/webstorm` to `root-of-project-you-working/.idea/`. Here's the command `cp -r path-to-ide-configurations-repo/web/webstorm/runConfigurations root-of-project-you-working/.idea`
3. Restart WebStorm, and you are ready to go!

#### Shortcuts

1. Prettify the file:

- Press `Command + Shift + A` and type `Prettier Fix`. Press enter to beautify the code.

2. Live debug the app:

- Install chrome plugin [here](https://chrome.google.com/webstore/detail/jetbrains-ide-support/hmhgeddbohgjknpmjagkdomcpobmllji?hl=en)
- Run the app by `yarn start`
- Press `option + ctrl + r` and select debug app
- All the console statements and breakpoints are available inside your ide now! No need to open google console

3. Run tests

- Press `option + ctrl + r` and select `Test`

### Visual Studio Code

#### Getting started

1. Copy the `extensions` folder to your systems's `.vscode` folder: 
    `cp -r path-to-ide-configurations-repo/web/vscode/extensions ~/.vscode/`
2. Copy the `.vscode` folder to your project's root folder: 
    `cp -r path-to-ide-configurations-repo/web/vscode/.vscode root-of-project-you-working/`