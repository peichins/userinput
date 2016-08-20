## Synopsis

An R package that provides some functions for reading user input from the console. 
It is a wrapper for readline which does things like 
- format multiple choice and validate inputted values (similar to utils::menu).
- validate a user specified directory by checking if it exists
- allow multi-select menu

## Installation

In R, if not already installed, install devtools package.

```
install.packages('devtools')
```

Then use devtools to install datatrack, dviewer and userinput from github

```
devtools::install_github("peichins/userinput")
```

## License

GPL-2

## Versioning

This project uses semantic versioning

(http://semver.org/)
