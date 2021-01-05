# Sortthis ( directory/Folder sorter )

### Prerequisite

```
- Any type of Shell installed ( bash, zsh, fish )
- Git
- python >= 3.6
- pip (python package installer )
```

#### This Script is basically a Directory Sorter using command line i.e.

    Terminal in Linux or Mac
    CMD(Command prompt) or PowerShell in Windows

### Clone the repository

```
git clone https://github.com/knight-byte/Scripts.git
cd Scripts/Sortthis
```

### Usage

> For accessing the Scripts from any Directory or location in your System

- Create a Directory named `bin` in your home Directory
- Copy the `sort` bash Script , `pythonScript` folder and paste in the bin directory
- Add the bin directory in your home path and add that home path in Path ( If you havent set yet )

  - add this line in your `.bashrc` or `.zshrc` or shell configuration of your shell you are using

  ```
  PATH="$HOME/bin:$PATH
  ```

- You are good to go Now you can access the Script in the bin directory from and Directory or location in terminal after completion of the sorting process.

To Sort a directory/folder just open terminal in that folder and type

```
sortthis
```

This will prompt user to continue the process or cancel, if typed y (for yes) done message will be in shown in the terminal

## ScreenShots:

### Before Sorting

![before sorting](https://i.imgur.com/1DVzksW.png)

### After sorting

![after sorting](https://i.imgur.com/U1Es5RW.png)

### Note

Change the Shebang\* of the Script if you are Using the Different Shell or the path of the shell doesnt match with the default location of the shell installed

> `A shebang is the character sequence consisting of the characters number sign and exclamation mark ( #!) at the beginning of a script. `

Made with ❤️ in India
