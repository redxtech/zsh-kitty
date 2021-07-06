# kitty
> kitty is a zsh plugin that provides completions for the `kitty` terminal emulator.

## Installing

### zinit
Add this to your zinit config (.zshrc):
```zsh
zinit light redxtech/zsh-kitty

# it also works with turbo mode:
zinit ice wait lucid
zinit load redxtech/zsh-kitty
```

### oh-my-zsh
Install it with your favourite zsh package manager, or clone it directly to your
`$ZSH_CUSTOM/plugins` directory with git, and add `zsh-kitty` to the plugins
array in your `.zshrc` file:

```zsh
plugins=(... zsh-kitty)
```

## Usage
Once you install it, you just need to run `__kitty_complete` (put it somewhere in your `.zshrc`
after loading your plugins), and completions for the `kitty` command should work!

## Author
**kitty** © [Gabe Dunn](https://github.com/redxtech), Released under the [MIT](./license.md) License.

