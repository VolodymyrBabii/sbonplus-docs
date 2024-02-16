# Welcome to MkDocs

## Про MkDocs

[MkDocs](https://www.mkdocs.org)— це швидкий , простий і справді чудовий генератор статичних сайтів, призначений для створення проектної документації. Вихідні файли документації записуються в Markdown і налаштовуються за допомогою одного файлу конфігурації YAML. Почніть із ознайомлення з підручником , а потім перегляньте Посібник користувача для отримання додаткової інформації.

Відвідайте  [mkdocs.org](https://www.mkdocs.org).

## Про Markdown

**Markdown** — полегшена мова розмітки даних, яку створено з ухилом на прочитність та зручність у публікації з подальшим перетворенням її XHTML або HTML.

Відвідайте  [Markdown](https://www.markdownguide.org/cheat-sheet/).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.


## Початок для GitLab Beskyd

### Підключення до GitLab
Потрібно згенерувати ключ для коистувача
  
  ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIAjGxfr60rwsVfPbYxhB4+mBrq+VeZivzWlTHhXHhHE1 bvm@beskyd.com

### Клонування з Git
```
  git@gitlab.beskyd.com:volodymyr.babii/sbonplus-5-docs.git
```
### Перевірка ключа
```
  ssh -T git@gitlab.beskyd.com
```
### Клонувати каталог  в поточний каталог
```
  git clone git@gitlab.beskyd.com:volodymyr.babii/sbonplus-5-docs.git
```
### Інтсалювати mkdocs-material
```
  pip install mkdocs-material
```
### Відкрити VC code і відкрити проект клонований

### Створити проект 
В терміналі свиконати команду для створення катлогу
 ```
 mkdocs new .
 ```
### Запускаємо сервер
```
mkdocs serve
```
### Завантажити проект на GitLab

Приклад файла сценарія:  *[.gitlab-ci.yml](https://github.com/Stepa86/demo_mkdocs/blob/master/.gitlab-ci.yml)*


## Початок для власного Git 
* Створити проект на Git
* Додати клонування  в локальну папку
  
  ```
  git clone git@gitlab.beskyd.com:volodymyr.babii/sbonplus-5-docs.git
  ```
* після створеня документа 
   ```python
    git add .
    git clone git@gitlab.beskyd.com:volodymyr.babii/sbonplus-5-docs.git
    git push origin main
    ```
 
## Експорт сайту в PDF

Ознайомтеся з описом за цією адресою *[mkdocs-print-site-plugin](https://timvink.github.io/mkdocs-print-site-plugin/index.html)*



