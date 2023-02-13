# GameHelper

### Описание

Анализируя цвета пикселей на экране, определяет, насколько ценная вещь вам досталась.

### Использование скрипта

Поместите свою вещь в инвентарь, раскомментируйте необходимые характеристики в настройках, укажите требуемое количество вещей к продуждению, положите вещи в РЯД
настройки в коде обозначены `--SETTINGS`.
Приведен ряд готовых настроек, вы можете просто раскомментировать нужную строчку или установить новые характеристики самостоятельно.

Например:
```
if ( enka > 25 ) or ( magattck > 500 and fizattck > 500 ) or (lovka > 90) then
``` 
При удачном пробуждении программа подаст звуковой сигнал и переключится на следующую вещь (если их несколько). Если же попытка будет неудачной, процесс будет продолжаться до тех пор пока у вас не кончатся камни / свитки.
Примеры работы вы можете видеть на приложенных изображениях.

### Профит!
Удачной игры

### *
Работает на windows. Рекомендуется запускать клиент игры в оконном режиме 1024*768.
Отступы в коде были сброшены для затруднения копирования и модификации.
