# My Extension

My Extension is a basic VSCode extension written in TypeScript that adds a command to the Command Palette.

## Prerequisites

Before you can build and run the extension, you must have the following software installed on your machine:

- [Visual Studio Code](https://code.visualstudio.com/)
- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)

## Installation

To install the extension, follow these steps:

1. Clone the repository:

```
git clone https://github.com/your-username/my-extension.git
```

2. Install the dependencies:

```
cd my-extension
npm install
```

## Building the Extension

To build the extension, run the following command:

```
npm run build
```

This will compile your TypeScript code into JavaScript and place it in the `out` folder.

## Running the Extension

To run the extension, press F5 to launch a new instance of Visual Studio Code with your extension loaded.

Open the Command Palette (Ctrl/Cmd + Shift + P) and type "Say Hello". You should see your new command in the list. Select it to execute the command and see the "Hello World!" message.

## Modifying the Extension

To modify the extension, edit the `extension.ts` file in the `src` folder of your extension.

When you're ready to test your changes, rebuild the extension by running the following command:

```
npm run build
```

Then, press F5 to launch a new instance of Visual Studio Code with your updated extension loaded.

## License

My Extension is released under the [MIT License](LICENSE).