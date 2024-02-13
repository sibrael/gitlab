Задание 1
Составьте команду rsync, которая позволяет создавать зеркальную копию домашней директории пользователя в директорию /tmp/backup
Необходимо исключить из синхронизации все директории, начинающиеся с точки (скрытые)
Необходимо сделать так, чтобы rsync подсчитывал хэш-суммы для всех файлов, даже если их время модификации и размер идентичны в источнике и приемнике.
На проверку направить скриншот с командой и результатом ее выполнения
![Image alt](https://github.com/sibrael/git/blob/d01dbebeebf7965e56f8a080207da7e9b09dfe2b/Rsync1.png)


---

Задание 2
Написать скрипт и настроить задачу на регулярное резервное копирование домашней директории пользователя с помощью rsync и cron.
Резервная копия должна быть полностью зеркальной
Резервная копия должна создаваться раз в день, в системном логе должна появляться запись об успешном или неуспешном выполнении операции
Резервная копия размещается локально, в директории /tmp/backup
На проверку направить файл crontab и скриншот с результатом работы утилиты.

![Image alt](https://github.com/sibrael/git/blob/d01dbebeebf7965e56f8a080207da7e9b09dfe2b/Cron.png)
![Image alt](https://github.com/sibrael/git/blob/d01dbebeebf7965e56f8a080207da7e9b09dfe2b/Log.png)




---
