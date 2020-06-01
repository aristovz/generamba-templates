# generamba-templates

Для добавления новых модулей в проект используется кодогенератор Generamba. Подробнее об установке можно почитать тут https://github.com/strongself/Generamba

Шаблоны находятся в корневой папке проекта Templates, архитектура VIPER.

Для создания нового модуля нужно сначала установить генерамбу, а затем в терменале из корневой папки проекта выполнить команду **generamba gen [ModuleName] [Template_Name]**

## Requirements

[Generamba](https://github.com/rambler-digital-solutions/Generamba) 1.3.0 or later.

## List of templates

* [GF VIPER module](https://github.com/aristovz/generamba-templates/tree/master/grow_food_viper_module) - generates a new module of **Grow Food VIPER** architecture

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
