# В Windows есть несколько мест, где можно найти список программ, которые запускаются автоматически при старте системы. Вот несколько из них:

- Диспетчер задач --> вкладка Автоз-агрузка

## Папка "Автозагрузка" в меню "Пуск":

- В адресной строке введите "%appdata%\Microsoft\Windows\Start Menu\Programs\Startup"

## Приложение "Планировщик заданий":

В поисковой строке введите "Планировщик заданий" и выберите его из списка результатов поиска.
В левой панели выберите "Библиотека Планировщика заданий".
Выберите задание, которое вы хотите изменить, и щелкните на нем правой кнопкой мыши.
Выберите "Свойства" и перейдите на вкладку "Действие".
В списке "Запуск программы" вы найдете путь к программе, которая запускается автоматически при старте системы.

## Реестр Windows:

Реестр Windows:
1. HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\RunOnce
2. HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\RunServices
3. HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\RunServicesOnce
4. HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Run
5. HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\policies\Explorer\Run
6. HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Winlogon\Userinit
7. HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Winlogon\Shell

## Папка "Tasks" в системном каталоге:

- C:\Windows\System32\Tasks
Службы Windows:

Через командную строку: **sc queryex type=service**
Через "Управление компьютером" (Computer Management) в разделе "Службы и приложения" (Services and Applications)