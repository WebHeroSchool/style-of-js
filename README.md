# My JavaScript Style Guide
## Содержание
1. [Объявление переменных](#oбъявление-переменных)
2. [Наименование переменных](#наименование-переменных)
3. [Точка с запятой](#точка-с-запятой)
4. [Объявление объекта](#объявление-объекта)
5. [Ключ значение объекта](#ключ-значение-объекта)
6. [Массивы](#массивы)
7. [Операторы сравнения](#операторы-сравнения)
8. [Пробелы](#пробелы)
9. [Строки](#строки)
10. [Функции](#функции)

&nbsp;

## Объявление переменных

Всегда используйте let или const для объявления переменных.

❌ не надо так 👇
```javascript
uperPower = new SuperPower();
```

&nbsp;

✅ надо так 👇
```javascript
const superPower = new SuperPower();
```
## Наименование переменных

Используйте camelCase для названий переменных, объектов и функций.

❌ не надо так 👇

```const OBJEcttsssss = {};
const this_is_my_object = {};
function c() {}
 ```

✅ надо так 👇

```const thisIsMyObject = {};
function thisIsMyFunction() {}
```

## Точка с запятой

Всегда ставьте точку с запятой в конце выражения.

❌ не надо так 👇

```const luke = {}
const leia = {}
[luke, leia].forEach((jedi) => jedi.father = 'vader')
 ```

✅ надо так 👇

```const luke = {};
const leia = {};
[luke, leia].forEach((jedi) => {
  jedi.father = 'vader';
});
```

## Объявление объекта

Для объявления объекта использую фигурные скобки.

❌ не надо так 👇

```const item = new Object();
 ```

✅ надо так 👇

```const item = {};
```

## Ключ значение объекта

Не дублируй названия ключей в объектах.

❌ не надо так 👇

```var foo = {
    bar: "baz",
    bar: "qux"
};

var foo = {
    "bar": "baz",
    bar: "qux"
};
 ```

✅ надо так 👇

```var foo = {
    bar: "baz",
    quxx: "qux"
};
```

## Массивы

Используй квадратные скобки [ ] для объявления массивов.

❌ не надо так 👇

```const items = new Array();
 ```

✅ надо так 👇

```const items = [];
```

## Операторы сравнения

Используй === и !== (строгое сравнение ), вместо == и != (нестрогое сравнение).

❌ не надо так 👇

```a == b
foo == true
bananas != 1
value == undefined
 ```

✅ надо так 👇

```typeof foo === 'undefined'
'hello' !== 'world'
0 === 0
true === true
foo === null
```

## Пробелы

Используйте отступ в 2 пробела

❌ не надо так 👇

``function foo() {
∙∙∙∙let name;
}


function bar() {
∙let name;
}
 ```

✅ надо так 👇

```function baz() {
∙∙let name;
}
```

## Строки

Используй одинарные кавычки ' ' для строк.

❌ не надо так 👇

```const name = "Capt. Janeway";
 ```

✅ надо так 👇

```const name = 'Capt. Janeway';
```

## Функции

 Всегда ставь один пробел перед () и перед {} в функциях.

   ❌ не надо так 👇

```const f = function(){};
const g = function (){};
const h = function() {};
```

✅ надо так 👇

```const x = function () {};
const y = function a() {};
```
