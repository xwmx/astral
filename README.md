```text
                   `..                    `..
                   `..                    `..
   `..     `.... `.`. `.`. `...   `..     `..
 `..  `.. `..      `..   `..    `..  `..  `..
`..   `..   `...   `..   `..   `..   `..  `..
`..   `..     `..  `..   `..   `..   `..  `..
  `.. `...`.. `..   `.. `...     `.. `...`...
```

# astral

A Zsh Theme with Zen Mode.

In normal mode, the `astral` prompt consists of 3 lines:

- Return Line: Displays the duration of the previous command and the time and date that the command exited. The return line is displayed in red when a command returns with an error status.
- Context Line: Displays the machine name, current path, and ssh status. When in a project directory, the context line also displays git status and language version information.
- Prompt line: Displays a simple prompt using color to indicate the return status of the last command.

`astral zen` mode hides the return and context lines, leaving just the prompt.

## ❯❯❯❯

<p align="center">
  <img src="https://raw.githubusercontent.com/xwmx/astral/master/astral.png" alt="astral preview" width="800">
</p>

Recommended:
- <https://github.com/chriskempson/base16-shell>
- <https://github.com/zsh-users/zsh-syntax-highlighting>
