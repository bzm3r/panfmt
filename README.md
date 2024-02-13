# panfmt

## Features

Format CommonMark files with `pandoc`!

## Requirements

Make sure you have the `pandoc` executable available on `PATH`, or
specify where it is located using the option `panfmt.pandocExePath`.

## Extension Settings

This extension contributes the following settings:

``` json
"panfmt.enabled": {
    "type": "boolean",
    "default": true,
    "description": "Enable panfmt as a markdown/typst formatter."
},
"panfmt.pandocExePath": {
    "type": "string",
    "default": "pandoc",
    "description": "Path to pandoc executable to use for formatting operations."
},
"panfmt.extraArgs": {
    "type": "array",
    "default": [],
    "description": "See https://pandoc.org/MANUAL.html#options"
}
```

## Known Issues

Check this repository's Issues tab for known issues.
