# Сборка проекта
Проект написан с использованием Spring. Для запуска нужно просто запустить класс Application
Для подключения vosk необходимо подключение к внешнему репозиторию. Об этом описано в https://alphacephei.com/vosk/install. Но у меня внешний репозиторий не подключился, поэтому jar файл библиотеки, скачанный из репозитория, я вручную подключил в maven. Данный jar файл я так же выложил сюда.
# Подключение моделей
Для подключения модели необходимо скачать с официального сайта https://alphacephei.com/vosk/models модель и разархивировать ее в папку "model".
Не выложил модель в гит, потому что делал на большой модели, а она весит 6Гб и в гит не влезает.
# Обращение по REST API
![image](https://user-images.githubusercontent.com/26345115/119250937-30a7bb80-bbac-11eb-968d-8eac3b604852.png)
Обращение POST /getText
Возвращается полностью результат работы модели
# Формат файла
На вход принимается файл формата wav. Файл должен быть 8khz, mono, 16 бит.
