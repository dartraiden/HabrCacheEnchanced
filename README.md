# HabrCache
Перенаправляет удалённые или скрытые в черновики записи с habrahabr.ru / geektimes.ru на кэш Google.

Основан на скрипте [HabrCache](https://userscripts-mirror.org/scripts/show/136481) от [dotneter](https://userscripts-mirror.org/users/138395.html). Добавлена поддержка Geektimes, отпочковавшегося от хабры. Кроме того, умеет распознавать страницы 404 в блогах компаний (у блогов страницы о недоступности поста отличаются от аналогичных страниц обычных пользователей, поэтому старый скрипт на этих страницах не срабатывал) и сами удалённые блоги компаний.

Скрипт тестировался лишь в Firefox. Ниже располагаются примеры для проверки работы.

* запись, скрытая в черновики: [geektimes](https://geektimes.ru/post/269660/), [habrahabr](https://habrahabr.ru/post/161695/)
* запись, удалённая из блога компании: [geektimes](https://geektimes.ru/company/ua-hosting/blog/251006/), [habrahabr](https://habrahabr.ru/company/muk/blog/255299/)
* удалённый блог компании, прекратившей деятельность на ресурсе: [habrahabr](https://habrahabr.ru/company/teradata/blog/)
