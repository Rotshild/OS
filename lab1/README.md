### 1 задание  
Использовал ls and cat  
ZGFpejZhaFJhZVNhZXhhaWJ1YWYK  
### 2 задание 
Сначала использовал команду ls and after cat .txt  
Понял, что мне нужно открыть все файлы для этого нужно использовать цикл...  
for i in /home/suzen/; do echo $i; cat $i; done;  
дальше нашел код:  
dGhlaWxpM2FoWm9odGFpM2VldzMK  
![Картинка](https://github.com/Rotshild/OS/blob/master/lab1/screenshots/2.jpg)
### 3 задание  
сначала использовал ls  
и так как кроме листа нет никаких команд, прочитал по строчно нужный файл в данной директории  
while read $LINE; do echo $LINE; done <./-diary.txt-;  
Y284ZWlxdXVlMmllTDNpZXBoNWUK  
![Картинка](https://github.com/Rotshild/OS/blob/master/lab1/screenshots/3.jpg)
### 14 Задание
Здесь просто нужно использовать команды cd и ls для того, чтобы найти ключ.  
d2FodmFoMWFlV2FpYmVlaG9vMmIK  
![Картинка](https://github.com/Rotshild/OS/blob/master/lab1/screenshots/14.jpg)
### 15 Задание
pwd - текущий рабочий каталог, указывает полный путь к текущему каталогу  ls .. TWVlMXdvaDJ6YWVoZWoyamllNm8K
![Картинка](https://github.com/Rotshild/OS/blob/master/lab1/screenshots/15.jpg)
### 16 Задание
Вводим команду id и получаем данные о пользователе:
ZXVsb29naG91MFBob2g4T2hkYWkK
![Картинка](https://github.com/Rotshild/OS/blob/master/lab1/screenshots/16.jpg)
### 17 Задание
ключ является скрытой директорией, чтобы его увидеть нужно добавить флаг -a:ls -a . -а - выводит скрытые файлы 
bmVlNm1lMEhhaU11M2thaGVpNmEK


![Картинка](https://github.com/Rotshild/OS/blob/master/lab1/screenshots/17.jpg)
### 18 Задание
Документация по команде, для этого используем команду man diary 
Y2hpZWNoM2VpRzRJZWtlaXNlbGUK
![Картинка](https://github.com/Rotshild/OS/blob/master/lab1/screenshots/18.jpg)
### 19 Задание
Для того, чтобы создать ветку директорий нужно использовать команду mkdir(создание директории) с флагом -p(сразу нескольких вложенных)
V2VpMGNvaHNoZWlxdWE0YWhnaG8K

![Картинка](https://github.com/Rotshild/OS/blob/master/lab1/screenshots/19.jpg)
### 20 Задание
Чтобы удалить папку со всем ее содержимым необходимо использовать команду rm с флагом -r
YW1pZWhpaW0yb2h5NW9vRjZlaXcK

![Картинка](https://github.com/Rotshild/OS/blob/master/lab1/screenshots/20.jpg)
### 21 Задание
1)rm [0-9].txt
2)rm [a-z].png
3)rm test-*.log
ls
aWU0b29XdWxlaXBodXBpZWZveW8K

![Картинка](https://github.com/Rotshild/OS/blob/master/lab1/screenshots/21.jpg)
### 22 Задание
i=1; while [ $i -lt 999 ];do touch $i.txt;let i++;done;
touch - создает файл, let i++ увеличивает счетчик на единицу. -lt == <;
aTc1Z3g3aVNvYk9CZmd6ZWF5TXh4WFBXNUJ3UG94aXBkMjYvekl0QWRWbz0K

![Картинка](https://github.com/Rotshild/OS/blob/master/lab1/screenshots/22.jpg)
### 23 Задание
cd destination
for i in /home/suzen/destination/*; do mv $i $i.back.log;done;
cd ..
cd source/
mv * ../destinaton/
cd ..
ls
dmVlc2VpQzVBb2dlaXI1cmVlM2YK

![Картинка](https://github.com/Rotshild/OS/blob/master/lab1/screenshots/23.jpg)
### 24 Задание
mkdir Music
cd Desktop
cp -r music/* ../Music
ls
YWVnaG9venVvejd2b292OHNvaEwK

![Картинка](https://github.com/Rotshild/OS/blob/master/lab1/screenshots/24.jpg)
### 25 Задание
ls и cat (вывод содержимого файла)
cat file
dGhlZThhcXVpZUNpTGFpdGhlZTkK

![Картинка](https://github.com/Rotshild/OS/blob/master/lab1/screenshots/25.jpg)
### 26 Задание
less - позволяет читать текст (logi)
q - выход
G - конец файла
g - начало файла
/SECOND_FLAG_PART: - искать по под строке в файле
WWVpc2gxYWlndXVrZWl5ZWloaWUK

![Картинка](https://github.com/Rotshild/OS/blob/master/lab1/screenshots/26.jpg)
### 27 Задание
tail -f diary
dGVlMUtleThhUXVvaDFnZTFiaWkK

![Картинка](https://github.com/Rotshild/OS/blob/master/lab1/screenshots/27.jpg)
### 28 Задание
cat<<EOF>diary
<ввод текста без последней строки>
EOF
echo -n "11:32pm: Нассал под кресло. Еееееееее!" >>diary – для решени проблем непечатных знаков
ZWV4b1g1WnVkMm9oZnVjYWhkdTMK

### 29 Задание
Нужно узнать историю, для этого нажимаем стрелочку вверх и ищем флаг.
dmFvbmcwcGFlMWlodUJvaFppZWQK
