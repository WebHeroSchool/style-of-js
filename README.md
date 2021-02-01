# My JavaScript Style Guide
## Содержание
1. [Объявление переменных](#Объявление-переменных)
2. [Наименование переменных](#Наименование-переменных)
3. [Точка с запятой](#Точка-с-запятой)
4. [Объявление объекта](#Объявление-объекта)
5. [Ключ значение объекта](#Ключ-значение-объекта)
6. [Массивы](#Массивы)
7. [Операторы сравнения](#Операторы-сравнения)
8. [Пробелы](#пробелы)
9. [Строки](#строки)
10. [Функции](#функции)

&nbsp;

1. Объявление переменных

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
2. Наименование переменных (#Наименование переменных)

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

3.Точка с запятой

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

4. Объявление объекта

Для объявления объекта использую фигурные скобки.

❌ не надо так 👇

```const item = new Object();
 ```

✅ надо так 👇

```const item = {};
```

5. Ключ значение объекта

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

6. Массивы

Используй квадратные скобки [ ] для объявления массивов.

❌ не надо так 👇

```const items = new Array();
 ```

✅ надо так 👇

```const items = [];
```

7. Операторы сравнения

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

8. Пробелы

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

9. Строки

Используй одинарные кавычки ' ' для строк.

❌ не надо так 👇

```const name = "Capt. Janeway";
 ```

✅ надо так 👇

```const name = 'Capt. Janeway';
```

10. Функции

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
