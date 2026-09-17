<<<<<<< HEAD
# starship-bash-fastfetch-dot-files
=======
# Fastfetch 

<h3 align="left">
Welcome to my Half-Life-themed Starship and Fastfetch dotfiles repository!

(Still waiting for the third game? Oh...)

</h3>

Probabliy you already know that [Fastfetch](https://github.com/fastfetch-cli/fastfetch) is a tool for fetching system information and displaying them in your screen. 
In this repo, I save my dot files for Starship and Fastfetch that I designed for my Nobara Linux and Arch Linux setup rices. 
Feel free to copy files and modify them or clone the complete repository.

<p align="center">
  <img src="~/fastfetch/screenshots/Nobara-Linux-dot.png" style="width: 100%;">
</p>
<p align="center">
  <img src="~/fastfetch/screenshots/Arch-Linux-dot.png" style="width: 100%;">
</p>

## Usage

Clone the repository into ``~/.local/share``

```sh
cd ~/.local/share
git clone https://github.com/Ziednaga/starship-bash-fastfetch-dot-files
```
and execute `arch` or `nobara` files (e.g. ``arch.jsonc`` or ``minimal.jsonc``) with 

```sh
fastfetch --config nobara
fastfetch --config arch
```

Or also you can copy your preferred config file (if necessary images/ascii-art files), rename it to ``config.jsonc``, move it to ``~/.config/fastfetch`` and execute it with 

```sh
fastfetch
# or with additional options e.g.
fastfetch --colors-block-range-start 4 --colors-block-width 2
```
>>>>>>> 8646173 (first commit)
