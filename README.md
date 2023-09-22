# [diploma.netology](https://sofdofi.github.io/diplom.netology2/)


Задача:Создание «информационной системы для предварительного бронирования билетов».
Разработка сайта онлайн-бронирования билетов.

Составляющие (сущности):
Кинозал
Помещение, в котором демонстрируются фильмы. Режим работы определяется расписанием на день. Зал — прямоугольный, состоит из N*M различных зрительских мест.

Зрительское место
Место в кинозале. Зрительские места могут быть VIP и обычные.

Фильм
Информация о фильме заполняется администратором. Фильм связан с сеансом в кинозале.

Сеанс
Сеанс — это временной промежуток, в котором в кинозале будет показываться фильм. На сеанс могут быть забронированы билеты.

Билет
QR-код c уникальным кодом бронирования, в котором обязательно указаны место, ряд, сеанс. Билет действителен строго на свой сеанс. Для генерации QR-кода использован QRCreator.js

Роль пользователя:
Гость-неавторизованный посетитель сайта

Возможности гостя:
просмотр расписания
просмотр информации о фильмах
выбор места в кинозале
бронирование билета


Реализация проекта:
Адаптирована исходная верстка под планшетные и мобильные устройства. Верстка корректно отображается на устройствах с шириной экрана 320px и более.
Разработана API для взаимодействия с Backend.
Получение списков всех залов, кинофильмов и сеансов
Получение актуальной схемы посадочных мест на выбранный сеанс
Заказ билета с qr-code.

ссылка сайта: https://sofdofi.github.io/diplom.netology2/
