**1. Какие принципы хорошего программирования ты знаешь?**  
Там нужно будет назвать SOLID, KISS, DRY, YAGNI.

- `KISS` - «keep it short and simple» — «делай кратко и просто». Надо держать свои функции максимально простыми, тупыми,
  чтобы они выполняли только то, что нужно, им не сложнее.
- `DRY` - Don't repeat yourself — «не повторяйтесь». Соответственно, чем больше мы повторяем раз свой кодярник, то если
  возникнет необходимость его модифицировать, то в n местах, где мы его повторили, n раз его надо будет
  про модифицировать, то есть n вероятность ошибки. Если его надо повторять, то он выносится в функцию, эта функция
  потом откуда-то вызывает.
- `YAGNI` - «You Ain't Gonna Need It» — «Вам это не понадобится» То есть, соответственно, у тебя в коде сейчас должен
  быть только тот функционал, который нужен тебе сейчас.
- `SOLID` - `S` - single responsibility - принцип единичной ответственности, что каждый класс должен выполнять только те
  цели, для которых он должен был, нет, для которых он был задуман. `O` - open-closed - Принцип открытости-закрытости.
  Про то, что класс у нас должен быть открыт для расширения и закрыт для модификации. Для модификации класса мы его
  должны пронаследовать. `L` - Liskov substitution - Принцип постановки Барбары Лисков. Это про то, что у нас есть
  родительский класс, если у нас есть его дочерний класс, и у нас есть функция, которая умеет работать с родительским
  классом. Так вот, мы в эту функцию можем без зазрения совести кинуть объект дочернего класса и это будет работать,
  потому что дочерний класс должен полностью уметь заменять родительский класс. Ну, объект дочернего класса должен
  полностью заменять объект родительского класса. `I` - interface segregation - Принцип разделения интерфейса. Чем иметь
  один жирный, здоровый интерфейс под все, что только можно, лучше иметь кучу мелких интерфейсов под конкретные
  нужно. `D` - dependency inversion - То, что должны быть зависимости на классах, а не классы на зависимости. То есть,
  по-хорошему, вы просто, если вам что-то нужно, создали класс, там реализовали что-то, отложили, что-то сделали.

--- 

**2. Какие паттерны программирования ты знаешь?**  
Их там в районе 40, насколько я помню, может быть больше. Gov-паттерны, они делятся на 3 группы. Это порождающие, 
поведенческие, структурные. 
https://refactoring.guru/ru/design-patterns/catalog


**3. SDLC**