## Текстовая игра

Игровой мир обычно состоит из комнат, где может происходить какое-то действие.
Так же имеется игрок.
Как у игрока, так и у комант есть состояния.

### Управление происходит через текстовый интерфейс:
* `осмотреться`
* `идти "room"` - пример: "идти коридор".
* `применить "obj1" "obj2"` - пример: "применить ключи дверь".
* `взять "obj"` - пример: "взять ключи".
* `надеть "obj"` - пример: "надеть рюкзак".

### Запуск:
В файле `in` писать список команд, оканчивающиеся на 'exit' <br>
Запуск программы через `./run.sh` или `sh run.sh` <br>
Пример выполненной программы:
<img src="game.png" width="100%">
Запускать тесты через `go test -v`.