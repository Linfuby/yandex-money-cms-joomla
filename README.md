#Y.CMS Joomla

Модуль оплаты Y.CMS Joomla необходим для интеграции с сервисом [Яндекс.Касса](http://kassa.yandex.ru/) на базе CMS Joomla и компонента JoomShopping. 

Доступные платежные методы, если вы работаете как юридическое лицо:
* **Банковские карты** -  Visa (включая Electron), MasterCard и Maestro любого банка мира
* **Электронные деньги** - Яндекс.Деньги и WebMoney
* **Наличные** - [Более 170 тысяч пунктов](https://money.yandex.ru/pay/doc.xml?id=526209) оплаты по России
* **Баланс телефона** - Билайн, МегаФон и МТС
* **Интернет банкинг** - Альфа-Клик и Сбербанк Онлайн

###Требования к CMS Joomla:
* версия 3.2.3 или 3.3.0;
* компонент JoomShopping версии 4.3.3 или 4.4.0

###Установка модуля
Для установки данного модуля необходимо распаковать [архив](https://github.com/yandex-money/yandex-money-cms-joomla/archive/master.zip) и поместить файл `update.sql` и папку `components` в корень вашего сайта!
Пожалуйста, обязательно делайте бекапы!

Внимание! Если у вас пустая страница конфигурации - у вас неправильно настроен `tmp_path` в файле настроек `configuration.php`и/или папка `/tmp` недоступна для записи на момент установки модуля (исправляется командой `chmod 777 /tmp`).

###Нашли ошибку или у вас есть предложение по улучшению модуля?
Пишите нам cms@yamoney.ru
