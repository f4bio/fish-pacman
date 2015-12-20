### plugin pacman for fundle / oh-my-fish
based on https://github.com/oh-my-fish/plugin-archlinux

## implemented
| Alias        | Function                                | Description                                                                                                         |
|:------------:|-----------------------------------------|:--------------------------------------------------------------------------------------------------------------------|
| pacin        | sudo pacman -S                          | Install specific package(s) from the repositories                                                                   |
| pacins       | sudo pacman -U                          | Install specific package not from the repositories but from a file                                                  |
| pacinsd      | sudo pacman -S --asdeps                 | Install given package(s) as dependencies of another package                                                         |
| pacloc       | pacman -Qi                              | Display information about a given package in the local database                                                     |
| paclocs      | pacman -Qs                              | Search for package(s) in the local database                                                                         |
| paclsorphans | sudo pacman -Qdt'                       | List all orphaned packages                                                                                          |
| pacmir       | sudo pacman -Syy                        | Force refresh of all package lists after updating /etc/pacman.d/mirrorlist                                          |
| pacre        | sudo pacman -R                          | Remove the specified package(s), retaining its configuration(s) and required dependencies                           |
| pacrem       | sudo pacman -Rns                        | Remove the specified package(s), its configuration(s) and unneeded dependencies                                     |
| pacrep       | pacman -Si                              | Display information about a given package in the repositories                                                       |
| pacreps      | pacman -Ss                              | Search for package(s) in the repositories                                                                           |
| pacrmorphans | sudo pacman -Rs $(pacman -Qtdq)'        | Delete all orphaned packages                                                                                        |
| pacupd       | sudo pacman -Sy && sudo abs && sudo aur | Update and refresh the local package, ABS and AUR databases against repositories                                    |
| pacupd       | sudo pacman -Sy && sudo abs             | Update and refresh the local package and ABS databases against repositories                                         |
| pacupd       | sudo pacman -Sy && sudo aur             | Update and refresh the local package and AUR databases against repositories                                         |
| pacupd       | sudo pacman -Sy                         | Update and refresh the local package database against repositories                                                  |
| pacupg       | sudo pacman -Syu                        | Synchronize with repositories before upgrading packages that are out of date on the local system.                   |

| Function       | Description                                                                                                       |
|----------------|:------------------------------------------------------------------------------------------------------------------|
| pacdisowned    | List all disowned files in your system                                                                            |
| paclist        | List all installed packages with a short description - [Source](https://bbs.archlinux.org/viewtopic.php?id=93683) |
| pacmanallkeys  | Get all keys for developers and trusted users                                                                     |
| pacmansignkeys |      
