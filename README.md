# RSS агрегатор

[![CI](https://github.com/ivladmay/rss-aggregator/actions/workflows/CI.yml/badge.svg)](https://github.com/ivladmay/rss-aggregator/actions/workflows/CI.yml) [![Maintainability](https://api.codeclimate.com/v1/badges/119597dc3b9575f035cb/maintainability)](https://codeclimate.com/github/ivladmay/rss-aggregator/maintainability)

### Возможности сервиса:

- Добавление неограниченного количества фидов
- Обновление списка постов в режиме реального времени
- Предварительный просмотр постов
- Переход к источнику поста для полного просмотра

### Инструкция по использованию:

Откройте страницу [сервиса](https://rss-aggregator-blush-nine.vercel.app/)

В поле для ввода введите валидный URL-адрес и нажмите на кнопку "Добавить". Сервис выполнит скачивание и парсинг RSS-потока, а затем отобразит данные в удобном формате. Для предварительного просмотра постов нажмите на кнопку "Просмотр". Появится модальное окно с краткой информацией о посте. Вы можете закрыть его или перейти к источнику поста для полного просмотра. Также, вы можете перейти к источнику поста, кликнув по его заголовку.

### Инструкция по локальному развертыванию:

1. Запустите терминал и склонируйте репозиторий в вашу домашнюю директорию
   `git clone https://github.com/ivladmay/rss-aggregator.git`
2. Перейдите в склонированный репозиторий `cd rss-aggregator`
3. Выполните команду `make install`
4. Для сборки приложения в режиме разработки выполните команду `make dev`, в продакшен режиме `make build`
