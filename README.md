## Цель

Это первый проект, связанный с работой нейронными сетями. Задача проекта заключается в разработке модели для предсказания температуры на поверхности звезды на основе различных характеристик.
### Используемые признаки

- **Абсолютная температура (T(K))** — температура на поверхности звезды в Кельвинах, таргет.
- **Относительная светимость (L/Lo)** — светимость звезды относительно светимости Солнца.
- **Относительный радиус (R/Ro)** — радиус звезды относительно радиуса Солнца.
- **Абсолютная звёздная величина (Mv)** — физическая величина, характеризующая блеск звезды.
- **Звёздный цвет** — цвет звезды, определяемый на основе спектрального анализа (например, белый, красный, синий, жёлтый, жёлто-оранжевый и др.).
- **Тип звезды** — тип звезды, обозначенный числом:
  - Коричневый карлик: 0
  - Красный карлик: 1
  - Белый карлик: 2
  - Звёзды главной последовательности: 3
  - Сверхгигант: 4
  - Гипергигант: 5

## Используемые библиотеки

- **Pytorch** — для создания и обучения нейронной сети.
- **Scikit-learn** — для предобработки данных и вычисления mse.
- **Matplotlib** / **Seaborn** — для визуализации данных и результатов модели.
- **Pandas**
- **NumPy**
