# EXIF reader for 1C
Внешняя обработка для платформы 1С: Предприятие.
Демонстрирует чтение метаданных JPEG файла.
Для работы требуется платформа не ниже 8.3.6.1977

## Пример использования
```
// Для встроенной обработки:
Чтение = Обработки.EXIFReader.Создать();

// Для внешней обработки:
Чтение = ВнешниеОбработки.Создать(ПутьКФайлуОбработки);

// Поддерживается чтение двоичных данных и потока в памяти, см. код
Чтение.ПрочитатьФайл(ПутьФайлу);

// Список поддерживаемых свойств описан в обработке. См. встроенные макеты отбработки и код.
ОриентацияСнимка = Чтение.Свойства.Orientation;
```

## Установка
Скопируйте репозиторий, и используйте файл с расширением `.epf`. Встраивания в конфигурацию не требуется
