# Проект "Cервис аренды самокатов GoFast"
Версия:
- [HTML](https://github.com/c3alex/yandex_practicum/blob/main/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%2004.%20%D0%A1%D0%B5%D1%80%D0%B2%D0%B8%D1%81%20%D0%B0%D1%80%D0%B5%D0%BD%D0%B4%D1%8B%20%D1%81%D0%B0%D0%BC%D0%BE%D0%BA%D0%B0%D1%82%D0%BE%D0%B2%20GoFast/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%204.%20%D0%A1%D1%82%D0%B0%D1%82%D0%B8%D1%81%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B9%20%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85%20%D0%BF%D0%BE%D0%BF%D1%83%D0%BB%D1%8F%D1%80%D0%BD%D0%BE%D0%B3%D0%BE%20%D1%81%D0%B5%D1%80%D0%B2%D0%B8%D1%81%D0%B0%20%D0%B0%D1%80%D0%B5%D0%BD%D0%B4%D1%8B%20%D1%81%D0%B0%D0%BC%D0%BE%D0%BA%D0%B0%D1%82%D0%BE%D0%B2%20GoFast.html)
- [ipynb](https://github.com/c3alex/yandex_practicum/blob/main/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%2004.%20%D0%A1%D0%B5%D1%80%D0%B2%D0%B8%D1%81%20%D0%B0%D1%80%D0%B5%D0%BD%D0%B4%D1%8B%20%D1%81%D0%B0%D0%BC%D0%BE%D0%BA%D0%B0%D1%82%D0%BE%D0%B2%20GoFast/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%204.%20%D0%A1%D1%82%D0%B0%D1%82%D0%B8%D1%81%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B9%20%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85%20%D0%BF%D0%BE%D0%BF%D1%83%D0%BB%D1%8F%D1%80%D0%BD%D0%BE%D0%B3%D0%BE%20%D1%81%D0%B5%D1%80%D0%B2%D0%B8%D1%81%D0%B0%20%D0%B0%D1%80%D0%B5%D0%BD%D0%B4%D1%8B%20%D1%81%D0%B0%D0%BC%D0%BE%D0%BA%D0%B0%D1%82%D0%BE%D0%B2%20GoFast.ipynb)


## Описание проекта

На основе данных сервиса аренды самокатов GoFast о некоторых пользователях из нескольких городов, а также об их поездках нужно выяснить частоту встречаемости городов, соотношение пользователей с подпиской и без подписки, возраст пользователей, расстояние, которое пользователь преодолел за одну поездку, продолжительность поездок, проверить гипотезы и ответим на вопросы о поведенческом различии пользователей с подпиской и без нее, выяснить, какая категория пользователей приносит больше выручки компании.

**Дополнительные задачи:**
- вычислить, какое минимальное количество промокодов нужно разослать, чтобы вероятность не выполнить план - 100 новых клиентов продлили подписку - была примерно 5%.
- построить примерный график распределения и оценить вероятность того, что уведомление откроют не более 399,5 тыс. пользователей при том, что уведомления открывают около 40% получивших клиентов. Отдел маркетинга планирует разослать 1 млн уведомлений.

## Навыки и инструменты

- `python`
- `pandas`
- `matplotlib`
- `warnings`
- `seaborn`
- `math`  
- `numpy`
- `scipy.stats`
- `t-тест`

## Вывод

Провели этапы обработки данных и на основе исследования данных выявили наиболее популярный город, количество пользователей по группам, общие параметры поездок пользователей, подсчитали выручку компании, проверили гипотезы о различиях групп пользователей с помощью t-теста. 

Также по дополнительным задачам установили минимальное количество промокодов, которое нужно разослать, и вероятность того, что уведомление откроют не более 399,5 тыс. пользователей.
