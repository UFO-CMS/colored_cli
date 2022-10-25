# colored_cli
Enum of colors for creating colored texts in the console


####Установка

```console
> composer required "ufo-cms/colored_cli: *"
```


####Запуск

```php
use \UfoCms\ColoredCli;

...

echo CliColor::RED->value. "Some text" . CliColor::RESET->value;

```

I