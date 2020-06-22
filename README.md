## Updating The Terminal Prompt

In Mac OSx Cataline, Apple switched the default shell to use **zsh** instead of **bash**.

As a result, the prompt must now be edited in the **zsh** profile when using default settings. While it's possible to still use **bash** in Terminal, it hasn't been updated in many years.

The best place to modify your prompt is in the `.zshrc` file. You can edit this with **nano** using the following command: `nano ~/.zshrc`. If there is no `PROMPT` line, you can add one at the beginning of the file. 

Using different prompt expansions, you can fully customize Terminal. The default prompt is `PROMPT="%n@%m %1~ %# "`

The full list of prompt expansion options can be found [here](http://zsh.sourceforge.net/Doc/Release/Prompt-Expansion.html#Prompt-Expansion).

I've also found [this guide](https://scriptingosx.com/2019/06/moving-to-zsh-part-2-configuration-files/) to be particularly helpful.
