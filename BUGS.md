## Ошибка в Тест-кейс 2: Отмена фильтрации по категории
тип ошибки Blocker (Hight)

**Описание:** пользователь находится на главной странице с уже выбранным списком игр категории "Shooter", пользователь решает выбрать категорию "not chosen".

**Шаги:**
  1. Откройте сайт https://makarovartem.github.io/frontend-avito-tech-test-assignment/
  2. Выберите список под названием "Filter by category"
  3. Среди указанных категорий выберите "Shooter"
  4. Выберите список под названием "Filter by category"
  5. Среди указанных категорий выберите "not chosen"

**Ожидаемый результат:** Отображаются все игры из списка независимо от категории.

**Фактический результат:** На странице возникает ошибка, сайт перестает реагировать на команды пользователя

При нажатии "Back to Main" или попытке перезагрузить страницу сайт не реагирует. 

## Ошибка в Тест-кейс 3: Переход на главную страницу

тип ошибки Minor (Low)

**Описание:** пользователь находится на странице с отображением игры и решает вернуться на главную страницу путем нажатия кнопки "Back to Main" внизу страницы.

**Шаги:**
  1. Откройте сайт https://makarovartem.github.io/frontend-avito-tech-test-assignment/
  2. Нажмите на случайную игру в списке, чтобы перейти на страницу карточки игры.
  3. Нажмите кнопку "Back to main".

**Ожидаемый результат:** пользователь возвращается на главную страницу, где отображены все игры.

**Фактический результат:** пользователь возвращается на главную страницу, при этом выбранная им до этого категория игр номинально становится "not chosen" при фактическом списке "Shooter"


