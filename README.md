### Урок №2, Задание №1

---
#### Игнорирование файлов и директорий <br/> и параллельно изучение языка разметки MarkDown

***
* `**/.terraform/*` - игнорирует все файлы внутри директории (-ий) ***"terraform"***, <br/> которая (-ые) в свою очередь может (могут) находиться в любой директории.
* `*.tfstate` - игнорирует все файлы с расширением ***".tfstate"***
* `*.tfstate.*` - игнорирует все файлы где в любом месте наименования используется ***".tfstate."***
* `crash.log` - игнорирует файл (-ы) с наименованием ***"crash.log"***
* `*.tfvars` - игнорирует все файлы с расширением ***".tfvars"***
* `override.tf` - игнорирует файл (-ы) с наименованием ***"override.tf"***
* `override.tf.json` - игнорирует файл (-ы) с наименованием ***"override.tf.json"***
* `*_override.tf` - игнорирует все файлы с окончанием ***"_override.tf"***
* `*_override.tf.json` - игнорирует все файлы с окончанием ***"_override.tf.json"***
* `.terraformrc` - игнорирует скрытый (-ые) файл (-ы) с наименованием ***".terraformrc"***
* `terraform.rc` - игнорирует файл (-ы) с наименованием ***"terraform.rc"***
