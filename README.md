# Форматирование отображения телефонного номера

## Требования

- PHP 8.4

## Установка

composer required komlev-ivan/phone-format

## Использование

```
<?php

$phone = '89031112233';

$formattedPhone = new FormatPhone($phone);
echo $formattedPhone; // +7 (903) 111-22-33

?>
```