Чтобы создать новую ветку, мы используем команду:  
> **git branch branch_name** - команда создает новую ветку с именем branch_name  

Чтобы вывести список всех веток на экран, используется команда:  
> **git branch** - показ всех веток
  
Чтобы вывести на экран истории всех коммитов с их хеш-кодами, мы используем команду:  
> **git log** - показывает журнал всех изменений 

Чтобы создать коммит, исползуется команда:
> **git commit -m "message"** - позволяет сохранить текущее состояние файла

Чтобы переключаться между ветками, мы используем команду:
> **git checkout branch_name** - переход к другой ветке

Чтобы удалить ветку, мы используем команду:
> **git branch -d branch_to_delete** - удаляет ветку

Чтобы вывести дерево сохранений, используется команда:
> **git log --graph** - выводит дерево коммитов  

Чтобы отправить нашу версию репозитория на внешний репозиторий, используется команда:  
> **git push** - отправить изменения в удаленный репозиторий

Чтобы склонировать внешний репозиторий на наш ПК, мы используем команду:  
> **git clone <url- адрес репозитория>** - клонирование внешнего репозитория на локальный ПК  

Чтобы скачать всё из текущего репозитория и автоматически сделать merge с нашей версией,  мы используем команду:
> **git pull** - получение изменений и слияние с локальной версией