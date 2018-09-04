# Python String HTML 
> Hopefully ready to add to the VSCode Marketplace soon

Adds syntax highlight support for code, placed in python multiline strings:
- HTML (incl. html quoted and unquoted attrs)
- SQL

## Community
- 2018-09-04 forked from [es6-string-css](https://github.com/bashmish/es6-string-css) - Highlight CSS in ES6 template literals

## Installation

- Install `python-string-html` from extensions (`ctrl + shift + x`)

## Example

![Example](docs/demo.png)

## Usage

Simply insert the comment /\*html\*/ or `html` (or sql instead of html) before the string
(see Requirements "section" for possible values) or select
`Insert python-string-html comment/template` from the commands menu
(`ctrl+shift+p` or `f1`)

> Tip: Comment in the beginning of python string is required

## Requirements

- Visual Studio Code v1.19.0 recommended
- Comment `/*html*/` before the string. Possible values:
- - `/*html*/`
- - `/*inline-html*/`
- - `/*template*/`
- - `/*inline-template*/`
- Or
- - `html` before the string

## Keybindings
- `ctrl+shift+h` - Insert `/*html*/`
- `ctrl+k h` - Insert `/*html*/` \`\`

## Donation

If this project help you reduce time to develop, you can give the original develper a cup of coffee :)

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=68P8BFSZPG5H2)

## Release Notes

### [0.0.0] - 2018-09-04
- Forked from es6-string-html

-----------------------------------------------------------------------------------------------------------

**Enjoy!**
