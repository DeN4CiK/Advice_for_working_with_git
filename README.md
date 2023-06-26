# Шпора GIT
GIT - систем контроля версий (Version Conttrol System), иногда называют Source(система) Control Managment(исходным кодом)
С помощью GIT отслеживаются изменения в прогах, файлах, кто их менял, когда и тд.
ревизия/версия - изменения в VCS
GUI - Graphical User Interface - Графический интерфейс
CLI - Command-line Interface - Командная строка
## Команды git
pwd - print working directory - показать рабочую(текущую) папку. Выводит путь к директории
cd - change directory - сменить директорию
~ домашняя директория
ls - list directory contents - отобразить содержимое директории
cd .. - возвращает на уровень выше(в родительскую директорию)
cd . - переход в текущую директорию(обращение к ней)
с помощью знака / можно перейти сразу на несколько уровней глубже 
ls -a выводит расширенный список со скрытыми файлами
также можно совмещать ls с ~, ..
touch - создает файл - пер. коснуться
mkdir - make directory - создать директорию 
Так же можно создавать с помощью / несколько директорий с помощью флага -p
И так же может работать с ~, .. Причем с помощью / и .. можно подниматься на несколько уровней
cp - copy - копирует файлы, два параметра что и куда можно указывать несколько файлов
mv - move - перемещает файлы или папки синтаксис как у cp
cat - conCATenate and print - обиъединить и распечатать - читает файл и выводит его содержимое. Только с текстовыми файлами.
rm - remove - удаляет файл
-r - recursive - рекурсивный - удаляет папку с содержимым
rmdir - remove directory - удаляет пустую папку.
&& - несколько команд одновременно
существует буфер команд им можно пользоваться с помощью стрелочек
с помощью tab можно дописывать команды и пути
### git настройка
.gitconfig - файл настройки
git config -- global user.name/mail "name/mail"
--list - дает просмотреть git config или с помощью cat
git init - initialize - инициализировать - git  начинает отслеживать изменения в этой папке то есть станет git-репозиторием
rm -rf .git - разгитит папку - r - recursive - удалить с содержимым f - force - заставить - убирает вопросы вы точно хотите удалить? 
git status - проверяет состояние репозитория
git add - для отслеживания информации о файлах
untracked - git еще на хранить инфу о версиях файла
ключ --all все антрэктэд файлы добавить
либо всю папку целиком с помощью .
отредактированный файл это modified - измененный
