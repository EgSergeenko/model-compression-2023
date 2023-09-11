# model-compression-2023
Репозиторий курса по сжатию и ускорению моделей машинного обучения.
ИТМО 2023, направление магистратуры Искуственный интеллект.

*План курса*

    Пара 1 - Введение в компрессию моделей машинного обучения: 
        Вводная
		Что такое компрессия моделей и зачем она нужна?
		Основные задачи в компрессии моделей машинного обучения
		Ограничения и применимость
		Организационные моменты, как будет проходить курс итд
        ДЗ: Разделиться на команды по 4 человека и выбрать модели для оптимизации, сделать базовые замеры
		метрик производительности
  	[https://docs.google.com/presentation/d/1FVG4Fpbl6ffpzjHUzYq8z-jtBt9AE6wZUhxCcA7gxmE/edit#slide=id.g249d310d701_0_166](Презентация)

    Пара 2 - Методы снижения размерности.
		Квантизация весов моделей
		Pruning
        Практика - по квантизации модели и применению прунинга
        ДЗ: Применить данные подходы к своим моделям и замерить производительность

    Пара 3 - Кластеризация весов моделей:
		Использование кластеризации для сокращения размера моделей.
		Алгоритмы кластеризации и их применение к моделям машинного обучения.
        Практика - Пример с кластеризацией весов
        ДЗ: Применение данного подхода к своим моделям и замер производительности

    Пара 4 - Дистиляция весов моделей:
		Принцип работы методов дистиляции моделей
		Отличия от обучения с нуля
		Практика - Попробуем обучить модель по принципу дистиляции весов
        ДЗ: - Попытаться применить данный метод к своим моделям

    Пара 5 - Автоматическая компрессия моделей:
        Автоматический выбор оптимальной архитектуры модели для компрессии.
		Оптимизация гиперпараметров моделей для сбалансированной компромиссной модели.
        Практика - Рассмотрим способы и бибилиотеки для автоматической компрессии
        ДЗ: Применить к своим моделям и замерить производительность

    Пара 6 - Экспорт моделей в ращличные форматы Tensort, ONNX.
        Сравнение производительности сжатых моделей с экспортированными в стандартные форматы
        Практика - Примеры с жкспортом моделей в различные форматы
        ДЗ: Экспорт своих моделей и замер производительности

    Пара 7 - Примененеие компрессии в реальных задачах.
        Разбор реального примера оптимизации моделей
		Разбор задания финального проекта
        Практика - Как запустить финальные проект
        ДЗ: Оптимизировать модели и улучшить метрики производительности в финальном проекте, создав Pull Request.

