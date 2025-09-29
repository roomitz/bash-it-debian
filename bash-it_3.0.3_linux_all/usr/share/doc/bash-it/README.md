# Bash-it

Bash-it is a collection of community Bash commands and scripts for Bash 3.2+.

Includes autocompletion, themes, aliases, custom functions, a few stolen pieces from Steve Losh, and more.

Bash-it provides a solid framework for using, developing and maintaining shell scripts and custom commands for your daily work. 
If you're using the *Bourne Again Shell* (Bash) regularly and have been looking for an easy way on how to keep all of these nice little scripts and aliases under control, then Bash-it is for you! 
Stop polluting your `~/bin` directory and your `.bashrc` file, fork/clone Bash-it and start hacking away.

## Main Pages and Documentation

- Main Page: https://bash-it.readthedocs.io/en/latest
- Contributing: https://bash-it.readthedocs.io/en/latest/contributing
- Installation: https://bash-it.readthedocs.io/en/latest/installation/
- Help: https://bash-it.readthedocs.io/en/latest/misc/#help-screens
- Search: https://bash-it.readthedocs.io/en/latest/commands/search/
- Custom scripts, aliases, themes, and functions: https://bash-it.readthedocs.io/en/latest/custom/
- Themes: https://bash-it.readthedocs.io/en/latest/themes
- Uninstalling: https://bash-it.readthedocs.io/en/latest/uninstalling
- Contributors: https://github.com/Bash-it/bash-it/contributors

## Installation

1. Clone this repository to a location of your choice, for example:

git clone --depth=1 https://github.com/Bash-it/bash-it.git ~/.bash_it

2. Run the installer script:

~/.bash_it/install.sh

That's it!

You can check out more components of Bash-it, and customize it to your desire.
For more information, see the detailed instructions on the main documentation page.

### custom configuration file location

By default the instller modifies/creates the actual ``~/.bashrc`` is updated.
If this is undesirable, you can create another file, by run the installer:

BASH_IT_CONFIG_FILE=path/to/my/custom/location.bash ~/.bash_it/install.sh


## Contributing

Please take a look at the Contribution Guidelines https://bash-it.readthedocs.io/en/latest/contributing before reporting a bug or providing a new feature.

The Development Guidelines https://bash-it.readthedocs.io/en/latest/development have more information on some of the internal workings of Bash-it,
please feel free to read through this page if you're interested in how Bash-it loads its components.

## Contributors

List of contributors https://github.com/Bash-it/bash-it/contributors

## License

Bash-it is licensed under the MIT License https://github.com/Bash-it/bash-it/blob/master/LICENSE.
