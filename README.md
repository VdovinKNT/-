# Программа для подсчета калорий в блюдах

### Ссылка на Colab
[Открыть в Google Colab](https://colab.research.google.com/drive/1L-jBJy8gtMafNRdkJmU3rpzgRbk8u34_?usp=sharing)

#### Видео URL
[Ссылка на видеопрезентацию](https://drive.google.com/file/d/ваш_id_видео/view)

#### Описание:

Данный проект представляет собой интерактивную программу для подсчета калорийности блюд на основе их состава.

### Функциональные возможности:
1. **Добавление продуктов:** Пользователь может вводить название продукта и его калорийность на 100 грамм. Это позволяет работать с любыми продуктами.
2. **Добавление ингредиентов в рецепт:** После указания продуктов и их калорийности пользователь может добавлять ингредиенты с указанием их количества в граммах.
3. **Подсчет калорийности блюда:** Программа автоматически рассчитывает общую калорийность блюда на основе ингредиентов и их количества.
4. **Просмотр текущего рецепта:** Отображает список всех добавленных ингредиентов с указанием их количества и калорийности.
5. **Сохранение рецепта:** Пользователь может сохранить текущий рецепт в текстовый файл.

### Пример использования:
1. Введите продукт, например: "картофель" и его калорийность 77 ккал на 100 грамм.
2. Добавьте картофель в рецепт, указав его количество, например 200 грамм.
3. Посмотрите общую калорийность блюда или сохраните рецепт в файл.

### Структура проекта:

- **Основной код**:
  - Файл содержит функцию `main`, которая управляет всеми процессами программы, включая вызов пользовательских функций.
  - Функции:
    - `add_product`: Добавление продуктов и их калорийности.
    - `add_ingredient`: Добавление ингредиентов в рецепт.
    - `calculate_calories`: Подсчет общей калорийности блюда.
    - `view_recipe`: Просмотр текущего рецепта.
    - `save_recipe`: Сохранение рецепта в файл.

### Варианты дизайна:
- Программа использует словари для хранения информации о продуктах и их калорийности, что обеспечивает быстрый доступ к данным.
- Выбрана модульная структура с отдельными функциями для каждой задачи, что делает код более читаемым и легким для модификации.

### Применимость проекта:
Программа может быть полезна для:
- Людей, следящих за своим рационом и подсчитывающих калории.
- Поваров и диетологов для составления рецептов с учетом калорийности.
- Любителей готовить, желающих понимать энергетическую ценность своих блюд.

### Примечание:

Для использования проекта откройте ссылку на Google Colab, запустите блокнот и следуйте инструкциям в интерактивном меню программы. Видео-презентация проекта доступна по указанной выше ссылке.

