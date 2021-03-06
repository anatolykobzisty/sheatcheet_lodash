## Cheatsheet Lodash

| семейство функции | описание                                                                                    |
| ----------------- | ------------------------------------------------------------------------------------------- |
| is\*              | Проверяет является ли значение чем-то                                                       |
| stub\*            | Возвращает некоторое преопределенное значение                                               |
| to\*              | Преобразует одно значение в другое                                                          |
| \*By              | Отображает функцию, которая принимает доп. параметр                                         |
| \*In              | Функция работает со своими и унаследованными свойствами                                     |
| \*Deep            | Работает рекурсивно с вложенными структурами данных                                         |
| \*Depth           | Работает рекурсивно с вложенными структурами данных, котролируется уровень глубины рекурсии |
| \*Right           | Функция работает справа налево                                                              |
| \*Width           | Принимает доп. функцию для сравнения, конструирования алгоритма                             |
| \*While           | Продолжает итерацию, пока соблюдается условие                                               |

- [Util](#Util)
- [Math](#Math)
- [Collection](#Collection)
- [String](#String)
- [Lang](#Lang)
- [Object](#Object)
- [Array](#Array)
- [Function](#Function)

### Util

| функция            | описание                                              |                                               |
| ------------------ | ----------------------------------------------------- | --------------------------------------------- |
| \_.noop            | ничего не делает возвращает undefined                 | [видео](https://youtu.be/RIp8cF5yTY0?t=3167)  |
| \_.identity        | возвращает первый аргумент, который принимает         | [видео](https://youtu.be/RIp8cF5yTY0?t=3283)  |
| \_.stubFalse       | всегда возвращает false                               | [видео](https://youtu.be/RIp8cF5yTY0?t=3382)  |
| \_.stubTrue        | всегда возвращает true                                |                                               |
| \_.stubArray       | всегда возвращает новый пустой array                  |                                               |
| \_.stubObject      | всегда возвращает новый пустой object                 |                                               |
| \_.stubString      | всегда возвращает пустую строку                       |                                               |
| \_.uniqueId        | генерирует уникальный id                              | [видео](https://youtu.be/RIp8cF5yTY0?t=3462)  |
| \_.defaultTo       | проверка значения по умолчанию                        | [видео](https://youtu.be/RIp8cF5yTY0?t=6613)  |
| \_.toPath          | конвертирует значения в свойства массива              | [видео](https://youtu.be/RIp8cF5yTY0?t=6699)  |
| \_.range           | создает массив чисел c шагом                          | [видео](https://youtu.be/RIp8cF5yTY0?t=7956)  |
| \_.constant        | создает функцию,которая возвращает значение аргумента | [видео](https://youtu.be/RIp8cF5yTY0?t=8757)  |
| \_.property        | позволяет переключиться в написание мелких функций    | [видео](https://youtu.be/RIp8cF5yTY0?t=9240)  |
| \_.iteratee        | итерация с shorthands                                 | [видео](https://youtu.be/RIp8cF5yTY0?t=10789) |
| \_.matches         | создает функцию проверяющую глубокое сравнение        |                                               |
| \_.matchesProperty | сравнивает одно свойство                              | [видео](https://youtu.be/RIp8cF5yTY0?t=11093) |

[назад](#Cheatsheet-Lodash)

### Math

| функция     | описание                                |                                              |
| ----------- | --------------------------------------- | -------------------------------------------- |
| \_.add      | сложение                                | [видео](https://youtu.be/RIp8cF5yTY0?t=3513) |
| \_.divide   | деление                                 |                                              |
| \_.multiply | умножение                               |                                              |
| \_.subtract | вычитание                               |                                              |
| \_.ceil     | округление к большему, в целых десятках | [видео](https://youtu.be/RIp8cF5yTY0?t=3578) |
| \_.floor    | округление к меньшему, в целых десятках |                                              |
| \_.round    | округление до целого, в целых десятках  |                                              |
| \_.max      | максимальное число в Array              | [видео](https://youtu.be/RIp8cF5yTY0?t=3728) |
| \_.min      | минимальное число в Array               |                                              |
| \_.mean     | среднее число в Array                   |                                              |
| \_.sum      | сумма Array                             |                                              |

[назад](#Cheatsheet-Lodash)

### Collection

| функция    | описание                                                   |                                               |
| ---------- | ---------------------------------------------------------- | --------------------------------------------- |
| \_.size    | размер коллекции                                           | [видео](https://youtu.be/RIp8cF5yTY0?t=3757)  |
| \_.filter  | возвращает отфильтрованную коллекцию                       | [видео](https://youtu.be/RIp8cF5yTY0?t=10620) |
| \_.map     | каждый элемент коллекции модифицирует указанной фунцией    | [видео](https://youtu.be/RIp8cF5yTY0?t=11447) |
| \_.reduce  | свертывает коллекцию в одно значение                       | [видео](https://youtu.be/RIp8cF5yTY0?t=11561) |
| \_.orderBy | сортировка по указанным значениям, и порядком asc или desc | [видео](https://youtu.be/RIp8cF5yTY0?t=11730) |
| \_.groupBy | группировка с shorthands                                   | [видео](https://youtu.be/RIp8cF5yTY0?t=11781) |

[назад](#Cheatsheet-Lodash)

### String

| функция         | описание                         |                                              |
| --------------- | -------------------------------- | -------------------------------------------- |
| \_.camelCase    | 'fooBar'                         | [видео](https://youtu.be/RIp8cF5yTY0?t=3928) |
| \_.kebabCase    |                                  |                                              |
| \_.lowerCase    |                                  |                                              |
| \_.snakeCase    |                                  |                                              |
| \_.startCase    |                                  |                                              |
| \_.upperCase    |                                  |                                              |
| \_.trim         | обрезка стоки                    | [видео](https://youtu.be/RIp8cF5yTY0?t=4094) |
| \_.trimEnd      |                                  |                                              |
| \_.trimStart    |                                  |                                              |
| \_.escape       | экранирование символов           | [видео](https://youtu.be/RIp8cF5yTY0?t=4175) |
| \_.unescape     |                                  |                                              |
| \_.escapeRegExp |                                  |                                              |
| \_.pad          | дополнение строки символами      | [видео](https://youtu.be/RIp8cF5yTY0?t=4354) |
| \_.padEnd       |                                  |                                              |
| \_.padStart     |                                  |                                              |
| \_.toLower      | преобразование в нижний регистр  |                                              |
| \_.toUpper      | преобразование в верхний регистр |                                              |

[назад](#Cheatsheet-Lodash)

### Lang

| функция        | описание                             |                                              |
| -------------- | ------------------------------------ | -------------------------------------------- |
| \_.isArray     | проверяет тип array                  | [видео](https://youtu.be/RIp8cF5yTY0?t=5164) |
| \_.isArrayLike |                                      | [видео](https://youtu.be/RIp8cF5yTY0?t=5249) |
| \_.isObject    | проверяет тип object                 | [видео](https://youtu.be/RIp8cF5yTY0?t=5338) |
| \_.isUndefined | проверяет undefined                  | [видео](https://youtu.be/RIp8cF5yTY0?t=5534) |
| \_.isBoolean   | проверяет примитивы                  | [видео](https://youtu.be/RIp8cF5yTY0?t=5749) |
| \_.isNumber    |                                      |                                              |
| \_.isString    |                                      |                                              |
| \_.isFunction  | проверяет тип function               | [видео](https://youtu.be/RIp8cF5yTY0?t=6098) |
| \_.isEmpty     | проверяет на пустоту типы            | [видео](https://youtu.be/RIp8cF5yTY0?t=6258) |
| \_.isError     | проверяет ошибки                     | [видео](https://youtu.be/RIp8cF5yTY0?t=6325) |
| \_.isEqual     | проверяет глубокое сравнение типов   | [видео](https://youtu.be/RIp8cF5yTY0?t=6375) |
| \_.isMatch     | проверяет частичное совпадение типов | [видео](https://youtu.be/RIp8cF5yTY0?t=6440) |
| \_.toArray     | преобразование в массив              | [видео](https://youtu.be/RIp8cF5yTY0?t=6527) |
| \_.toFinite    |                                      |                                              |
| \_.toInteger   |                                      |                                              |
| \_.toNumber    |                                      |                                              |
| \_.toString    |                                      |                                              |

[назад](#Cheatsheet-Lodash)

### Object

| функция          | описание                                                                               |                                               |
| ---------------- | -------------------------------------------------------------------------------------- | --------------------------------------------- |
| \_.get           | получение вложенного свойства объекта по пути                                          | [видео](https://youtu.be/RIp8cF5yTY0?t=6763)  |
| \_.has           | проверяет есть ли свойство(собственное) в объекте                                      | [видео](https://youtu.be/RIp8cF5yTY0?t=7015)  |
| \_.hasIn         | проверяет есть ли свойство(собственное и унаследованное) в объекте                     | [видео](https://youtu.be/RIp8cF5yTY0?t=7089)  |
| \_.pick          | копирует указанные свойства                                                            | [видео](https://youtu.be/RIp8cF5yTY0?t=7121)  |
| \_.omit          | удаляет указанные свойства                                                             | [видео](https://youtu.be/RIp8cF5yTY0?t=7160)  |
| \_.at            | возвращает по указанныму пути значения в виде массива                                  | [видео](https://youtu.be/RIp8cF5yTY0?t=7218)  |
| \_.keys          | возвращает только собственные перечисляемые свойства в виде массива                    | [видео](https://youtu.be/RIp8cF5yTY0?t=7257)  |
| \_.valuesIn      | возвращает все значения (собственные и унаследованные) в виде массива                  | [видео](https://youtu.be/RIp8cF5yTY0?t=7323)  |
| \_.toPairs       | преобразует объект с ключами и значениями в массив пар массивов                        | [видео](https://youtu.be/RIp8cF5yTY0?t=7363)  |
| \_.set           | устанавливает вложенное значение объекта по пути                                       | [видео](https://youtu.be/RIp8cF5yTY0?t=7483)  |
| \_.unset         | удаляет вложенное значение объекта по пути (кроме свойства configurable)               | [видео](https://youtu.be/RIp8cF5yTY0?t=7596)  |
| \_.assign        | сливает один объект в другой                                                           | [видео](https://youtu.be/RIp8cF5yTY0?t=7712)  |
| \_.defaultsDeep  | устанавливает свойства исходных объектов, одинаковые свойства игнорируются.(в глубину) | [видео](https://youtu.be/RIp8cF5yTY0?t=7857)  |
| \_.merge         | объединяет объекты, включая унаследованные свойства                                    | [видео](https://youtu.be/RIp8cF5yTY0?t=7909)  |
| \_.update        | объединение функций get и set                                                          | [видео](https://youtu.be/RIp8cF5yTY0?t=8924)  |
| \_.assignIn      | сливает один объект в другой , работает с унаследованными свойствами                   | [видео](https://youtu.be/RIp8cF5yTY0?t=9022)  |
| \_.assignInWidth | сливает один объект в другой , работает с унаследованными свойствами, с customizer     |                                               |
| \_.mergeWith     | объединяет объекты, включая унаследованные свойства, с customizer                      | [видео](https://youtu.be/RIp8cF5yTY0?t=9162)  |
| \_.pickBy        | копирует указанные свойства по условию                                                 | [видео](https://youtu.be/RIp8cF5yTY0?t=10452) |
| \_.omitBy        | удаляет указанные свойства по условию                                                  |                                               |

[назад](#Cheatsheet-Lodash)

### Array

| функция         | описание                                                                      |                                              |
| --------------- | ----------------------------------------------------------------------------- | -------------------------------------------- |
| \_.fromPairs    | преобразует массив пар в объект с ключами и значениями                        | [видео](https://youtu.be/RIp8cF5yTY0?t=7449) |
| \_.head         | возвращает первый элемент                                                     | [видео](https://youtu.be/RIp8cF5yTY0?t=8036) |
| \_.last         | вовращает последний элемент                                                   |                                              |
| \_.nth          | возвращает элемент по позиции                                                 |                                              |
| \_.drop         | создает срез из массива и выкидывает из него n элементов слева                | [видео](https://youtu.be/RIp8cF5yTY0?t=8133) |
| \_.dropRight    | создает срез из массива и выкидывает из него n элементов справа               |                                              |
| \_.initial      | создает срез из массива кроме последнего элемента                             |                                              |
| \_.slice        | создает срез из массива в указанном диапазоне                                 |                                              |
| \_.tail         | создает срез из массива кроме первого элемента                                |                                              |
| \_.take         | создает срез массива из первых n элементов                                    |                                              |
| \_.takeRight    | создает срез массива из последних n элементов                                 |                                              |
| \_.compact      | убрать из массива все значения приводимые к false                             | [видео](https://youtu.be/RIp8cF5yTY0?t=8256) |
| \_.pull         | убирает указанные элементы из массива, мутируя исходный массив                |                                              |
| \_.without      | убирает указанные элементы из массива, не мутируя исходный массив             |                                              |
| \_.flatten      | разворачивает вложженый массив на один уровень                                | [видео](https://youtu.be/RIp8cF5yTY0?t=8355) |
| \_.flattenDeep  | разворачивает вложженые массивы в один                                        |                                              |
| \_.flattenDepth | разворачивает вложженые массивы на указанный уровень                          |                                              |
| \_.concat       | создает новый массив присоединением указанного массива и любого значения      | [видео](https://youtu.be/RIp8cF5yTY0?t=8440) |
| \_.difference   | создает массив из элементов которые есть в первом массиве ,но нет в следующих |                                              |
| \_.intersection | создает массив из элементов которые есть во всех массивах                     |                                              |
| \_.union        | создает массив из уникальных значений со всех массивов                        |                                              |

[назад](#Cheatsheet-Lodash)

### Function

| функция    | описание                                                     |                                               |
| ---------- | ------------------------------------------------------------ | --------------------------------------------- |
| \_.partial | аналог стрелочной функции                                    | [видео](https://youtu.be/RIp8cF5yTY0?t=9988)  |
| \_.curry   | каррирование функции                                         | [видео](https://youtu.be/RIp8cF5yTY0?t=10285) |
| \_.negate  | возвращает функцию, которая инвернтирует результат предиката | [видео](https://youtu.be/RIp8cF5yTY0?t=10936) |

[назад](#Cheatsheet-Lodash)
