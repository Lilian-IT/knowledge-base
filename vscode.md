//install from file
cat vscode-extensions.list | xargs -L 1 code --install-extension

//write to file
code --list-extensions > vscode-extensions.list