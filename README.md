Сначала я скопировал проект в свой github. 
![](screenshots/s1.png)
Затем, я ввел свое имя/фамилию и почту. 
![](screenshots/s2.png)
После, я перешел в папку Lab, где будут проходить все манипуляции с репозиторием.
![](screenshots/s3.png)
В папке Lab я инициализировал git, затем связал удаленный репозиторий с данной папкой, а затем, клонировал проект в папку. 
![](screenshots/s4.png)
В результате, в папке Lab появляются файлы. 
![](screenshots/s5.png)
Затем, при помощи GitHub, я создал текстовый файл с примером кода, после чего сохранил при помощи кнопки «Commit new file» 
![](screenshots/s6.png)
В GtiBash я ввел команду git pull origin master, которая загружает все изменения.
![](screenshots/s7.png)
Для того, чтобы посмотреть все последние изменения, можно использовать команду git log.
![](screenshots/s8.png)
Можно также, например, при помощи команды git show ‘Код коммита’ можно получить подробную информацию о последнем изменении
![](screenshots/s9.png)
При помощи git checkout можно переключится в различные ветки репозитория. Однако, я попытался загрузить в ветку мастер сразу ветку branch1, попутно выполнив слияние. Однако, возникла ошибка.
![](screenshots/s10.png)
Исправив ошибку в mergefile(конфликт текста внутри), я вновь попробовал слить ветку, и, на этот раз, все получилось.
![](screenshots/s11.png)
После, я удалил ненужную ветку branch1 и запушил все в github
![](screenshots/s12.png)
Видно, что осталась лишь одна ветка master 
![](screenshots/s13.png)
Я создал несколько файлов с разным описанием(причем GitHub создает собственное стандартное описание, которое видно возле файла Test File)
![](screenshots/s14.png)
Я забрал изменения и посмотрел лог изменений
![](screenshots/s15.png)
Затем, я удалил последний коммит и запушил результат. -f необходим так как исчез один из файлов, чтобы пропустить возможный конфликт. Сообщение HEAD говорит, что теперь последним коммитом является создание нового файла.
![](screenshots/s16.png)
После, я сохранил все скрины в отдельную папку, и при помощи git status проверил наличие файлов перед коммитом
![](screenshots/s17.png)
Затем, я создал отчет в файле Readme.md
![](screenshots/s18.png)
Итоговый лог перед последним коммитом
![](screenshots/s19.png)
Все скриншоты располагаются в папке screenshots.
