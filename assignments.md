# Занятие 1.
### Установить Linux

# Занятие 2.
### Выполнить упражнения

Перед вами набор задач, с которыми так или иначе приходится сталкиваться любому пользователю Linux систем. Для каждой из них, необходимо написать Bash команду, которая ее решает. Сделать это нужно в одну строчку, допускается использование `&&`, `|` там где это необходимо.  
Например:  
1. Выведите на экран "Hello, world!"
2. Обновите списки пакетов и установите пакет git
3. Найдите кол-во символов в файле `long_text.txt`

Ответ:  
1. `echo "Hello, world!"`
2. `sudo apt update && sudo apt install git`
3. `wc -m long_text.txt`  

Чем **больше** задач, вы выполните, тем **больше** очков получите. Удачи!


+ 10 очков за первые 11 заданий

1. Откройте терминал и создайте папку tasks
2. Перейдите в папку tasks
3. Узнайте в какой директории вы находитесь
4. Скачайте файл по ссылке https://raw.githubusercontent.com/MITS-TSU/IntroToLinux/main/text1.txt В директорию tasks
5. Выведите содержимое файла в терминал
6. Скачайте файл https://raw.githubusercontent.com/MITS-TSU/IntroToLinux/main/text2.txt
7. Сколько строк в этом файле?
8. А как узнать его вес?
9. Выведите последние 10 строк файла
10. Выведите первую строку файла
11. Найдите все упоминания строки "1010101"

Используйте Google и постарайтесь справиться с этими задачами:  

 **12**. +2 очка  
 - Скачайте архив https://github.com/MITS-TSU/IntroToLinux/raw/main/parts.tar
 - Разархивируйте и перейдите в папку parts
 - Внутри лежат части сообщения, пронумерованные от 0 до 80 включительно, их нужно _сконкатенировать_ в один файл text3.txt но в верном порядке!
 - Попробуйте сделать это одной командой.
 - Подсказка: по-умолчанию bash и все gnu утилиты сортируют файлы в лексикографическом порядке, то есть parts10 будет идти ПЕРЕД parts1. Поищите как это исправить - вам нужен numerical order. Чтобы использовать вывод одной команды как АРГУМЕНТЫ другой, можно использовать "\`", например: cat \`ls\` выведет содержимое всех файлов которые выведет ls. Также вам понадобиться узнать что такое "перенаправление вывода".  
 
 **13**. + 3 очка 
  - Установите и настройте веб-сервер Appache или Nginx. Сервер должен отвечать одной и той же строкой на любые запросы (на ваш выбор). Учится веб-программированию не надо, достаточно погуглить.  
  - Проверить как работает ваш сервер можно открыв браузер и перейдя на 127.0.0.1:<PORT>, (обычно PORT=80). Либо вы можете сделать curl 127.0.0.1:PORT  
  - В качестве ответа - скрин конфига и скрин ответа от сервера
  
 **14**. + 1  
  - Измените prompt вашей командной строки так, чтобы отображалось лишь `~$ ` (с пробелом!). Или поищите промпт который понравится вам!
  
 **15**.  
 **16**.  
