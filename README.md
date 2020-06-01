# generamba-templates

Для добавления новых модулей в проект используется кодогенератор Generamba. Подробнее об установке можно почитать тут https://github.com/strongself/Generamba

Шаблоны находятся в корневой папке проекта Templates, архитектура MVP.

Для создания нового модуля нужно сначала установить генерамбу, а затем в терменале из корневой папки проекта выполнить команду **generamba gen ModuleName surf_mvp_module**

## Requirements

[Generamba](https://github.com/rambler-digital-solutions/Generamba) 1.3.0 or later.

## List of templates

* [GF VIPER module](https://github.com/surfstudio/generamba-templates/tree/master/surf_mvp_module) - generates a new module of **Surf MVP** architecture

## Installation

To install a template just put these strings in your `Rambafile` and run `generamba template install` in Terminal

```
### Catalogs
catalogs:
- 'https://github.com/aristovz/generamba-templates'

### Templates
templates:
- {name: needed_template_name}
```
