# SmartHomeMIREA
Концепция такая:
У нас есть разнородные устройства, объединенные в единую сеть и передающие данные владельцу дома через головной контроллер.
Примерный список устройств по функционалу:

1)Головной контроллер

2) Освещение
- лампочки
- жалюзи
3) Температура, включает в себя:
- отопление
- кондиционер
- термометр
- пол
- термостат
4) датчик протечек
5) датчик дыма
6) шлюзовые устройства (промежуточная связь с головным контроллером)
- розетки
- выключатели
7) Безопасность
- камеры
- датчики движения
- замки

Все устройства делятся также по логике работы:
1) передача данных и изменение состояний (лампочки, термостат)
2) функциональные устройства (изменение своих параметров по определённым входным данным, могут выполнять роль промежуточных маршрутизаторов, кондиционер, розетка)
3) управляющие устройства - головной контроллер, который коннектиться к внешней сети (интернету)

В рамках стенда нужно, условно, штук 10-20 сенсорных устройств, 5-10 функциональных устройств, 3-5 управляющих устройств

Вся эта хуерга должна работать:
Wi-fi
ZigBee
Пока ищу варианты для интеграции thread, lorawan, bluetooth LE, nfc

Топологии, которые должны появиться в процессе конфигурирования сети:
1) Звезда
2) Ячеистая
3) Дерево
4) Смешанная (например, гибрид дерева и звёзды)

Протоколы, которые будут использоваться

1) MQTT
2) AQMP
3) COAP
4) tcp/ip
5) udp
6) http
