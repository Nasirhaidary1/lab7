# РОССИЙСКИЙ УНИВЕРСИТЕТ ДРУЖБЫ НАРОДОВ
## Факультет физико-математических и естественных наук
### *ОТЧЕТ*
### *ПО ЛАБОРАТОРНОЙ РАБОТЕ №7*

*дисциплина: Операционные системы*

Студент: Хайдари Ахмад Насир
Группа: НБИбд-01-20

### **МОСКВА** 

#### 2021 г


### Цель работы

Ознакомление с инструментами поиска файлов и фильтрации текстовых данных. Приобретение практических навыков: по управлению процессами, по проверке использования диска и обслуживанию файловых систем.


### Выполнение лабораторной работы

1. Включаем компьютер, и заходим в учетную запись.

2. Запишем в файл file.txt названия файлов, содержащихся в каталоге /etc. Допишем в этот же файл названия файлов, содержащихся в нашем домашнем каталоге.

<a href="https://wampi.ru/image/RAQ6zUy"><img src="https://ic.wampi.ru/2021/09/18/11af062dba25cb0f0.png" alt="11af062dba25cb0f0.png" border="0"></a>

3. Выведем имена всех файлов из file.txt, имеющих расширение .conf, после чего запишем их в новый текстовой файл conf.txt.

<a href="https://wampi.ru/image/RAQ6qZV"><img src="https://ic.wampi.ru/2021/09/18/2b43253a4928cec58.png" alt="2b43253a4928cec58.png" border="0"></a>

4. Определили, какие файлы в нашем домашнем каталоге имеют имена, начинавшиеся с символа c? 
<a href="https://wampi.ru/image/RAQRMki"><img src="https://ic.wampi.ru/2021/09/18/3d7a74fd3887361f0.png" alt="3d7a74fd3887361f0.png" border="0"></a>

5. Выведем на экран (постранично) имена файлов из каталога /etc, начинающиеся с символа h.
 > find /etc -name "h*" -print | less

 <a href="https://wampi.ru/image/RAQR3fc"><img src="https://ia.wampi.ru/2021/09/18/49b456de4bf97f5f2.png" alt="49b456de4bf97f5f2.png" border="0"></a>

 6. Запустили в фоновом режиме процесс, который будет записывать в файл ~/logfile файлы, имена которых начинаются с log. Процесс выполнен

7. Удалили файл ~/logfile. Но сначала убили процесс в нем.

<a href="https://wampi.ru/image/RAQR8kZ"><img src="https://ic.wampi.ru/2021/09/18/5.png" alt="5.png" border="0"></a>

8. Запустили из консоли в фоновом режиме редактор gedit.

9. Определили идентификатор процесса gedit, используя команду ps, конвейер и фильтр grep

10. Прочитали справку (man) команды kill, после чего используйте её для завершения процесса gedit.

<a href="https://wampi.ru/image/RAQRFKf"><img src="https://ia.wampi.ru/2021/09/18/6.png" alt="6.png" border="0"></a>

11. Выполним команды df и du, предварительно получив более подробную информацию об этих командах, с помощью команды man.

<a href="https://wampi.ru/image/RAQReMy"><img src="https://ic.wampi.ru/2021/09/18/7.md.png" alt="7.md.png" border="0"></a>

<a href="https://wampi.ru/image/RAQRBRt"><img src="https://ia.wampi.ru/2021/09/18/8.png" alt="8.png" border="0"></a>


<a href="https://wampi.ru/image/RAQRJK0"><img src="https://ia.wampi.ru/2021/09/18/9.png" alt="9.png" border="0"></a>

12. Воспользовавшись справкой команды find, вывести имена всех директорий, имеющихся в нашем домашнем каталоге.

<a href="https://wampi.ru/image/RAQR0NJ"><img src="https://ia.wampi.ru/2021/09/18/last.png" alt="last.png" border="0"></a>

 ### Вывод

В данной работе мы ознакомились с инструментами поиска файлов и фильтрации текстовых данных. А также приобрели практические навыки по управлению процессами.