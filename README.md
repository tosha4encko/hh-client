# hh-client

# ТЗ

* Веб приложение, повторяющее функционал hh.ru
* Язык - TypeScript
* UI - ReactJS + Ant
* CSS - Stylus (временно)
* GIS - Openlayers
* HTTP - Axios
* Bundler - Webpack
* Менеджер пакетов - npm

#

* На главной странице должны присутствовать настройки для фильтрации и список актуальных вакансий с возможностью их сортировки.
* Все настройки, кроме полнотекстного поиска, должны сохраняться в localstorage между сессиями
* Реализовать возможность сохранять в localStorage пользовательские варианты фильтрации и переключаться между сохраненными вариантами
* Реализовать отрисовку активных вакансий на карте (https://openlayers.org/)
* Разобраться, как работает авторизация на hh и сделать возможным авторизацию для пользователя, пользовательская информация сохраняется в localStorage
* Помимо авторизации запоминать в ls адрес пользователя. 
* Добавить сортировку вакансий по удаленности от пользователя. Для нахождения координат адреса можно использовать геокодер янекса.

