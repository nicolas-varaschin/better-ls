# better-ls
ls with customizable icons and colors, expanded off of ryanoasis' [nerd-fonts](https://github.com/ryanoasis/nerd-fonts) and [devicons-shell](https://github.com/ryanoasis/devicons-shell).

![better-ls usage.](http://imgur.com/Gm3Y4k1.png)

## Features

  - Columnizes output
  - Windows support! (MinTTY)
  - Contains predefined icons for many file types
  - Has support for additional file type icon descriptions, which are easily added

## Installation
  - If you don't have nerd-fonts, run ./install-fonts.sh . This installs only the necessary fonts.
  - Make a symlink or copy .lsicons.py to your $PATH

## Usage
  - ./lsicons outputs the columnized version, just like the picture
  - ./lsicons -l is analogous to ls -la
  - ./lsicons -d [DIR] executes the script in other directory

Pull requests (esp. those containing file type expansions) are welcome!
