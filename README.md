# goit-js-hw-05

Модуль 5 - Конструкторы. Прототипы. Классы

Task #1. Функция-конструктор Account, которая создает объект со свойствами login
и email. В prototype функции-конструктора добавлен метод getInfo(), который
выводит в консоль значения полей login и email объекта который его вызвал.

Task #2. Создан класс User для пользователя со следующим свойствами: name -
строка; age - число; followers - число; Добавлен метод getInfo(), который,
выводит строку: User ${имя} is ${возраст} years old and has ${кол-во фоловеров}
followers.

Task #3. Создан класс Storage, который создает объекты для управления складом
товаров. При вызове будет получать один аргумент - начальный массив товаров, и
записывать его в свойство items. Добавлены методы класса: getItems() -
возвращает массив текущих товаров; addItem(item) - получает новый товар и
добавляет его к текущим; removeItem(item) - получет товар и, если он есть,
удаляет его из текущих.

Task #4. Создан класс StringBuilder. На вход он получает один параметр - строку,
которую записывает в свойство \_value. Добавлены следующие методы: get value -
возвращает текущее значение поля \_value; Метод append(str) - получает парметр
str (строку) и добавляет ее в конец \_value; Метод prepend(str) - получает
парметр str (строку) и добавляет ее в начало value; Метод pad(str) - получает
парметр str (строку) и добавляет ее в начало и в конец \_value;

Task #5. Создан класс Car с указанными свойствами и методами. Принимает свойства
будущеего экземпляра класса:

- speed - текущая скорость, изначально 0
- price - цена автомобиля
- maxSpeed - максимальная скорость
- isOn - заведен ли автомобиль, значения true или false. Изначально false
- distance - общий киллометраж, изначально 0

- getSpecs(car) /статический метод, работает со спецификацией автомобиля.

- Get and Set () /Работает со свойством цены автомобиля.

- turnOn() {} /Чтобы завести автомобиль, записывает в свойство isOn значение
  true

- turnOff() {} /Чтобы заглушить автомобиль, записывает в свойство isOn значение
  false, и сбрасывает текущую скорость в 0

- accelerate(value) {} /Добавялет к свойству speed полученное значение, при
  условии что результирующая скорость не больше чем значение свойства maxSpeed

- decelerate(value) {} /Отнимает от свойства speed полученное значение, при
  условии что результирующая скорость не меньше нуля

- drive(hours) {} /Добавляет в поле distance киллометраж (hours \* speed), но
  только в том случае если машина заведена
