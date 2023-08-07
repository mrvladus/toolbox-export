# toolbox-export
Script for exporting application's from toolbox or any other containers.

It's exporting .desktop files to `~/.local/share/applicatios` and app icons to `~/.local/share/icons`

## Install
```bash
wget https://raw.githubusercontent.com/mrvladus/toolbox-export/main/toolbox-export.py -O ~/.local/bin/toolbox-export
```

## Usage

Enter the container. For toolbox run:
```
toolbox enter
```
Run command:
```
toolbox-export APP
```
For exapmple, if you want to export VSCode run:
```
toolbox-export code
```
