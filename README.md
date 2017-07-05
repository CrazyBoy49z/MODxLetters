# MODxLetters
## Модуль для рассылки писем с сайта
* Для полноценного использования отключил проверку email на реальность
* Создайте минимум один шаблон письма
* Создайте минимум одну категорию подписчиков
## Сниппет для рассылки писем с сайта
Параметры вызова
 * @lng
 Язык
 По умолчанию - russian-UTF8
 Имена файлов в папке languages
 * @tpl
 Шаблон формф подписки.
 По умолчанию так, как определено ниже.
 Возможные значения - имя чанка в системе
 * @tpl_unsubscribe
 Шаблон отписки от рассылки
 Значение: чанк из системы
 * @cat_id
 Список категорий через запятую, который будет присвоен подписчику
 Пример 1 или 2,4 или 2,3,4,5
 * @formname
 Имя формы атрибута name
 String
 * ПРИМЕР вызова
 ```[!MODxLetters? &type=`subscribe` &cat_id=`2`!]```
 ```[!MODxLetters? &type=`unsubscribe`!]```
