[![Maintainability](https://api.codeclimate.com/v1/badges/d4fd2dc726f19e2d4bc2/maintainability)](https://codeclimate.com/github/euhoo/watch_bg/maintainability)
[![Build Status](https://travis-ci.org/euhoo/watch_bg.svg?branch=master)](https://travis-ci.org/euhoo/watch_bg)  
Сделано с использованием  
https://habr.com/ru/post/307744/  
Так же помогла дока socket.io  
https://socket.io/get-started/chat/  
Так же спасибо моему другу и сенсею Ивану Фисунову за подсказки и сэкономленное время!  
  
Приложение можно использовать отдельно(как сейчас),а можно встроенным в ангуляр.  
Приложение сделано для hot reload моего рабочего проекта, где нет сборки на этапе разработки, а есть просто angularjs, разработческий сервак на express, нет никакого сборщика.  
Именно по этой причине я подключаю библиотеки на фронте в файл index.html, а на серваке могу пользоваться пакетами из npm.   
Релоадит указанную папку рекурсивно