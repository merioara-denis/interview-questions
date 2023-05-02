# Вопросы на собеседования

## — React

**Назовите хуки, аргументы и для чего они используются**

- [ ]  useState - локальное состояние
- значение (исходное значение)
- функция (ленивое вычисление)
- [ ]  useEffect / useLayoutEffect (в чём разница)
- [ ]  useCallback
- [ ]  useMemo
- [ ]  useRef
- [ ]  useContext
- [ ]  useReducer

— Дополнительно —

- [ ]  useId
- [ ]  useImperativeHandle
- [ ]  useInsertionEffect
- [ ]  useSyncExternalStore
- [ ]  useTransition
- [ ]  useDebugValue
- [ ]  useDeferredValue

**Что такое HOC ?**

- [ ]  это функция, которая на входе принимает один компонент, а на выходе возвращает новый с более расширенным функционалом

**Для чего используется React.memo ?**

- [ ]  позволяет вашему компоненту пропускать повторный рендеринг с теми же реквизитами.

**Для чего используется React.forwardRef ?**

- [ ]  Для возможность проброса ссылки,

**В чем разница ReactDOM.createPortal и ReactDOM.render ?**

- [ ]  при использование **ReactDOM.createPortal** возможна перерисовка при изменений Props, **ReactDOM.render** будет игнорировать изменения Props

### — CSS

**Назовите какие css свойства знаете и для чего они используются ?**
- пример: margin, padding
- Ответ: 

**Какие свойства для управления “display: grid" знаете ?**

- [ ]  grid-template-rows , grid-template-columns,
- [ ]  grid-auto-flow
- [ ]  grid-template-areas
- [ ]  grid-row, grid-column, grid-area
- [ ]  grid-row-start, grid-column-start, grid-row-end, grid-column-end
- [ ]  row-gap, column-gap, gap
- [ ]  align-content
- [ ]  justify-content

**Какие свойства для управления “display: flex" знаете ?**

- [ ]  flex-basis
- [ ]  flex-direction
- [ ]  flex-flow
- [ ]  flex-grow
- [ ]  flex-shrink
- [ ]  flex-wrap
- [ ]  gap
- [ ]  align-content, align-items, align-self
- [ ]  justify-content, justify-items, justify-self

