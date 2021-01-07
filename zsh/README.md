# ZSH & Oh-my-zsh
Для установки оболочки ZSH необходимо выполнить следующую команду в зависимости от системы.

Linux:
```
sudo apt install zsh
```

MacOS:
```
brew install zsh
```

Далее устанавливаем framework для управления конфигурацией zsh - Oh My Zsh!
Инструкции и команды для установки можно найти на [оффициальном сайте][oh_my_zsh_install].

Для установки конфигурации находясь в главном каталоге данного репозитория нужно выполнить команду:
```
cp zsh/.zshrc ~
```

А затем изменить `user_home` на путь к домашней директории пользователя в слудующем фрагменте файла конфигурации `.zshrc`:
```
# Path to your oh-my-zsh installation.
export ZSH="/user_home/.oh-my-zsh"
```

[oh_my_zsh_install]: https://ohmyz.sh/#install
