# CS2-ShowDamage

- **ShowDamage** - отображает на экране информацию о нанесенных повреждениях.
- **Видео-демонстрация - https://youtu.be/BiAjXuetyT8**

# Установка
1. Установите [Metamod:Source](https://www.sourcemm.net/downloads.php/?branch=master) и [CounterStrikeSharp](https://github.com/roflmuffin/CounterStrikeSharp).
2. Скачайте ShowDamage
3. Распакуйте архив и загрузите его на игровой сервер

# Основной конфиг (Config.yml)
```
grenadeDamageMessage: "Общий урон от гранаты: <font color='red'>{0}</font>"
damageMessage: "Урон: <font color='red'>{0}♥</font>, Остаток HP: <font color='green'>{1}❤</font>, Попадание: <font color='yellow'>{2}</font>"
showDamageEnabledMessage: '[ {Green}ShowDamage{White} ] Отображение урона {Green}включено{White}.'
showDamageDisabledMessage: '[ {Red}ShowDamage{White} ] Отображение урона {Red}отключено{White}.'
```

# Команды
- `!damage` выключить/включить показ урона
