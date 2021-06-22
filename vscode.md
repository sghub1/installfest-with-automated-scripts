# Installfest

- [x] [Github and Initial Setup](github.md)
- [x] [Git](git.md)
- [x] [Command Line Tools - Xcode (macOS only)](command_line_tools.md)
- [x] [Homebrew](homebrew.md)
- [x] [Node](node.md)
- [x] [Python](python.md)
- [x] [Chrome](chrome.md)
- [ ] **Install a Text Editor**

If you do not already have one of the text editors below please choose one, either is fine: 

## Sublime 
[Download Here](https://www.sublimetext.com/download)

## Atom 
[Download Here](https://atom.io/)


## VS Code
[Download Here](https://code.visualstudio.com/download).


**Important**: When done installing, if you are on a Mac, be sure to click and drag the text editor you installed into your Applications folder. If you skip this step, any custom configurations will be lost each time you reopen your text editor.

![Click application and drag to Applications folder](https://i.imgur.com/Cd0B9hW.png)

### Launching from Terminal

#### Sublime
- Open Sublime by clicking on the icon in your dock, OR by opening your search `cmd` + `space` and typing `subl`.
- To be able to launch Sublime from your terminal: open the Command Palette (⇧⌘P) and type 'shell command' to find the Shell Command: Install 'subl' command in PATH.

#### Atom
- Open Atom by clicking on the icon in your dock, OR by opening your search `cmd` + `space` and typing `atom`.
- To be able to launch Atom from your terminal: open the Command Palette (⇧⌘P) and type 'shell command' to find the Shell Command: Install 'atom' command in PATH.

#### VS Code 
- Open VS Code by clicking on the icon in your dock, OR by opening your search `cmd` + `space` and typing `vscode`.
- To be able to launch VS Code from your terminal: open the Command Palette (⇧⌘P) and type 'shell command' to find the Shell Command: Install 'code' command in PATH.

![install shell commands](https://i.imgur.com/il5eKGh.png)

- You might need to quit terminal _and_ your text editor of choice (`cmd` + `q`) in order for this to take effect.
- Make sure you are `quitting` terminal and the text editor, not just closing the program to install shell commands.


#### How do I know it worked?

1. Open terminal.
2. Type the command `subl --help` , `atom --help` or`code --help` into terminal. If you see some help options, you successfully installed the `subl, atom or code` command.


### Install VS Code Extensions (If you are using VS Code) 

VS Code has numerous extensions that make developers' lives easier! We will be installing a few essential ones right now:

```
"ritwickdey.liveserver",
"dbaeumer.vscode-eslint",
"esbenp.prettier-vscode",
```

### Recommended but no required
```
"coenraads.bracket-pair-colorizer",
"christian-kohler.path-intellisense",
```

> Quit your instance of VS Code and reopen for the newly-installed extensions to take effect!




