## Читать следы

Пассивное умение, позволяющее обнаруживать дичь и следы животных в определённом радиусе вокруг юнита

### Тип навыка

Пассивный

### Допустимые цели

Сам юнит (автоматическое сканирование области)

### Ограничения

Действует в радиусе трёх клеток. Эффективность снижается в плохую погоду

### Зона действия

Круг радиусом трёх клеток вокруг юнита

### Модификаторы

1. Уровень навыка и юнита (увеличивает радиус/точность)
2. Погодные условия (дождь/снег уменьшают эффективность)
3. Ритуалы шамана (временное усиление)
4. Время суток (ночью сложнее)

### Стоимость использования

Не применимо (пассивный навык)

### Время восстановления (Cooldown)

Не применимо (пассивный навык)

### Время применения / Каст

Не применимо (пассивный навык)

### Эффекты

1. Автоматическое обнаружение дичи в радиусе
2. Отображение следов животных на земле
3. Индикация направления движения дичи
4. Информация о времени появления следов

### Визуальные эффекты

Подсветка следов животных. Маркеры обнаруженной дичи. Эффект "шестого чувства" (мерцание контура земли). Навык применяется ко всем типам наземных зверей

Типы следов:
- Малые травоядные животные (лапы)
- Парнокопытные
- Малые и средние хищники (волк, лиса - лапы с когтями)
- Крупные хищники (саблезубый лев, тигр)
- Медведь
- Мамонт

### Звуковые эффекты

Тихий звук при обнаружении. Шум ветра/природы при сканировании

### Связанные задачи

**Графика:**
1. Эффекты подсветки следов
2. Маркеры для обнаруженной дичи
3. Шейдерные эффекты для "шестого чувства"
4. Иконка пассивного навыка

**Звук:**
1. Звуки обнаружения следов/дичи
2. Атмосферные звуки сканирования

**Гейм-дизайн:**
1. Определение базового радиуса действия навыка
2. Формулы влияния модификаторов
3. Разработка уровней навыка
4. Баланс сезонных/погодных ограничений
5. Интеграция с системой охоты

**Программирование:**
1. Реализация пассивного сканирования области
2. Система обнаружения и классификации следов
3. Интеграция с погодными/сезонными условиями
4. Визуализация обнаруженных объектов
5. Расчет направления/возраста следов

**Требования к UX/UI:**
1. Индикация активного навыка в HUD
2. Миникарта с отметками дичи/следов
3. Фильтры отображения типов следов
4. Текстовые подсказки о возрасте следов