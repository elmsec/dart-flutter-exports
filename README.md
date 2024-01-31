# Dart & Flutter Exports

The Dart & Flutter Exports extension automates the creation of Dart exporter files in your Dart or Flutter project, making it easier to manage and organize your code structure.

## Features

The extension provides the following features:

- **Recursive Export File Creation**: Automatically generates exporter files (`folder_name.dart`) recursively in specified directories.
- **Overwrite Confirmation**: Prompts the user to confirm overwriting existing exporter files or skip the current folder.
- **Intelligent Export Checks**: Improved checks to identify existing exporter files and avoid overwriting non-exporter files.

## Usage
Simply right click on a folder in your Dart/Flutter project and click on the "Generate Dart export files" option. 

Remember that this operation works recursively, meaning that it will also create export files for subfolders.

## Demo
<video src="https://elma.dev/_files/dart-exports.mp4" controls></video>

https://github.com/elmsec/dart-flutter-exports/assets/42157155/5a1be88c-56c7-4cd6-a3af-3dc2e99049ff


## Requirements

No additional requirements or dependencies are needed for this extension.

## Extension Settings

The extension does adds a new option to the context menu of the Explorer view. You can right-click on any folder in your project and select the `Generate Dart Export Files` option to start the process.

## Known Issues

No known issues currently. Feel free to report any problems you encounter.

## Release Notes

Please check the [CHANGELOG](CHANGELOG.md) for more information.

## Tests

To run the tests, you can use the `npm test` command.

**Enjoy!**
