# WordPress and Base automated installer
Basic command-line tool to install the latest version of WordPress and [Base](https://github.com/armazemcriativo/base) boilerplate theme.

### Tasks

* Downloads latest version of WordPress and renames the directory to the project name you've given
* Creates .gitignore file with basic 'ignorable' files/directories
* Removes pre-installed WordPress plugins and themes
* Installs Base (and renames it to the project name you've given) and all its submodules
* Installs npm dependencies

### Installation

```
git clone https://github.com/armazemcriativo/base-automated-installer.git
chmod +x base-automated-installer/base
mv base-automated-installer/base /usr/local/bin
rm -rf base-automated-installer
```

### Usage

Just run `base name_of_the_project`, enter your admin password when asked (in order to install node modules), and it's done.

*The name_of_the_project will be used for your project directory such as the theme directory.*
