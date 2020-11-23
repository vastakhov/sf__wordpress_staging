# Описание
После запуска плейбука на удаленной машине поднимается WordPress.

# Содержание
1. [Установка Ansible](##-1.-Установка-Ansible)
2.

## 1. Установка Ansible

Установка для Debian подобных систем

`sudo apt install -y ansible`
***

Установка для RHEL подобных систем

`sudo yum install -y ansible`
***
Установка для Arch подобных систем

`sudo pacman -S ansible`
***

## Копирование репозитория
`git clone git@github.com:vastakhov/sf__wordpress_staging.git` 

Перейти в директорию с репозиторием

`cd sf__wordpress_staging`

## Редактирование файла `hosts`







# sf__wordpress_staging

Edit file hosts and add server IP

git clone https://github.com/vastakhov/sf__wordpress_staging.git

ansible-playbook playbook.yml -i hosts -v


enjoy!
