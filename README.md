# clstyles
A simple module for styling command line outputs.

## Features

- **Color Formatting:** Apply colors to command line outputs.
- **Bold Styling:** Make command line outputs bold.

## Install

To install, run:

```bash
npm install clstyles
```

## Usage

Import the styledText function and use it to style your console output:

```js
import { styledText } from 'clStyles';

// Output: Bold green text
console.log(styledText("Hello World", "\x1b[32m", true));
```

## Colors

You can enter any ANSI color code you want. If you want a collection of them for convenience, [install clcolors](https://github.com/kaidx3/clcolors).


## Parameters
  - **text:** The string you want to format.
  - **color:** the ANSI color code for your text.
  - **isBold (optional):** A boolean to make the text bold.
