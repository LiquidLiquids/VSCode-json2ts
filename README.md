# json2ts for Visual Studio Code

## Changes
First character of key is not converted to lower case.

## Installation 
~~json2ts is a VSCode Extension which converts a JSON to TypeScript interfaces.
You can browse and install extensions from within VS Code. Press `Ctrl+P` and narrow down the list commands by typing `ext install json2ts`.~~

1.clone this project or download zip

2.run npm install & npm install vsce -g

3.run vsce package

4.run code --install-extension json2ts-0.0.6.vsix

5.restart vscode

### Usage
json2ts converts a JSON from clipboard to TypeScript interfaces with `cmd+alt+V` or `ctrl+alt+V`.

![json2ts Screenshot](https://github.com/GregorBiswanger/VSCode-json2ts/blob/master/images/json2ts.gif?raw=true)

Another way is, to copy a REST-Service URL to clipboard and insert TypeScript interfaces with `cmd+alt+X` or `ctrl+alt+X`.

![json2ts Screenshot](https://github.com/GregorBiswanger/VSCode-json2ts/blob/master/images/json2ts.REST-URL-Support.gif?raw=true)

### Contributing
Feel free to submit a pull request if you find any bugs (to see a list of active issues, visit the [Issues section](https://github.com/GregorBiswanger/VSCode-json2ts/issues)).
Please make sure all commits are properly documented.

### License
MIT-licensed

** Enjoy! **