# ant-ext-tools
Launch ant (using maven dependencies) with current file in intellij as an argument.


## Add External Tools
File > Settings > Tools > External Tools

Program: ant

Arguments: run -DfileName=$FilePathRelativeToProjectRoot$

Working dir: $ProjectFileDir$


## Shortcup
File > Settings > Keymap > External Tools

