# toolbox-export
Script for exporting applications from toolbox or any other containers.

It's exporting .desktop files to `~/.local/share/applicatios` and app icons to `~/.local/share/icons`

## Install
Make sure you have `~/.local/bin` in your `PATH` and `curl` is installed.
```bash
curl https://raw.githubusercontent.com/mrvladus/toolbox-export/main/toolbox-export.py --create-dirs -o ~/.local/bin/toolbox-export && chmod +x ~/.local/bin/toolbox-export
```

## Usage

Enter the container. For toolbox run:
```bash
toolbox enter
```
Run command:
```bash
toolbox-export APP
```
For example, if you want to export VSCode run:
```bash
toolbox-export code
```
