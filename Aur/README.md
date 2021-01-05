# AUR ( Arch User Repository) Package Downloader

### Prerequisite

```
- Any type of Shell installed ( bash, zsh, fish )
- Git
```

### Clone the repository

```
git clone https://github.com/knight-byte/Scripts.git
cd Scripts/Aur
```

### Usage

> For accessing the Scripts from any Directory or location in your System

- Create a Directory named `bin` in your home Directory
- Copy the `aur` bash Script and paste in the bin directory
- Add the bin directory in your home path and add that home path in Path ( If you havent set yet )

  - add this line in your `.bashrc` or `.zshrc` or shell configuration of your shell you are using

  ```
  PATH="$HOME/bin:$PATH
  ```

- You are good to go Now you can access the Script in the bin directory from and Directory or location in terminal.

To install aur package from any package just type in terminal

```
aur <package name>
```

eg. installing Spotify

```
aur spotify
```

Done

### Note

Change the Shebang\* of the Script if you are Using the Different Shell or the path of the shell doesnt match with the default location of the shell installed

> `A shebang is the character sequence consisting of the characters number sign and exclamation mark ( #!) at the beginning of a script. `

Made with ❤ in India
