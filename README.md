# Уникализация креативов

Скачать скрипт [можно здесь](https://github.com/zhitnyakov/uniq/archive/master.zip)
Подробнейшая видео-инструкция [находится здесь](https://youtu.be/brHPHBS5J9c).

## Список команд

- `apt update`
- `apt install apache2`
- `apt install php`
- `apt install libapache2-mod-php`
- `apt install php-imagick`
- `apt install ffmpeg`

## Для тех, кто не разбирается в тех. части

Действуйте по 8-минутной [видео-инструкции](https://youtu.be/brHPHBS5J9c).

## Для тех, кто разбирается в тех части

Лучше тоже следуйте 8-минутной [видео-инструкции](https://youtu.be/brHPHBS5J9c) 🙃

Anyway. Если вы хотите закинуть данный скрипт на уже имеющийся у вас сервер, то на сервере должно быть несколько вещей:

- PHP, интегрированный с веб-сервером
- Расширение PHP [ImageMagick](https://www.php.net/manual/ru/book.imagick.php). В debian-based ОС устанавливается командой `apt install php-imagick`
- [FFmpeg](https://www.ffmpeg.org/). В debian-based ОС устанавливается командой `apt install ffmpeg`
