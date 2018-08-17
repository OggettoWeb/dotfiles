# Проверка LESS и CSS
Код проверяется с помощью [Stylelint](http://stylelint.io/).

Настройки хранятся в файле [`stylelint.config.js`](css/stylelint.config.js). Для игнорирования файлов можно создать `.stylelintignore`.

Установка:

```bash
npm install stylelint stylelint-order --save-dev
```

Автоматически форматировать код, согласно правилам из конфига Stylelint можно командой `stylelint filename.less --fix`.
