[[ЭВМ|<==]]
# Отладчик машинных команд debug.
Программа debug предназначена для отладки программ на уровне машинных кодов. Полный набор возможностей этой программы можно найти в любом справочном руководстве по командам операционной системы MS DOS. 
# Основные функции и команды.
Функции:
- прямой ввод кодов программ и данных в выбранные поля оперативной памяти, причем коды могут вводиться как в машинном (шестнадцатеричном), так и в ассемблерном формате;
- редактирование содержимого полей памяти в шестнадцатеричном или символьном виде;
- запуск программ на выполнение в обычном режиме и в режиме трассировки;
- просмотр содержимого выбранного участка оперативной памяти;
- просмотр содержимого регистров процессора;
- целый ряд других режимов, которые обслуживают все связанные с отладкой программ действия.

Таблица 1. [Команды debug](https://celitel.info/klad/nhelp/helpbat.php?dcmd=debug#Debug_c)

| Команда    | Сокращение | Параметры                                | 
| ---------- | ---------- | ---------------------------------------- |
| assemble   | a          | [address]                                |
| compare    | c          | range address                            |
| dump       | d          | [range]                                  |
| enter      | e          | address [list]                           |
| fill       | f          | range list                               |
| go         | g          | [=address] [addresses]                   |
| hex        | h          | value1 value2                            |
| input      | i          | port                                     |
| load       | l          | [address] [drive] [firstsector] [number] |
| move       | m          | range address                            |
| name       | n          | [pathname] [arglist]                     |
| output     | o          | port byte                                |
| proceed    | p          | [=address] [number]                      |
| quit       | q          |                                          |
| register   | r          | [register]                               |
| search     | s          | range list                               |
| trace      | t          | [=address] [number]                      |
| unassemble | u          | [range]                                  |
| write      | w          | [address] [drive] [firstsector] [number] |