**Какие псевдоклассы знаете ?**
[https://developer.mozilla.org/ru/docs/Web/CSS/Pseudo-classes](https://developer.mozilla.org/ru/docs/Web/CSS/Pseudo-classes)

- [ ]  before, after
- [ ]  empty, not
- [ ]  active, hover, focus, visited
- [ ]  nth-child, nth-first-child, nth-last-child
- [ ]  first-child, last-child,
- [ ]  disabled, checked

**Что такое sprite и для чего он используется ?**

- [ ]  Собрание медиа изображений в один файл для ускорения загрузки страницы

### — HTML

**В чем разница между блочными и строчные элементы, приведите примеры тэгов ?**

Блочные элементы предназначены для структурирования основных частей вашей страницы, путём разделения содержимого на логически связанные блоки.

Строчные элементы предназначены, чтобы разграничить часть текста и придать ему определённую функцию или смысл. Строчные элементы, как правило, содержат одно или несколько слов.

Примеры блочных:

Примеры строчных:

- [ ]  К каким относиться параграф ? (Ответ: блочным)

**На что влияет не валидная верстки ?**

- [ ]  Возможна некорректное отображение cross browser-ной разметки ?
- [ ]  Увеличения времени отрисовки

## — JavaScript

**Назовите типы данных** 

- [ ]  undefined
- [ ]  boolean
- [ ]  number
- [ ]  string
- [ ]  bigint
- [ ]  symbol
- [ ]  null
- [ ]  object

**Как получить переменой ?**

- [ ]  typeof вернет string тип данных
- [ ]  для null результат typeof будет object, можно сравнить с null для исключения погрешность

**Назовите какие есть методы для работы с массивами (Array) ?**  

- [ ]  forEach 
- аргумент (item, index, array) ⇒ void
- [ ]  map 
- аргумент (item, index, array) ⇒ Результат
- [ ]  reduce 
- аргумент 1: (accumulate, item, index, array) ⇒ accumulate
- аргумент 2: начальное значение
- [ ]  indexOf
- аргументом передаём значение которое ищем 
- если не найден вернёт -1
- [ ]  findIndex
- аргумент (item, index, array) ⇒ boolean
- [ ]  filter
- аргумент (item, index, array) ⇒ boolean
- если не найден вернёт undefined
- [ ]  find
- аргумент (item, index, array) ⇒ boolean
- если не найден вернёт undefined
- [ ]  some
- аргумент (item, index, array) ⇒ boolean
- [ ]  every
- аргумент (item, index, array) ⇒ boolean
- [ ]  sort
- аргумент (a, b) ⇒ number (-1 | 1)

**Назовите какие есть методы для работы с объектами (Object) ?**  

- [ ]  keys - вернёт массив ключей
- [ ]  values - вернёт массив значений
- [ ]  entres - вернёт массив кортежей из двух значений ключ и значение
- [ ]  hasOwnProperty вернёт boolean есть ли в объекте такой ключ
- [ ]  assign создаст копию объекта
- [ ]  freeze назначит объект не редактируемым
- [ ]  create создаст новый объект на основе исходного

## — TypeScript

**Назовите служебные типы и что они делают**

- [ ]  Pick
- [ ]  Omit
- [ ]  Exclude
- [ ]  Extract
- [ ]  Partial
- [ ]  Required
- [ ]  Readonly
- [ ]  NonNullable
- [ ]  Parameters

— П**ринципы программирования**

**Расскажите как расшифровывается SOLID и о чем говорят эти принципы ?**

- [ ]  S - single responsibility (единственная зона ответственность, разделения на логические на сущности, где четко понятно зона ответственность)
- [ ]  O - open/close (код открыт для расширения и закрыт для изменения, разрешается добавлять функционал и запрещается изменять)
- [ ]  L - Liskov substitution (Интерфейсы наследники должны заменять родителей)
- [ ]  I - interface segregation (Дробления интерфейсов для возможность пере использования без реализаций избыточных методов)
- [ ]  D - dependency inversion (зависимость от интерфейсов вместо зависимость от реализаций, позволяет подменить реализацию)
*тут можно попросить привесить пример подключения к базе данных*

**Расскажите как расшифровывается DRY и о чем говорят эти принципы ?**

- [ ]  Don’t repeat yourself - код не должен повторяться, если в проекте код переиспользоваться его стоит поместить в набор переиспользуемых функций

**Расскажите как расшифровывается KISS и о чем говорят эти принципы ?**

- [ ]  Keep it simple, stupid - необходимо уходить от усложнения реализаций
- для повышения надёжность
- для поддержания более низкого порога входа
- для улучшения читаемость

**Расскажите как расшифровывается YAGNI и о чем говорят эти принципы ?**

- [ ]  You aren't gonna need it - Тебе это не понадобится (не делать того что не требуется в задаче)

**Назовите принципы ООП ?**

- [ ]  Полиморфизм
- [ ]  Наследование
- [ ]  Инкапсуляция
- [ ]  Абстракция

## — Проектирование

**Назовите паттерны ООП (Объектно-ориентированное программирование) ?**
тут не обязательно все, главное понимание ****Decorator, Adapter

- [ ]  Singleton (Одиночка)
- [ ]  Factory Method (Фабричный метод)
- [ ]  Abstract Factory (Абстрактная фабрика)
- [ ]  Prototype (Прототип)
- [ ]  Builder (Строитель)
- [ ]  Decorator (Декоратор)
- [ ]  Facade (Фасад)
- [ ]  Proxy (Заместитель)
- [ ]  Adapter (Адаптер)
- [ ]  Composite (Компоновщик)
- [ ]  Bridge (Мост)
- [ ]  Flyweight (Легковес)
- [ ]  Mediator (Посредник)
- [ ]  Iterator (Итератор)
- [ ]  Chain of Responsibility (Цепочка обязанностей)
- [ ]  Strategy (Стратегия)
- [ ]  Memento (Снимок)
- [ ]  Template Method (Шаблонный метод)
- [ ]  Visitor (Посетитель)
- [ ]  Command (Команда)
- [ ]  Observer (Наблюдатель)
- [ ]  State (Состояние)

**Что такое курирование (curry) ?**
[https://learn.javascript.ru/currying-partials](https://learn.javascript.ru/currying-partials)

- [ ]  трансформирование функций для передачи аргументов частями

**Что такое замыкание ?**
*приведите пример ?*

**Расскажите процесс отрисовки страницы в browser ?**
[https://doka.guide/js/how-the-browser-creates-pages/](https://doka.guide/js/how-the-browser-creates-pages/)
**Как работает React под капотом ?**
Для решения проблемы производительности используется концепция виртуального DOM.
