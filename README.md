# Breakbot
Quickly add disruptive unicode, dangerous strings, and more to your clipboard.

BreakBot is MIT licensed and open source; contribute at https://github.com/jkingsman/Breakbot.

## Usage
You can get Breakbot from the Chrome store, or run `gulp` and import the `dist` directory as an unpacked extension. Click the cracked egg icon on your toolbar to expand a searchable list of naughty strings.

## Installation

### Manual

> You'll need node and npm set up on your system (which is beyond the scope of this README), and gulp installed (`npm install -g gulp` if you don't already have it).

1. Clone this repo:

  `git clone https://github.com/jkingsman/Breakbot.git`

2. Move into it:

  `cd Breakbot`

2. Install the gulp dependencies:

  `npm install`

3. Make sure the build directory is empty:

  `gulp empty`

4. Build it, using any of the following commands:

| `gulp` command  | result |
| ------------- | ------------- |
| `gulp`  | Lint the code and build the `src` directory into the `dist` directory. `dist` can be imported as an unpacked extension.  |
| `gulp zip`  | Lint the code and build the `src` directory into the `dist` directory, then zip the `dist` directory into `Breakbot.zip` in the root `BreakBot` folder.  |
| `gulp watch`  | Build the `src` directory into the `dist` directory and rebuild on changes to `src`.  |

## License
MIT.

***
