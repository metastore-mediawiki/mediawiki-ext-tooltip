# Информация

Всплывающее информационное сообщение напротив определённого слова. Расшифровка аббревиатур.

## Синтаксис

```
{{#icon: name=[NAME]|size=[SIZE]|color=[COLOR]|options=[OPTIONS]}}
```

- `name` - название иконки;
- `size` - размер иконки в единице измерения "em";
- `color` - цвет иконки (название цвета / HEX-код цвета);
- `options` - дополнительные опции иконки (fa-spin / fa-fw / и т.д.).

## Установка

1. Загрузите папки и файлы в директорию `extensions/MW_EXT_Icon`.
2. В самый низ файла `LocalSettings.php` добавьте строку:

```
wfLoadExtension( 'MW_EXT_Icon' );
```

## Авторы

- [**Kitsune Solar**](https://kitsune.solar/) - разработчик.

## Ссылки

- [**METASTORE**](https://metastore.pro/) - хранилище открытых проектов [**METADATA**](https://metadata.foundation/).
- [**METADATA / FOUNDATION**](https://metadata.foundation/) - поддержка и разработка открытых проектов.
