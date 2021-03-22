# Installfest

- [x] [Github and Initial Setup](github.md)
- [x] [Git](git.md)
- [x] [Bash Configuration](bash.md)
- [x] [Command Line Tools - Xcode (macOS only)](command_line_tools.md)
- [x] [Homebrew](homebrew.md)
- [x] [Node](node.md)
- [x] [Python](python.md)
- [x] [Chrome](chrome.md)
- [ ] **VS Code**

## VS Code

If you do not already have Visual Studio Code, [download here](https://code.visualstudio.com/download).

**Important**: When done installing, if you are on a Mac, be sure to click and drag VS Code into your Applications folder. If you skip this step, any custom configurations will be lost each time you reopen VS Code.

![Click application and drag to Applications folder](https://i.imgur.com/Cd0B9hW.png)

### Launching VS Code from Terminal

- Open VS Code by clicking on the icon in your dock, OR by opening your search `cmd` + `space` and typing `vscode`.
- To be able to launch VS Code from your terminal: open the Command Palette (⇧⌘P) and type 'shell command' to find the Shell Command: Install 'code' command in PATH.

![install shell commands](https://i.imgur.com/il5eKGh.png)

- You might need to quit terminal _and_ VS Code (`cmd` + `q`) in order for this to take effect.
- Make sure you are `quitting` terminal and VS Code, not just closing the program to install shell commands.


#### ALTERNATIVE: Use the Command Line

1. Open the terminal.
1. Copy and paste the following lines into the terminal: 

```bash
cat << EOF >> ~/.bash_profile
# Add Visual Studio Code (code)
export PATH="\$PATH:/Applications/Visual Studio Code.app/Contents/Resources/app/bin"
EOF
```

#### How do I know it worked?

1. Open terminal.
2. Type the command `code --help` into terminal. If you see some help options, you successfully installed the `code` command.

### Configure VS Code as your default Git commit/diff tool

From the command line, run the following command from any directory: `git config --global core.editor "code --wait"`

> This is especially important if you have previously used other code editors on your system.

### Install VS Code Extensions

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




