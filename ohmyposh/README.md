# To use this config in your system

1) Make Sure oh-my-posh is installed and configured including it's dependencies.
2) Your environment variable should be all set for your terminal (zsh/ bashrc).
3) Make a `ohmyposh` directory inside `.config`.
    ```bash
    mkdir .config/ohmyposh
    ```
4) Export the deafult configuration into the new folder created.
    ```bash
    oh-my-posh config export --format toml --output ~/.config/ohmyposh/zen.toml
    ```
5) Add this newly created file to path.
    For bash:
    - Inside the .bashrc file add
    ```bash
    eval "$(oh-my-posh init bash --config $HOME/.config/ohmyposh/zen.toml)"
    ```
    For zsh:
    - Inside the .zshrc file add
    ```bash
    eval "$(oh-my-posh init zsh --config $HOME/.config/ohmyposh/zen.toml)"

6) Replace the contents of `zen.toml` with the one from this directory.

*NOTE:*
The colors are a bit off at the moment, you're more than welcome to change them as per your taste.

I wil find good set of colors and replace the propritory ones as soon as possible.
