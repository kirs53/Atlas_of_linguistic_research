# Атлас лингвистических исследований

# Описание:

В данном проекте мы предлагаем метод построения семантической карты лингвистики на основе аннотаций научных статей.

Методология:

Сбор данных:

Источник: Список Наукометрического центра НИУ ВШЭ "Филология, лингвистика и медиакоммуникация".
Отбор: Выбор журналов, относящихся к лингвистике.
Извлечение аннотаций:
Инструмент: Открытая база данных Open Alex.
Язык программирования: R.
Обработка данных:

Представление аннотаций: doc2vec (векторное пространство).
Снижение размерности: UMAP.
Разметка аннотаций:

Формат: Полуавтоматический.
Процесс:
Разделение 2D пространства на зоны.
Присвоение аннотациям направлений лингвистики (на основе метаданных).
Выделение ключевых зон для каждого направления.
Классификация неразмеченных работ (k-means).
Результаты:

Семантическая карта лингвистики, отображающая взаимосвязи между различными направлениями лингвистики.
Классификация аннотаций научных статей по направлениям лингвистики.
Использование:

Исследователи:
Анализ тематики лингвистических исследований.
Поиск relevantных работ.
Преподаватели:
Визуализация лингвистики как дисциплины.
Обучение студентов основам лингвистики.
