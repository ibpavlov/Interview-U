# WIP-Interview-U (Подготовка за интервю) #

Това е един проект направен по време на [Code4.Tech](http://code4.tech) в [Русе](http://code4.tech/%D1%80%D1%83%D1%81%D0%B5/) състезание 2016 г. Цели подготвяне на ученици, студенти и професионалисти за интервю. 
С тази платформа може да получите полезни съвети, да направите IQ тест (в разработка), да се подготвите с въпросник, който се оценява (в разработка) и видео интервю (за лична подготовка).
Възможно е да управлявате записаните видеа, както и всички въпроси на сайта.

### За кого е хранилището? ###

* За програмисти
* Version 1.1
* [Learn Markdown](https://bitbucket.org/tutorials/markdowndemo)

### Преди да започнем? ###

* PHP 5.5+ 
* Phalcon 2+
* Composer
* Mysql server

### Лиценз ###

* Свободен за ползване - MIT

### Как да го инсталираме ###

1. Като инициализирате [composer](https://getcomposer.org/) 
`composer install`
2. Можете директно да използвате [PHP Build in Server](http://php.net/manual/en/features.commandline.webserver.php)     
``php -S localhost:8000 -t public .htrouter.php``    
3. Да качите базата данни от папка /scheme където желаете - localhost или remote
4. Да създадете копие на файла /app/config/config.dist.php като config.php и да попълните вашите данни
5. Готово, може да тествате дали работи
