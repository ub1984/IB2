# В Windows есть несколько мест, где можно найти список программ, которые запускаются автоматически при старте системы. Вот несколько из них:

## Папка "Автозагрузка" в меню "Пуск":

Щелкните правой кнопкой мыши по кнопке "Пуск" в левом нижнем углу экрана.
Выберите "Проводник" или "Папка".
В адресной строке введите "%appdata%\Microsoft\Windows\Start Menu\Programs\Startup" (без кавычек) и нажмите "Enter".
В открывшейся папке "Автозагрузка" вы найдете ярлыки программ, которые запускаются при старте системы.

## Приложение "Планировщик заданий":

Нажмите на кнопку "Пуск".
В поисковой строке введите "Планировщик заданий" и выберите его из списка результатов поиска.
В левой панели выберите "Библиотека Планировщика заданий".
Выберите задание, которое вы хотите изменить, и щелкните на нем правой кнопкой мыши.
Выберите "Свойства" и перейдите на вкладку "Действие".
В списке "Запуск программы" вы найдете путь к программе, которая запускается автоматически при старте системы.

## Реестр Windows:

Реестр Windows:
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Run
HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\RunOnce
HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\RunServices
HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\RunServicesOnce
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Winlogon\Userinit
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Winlogon\Shell
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\policies\Explorer\Run

## Папка "Tasks" в системном каталоге:

C:\Windows\System32\Tasks
Службы Windows:

Через командную строку: **sc queryex type=service**
Через "Управление компьютером" (Computer Management) в разделе "Службы и приложения" (Services and Applications)