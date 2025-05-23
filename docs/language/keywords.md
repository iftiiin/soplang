# Soplang Keywords Reference

This document provides a reference for all keywords in the Soplang programming language, along with their meanings and examples of usage.

## Variable Declaration Keywords

| Keyword  | Meaning                      | English Equivalent | Example                                |
| -------- | ---------------------------- | ------------------ | -------------------------------------- |
| `door`   | Dynamic variable declaration | `var`/`let`        | `door magac = "Sharafdin"`             |
| `tiro`   | Integer type                 | `int`              | `tiro da = 25`                         |
| `jajab`  | Decimal/float type           | `float`/`double`   | `jajab qiimo = 3.14`                   |
| `qoraal` | String type                  | `string`           | `qoraal magac = "Sharafdin"`           |
| `bool`   | Boolean type                 | `bool`             | `bool waaRun = run`                    |
| `walax`  | Object type                  | `object`           | `walax person = { name: "Sharafdin" }` |
| `liis`   | List/array type              | `array`            | `liis numbers = [1, 2, 3]`             |
| `maran`  | Null value                   | `null`             | `door a = maran`                       |

## Control Flow Keywords

| Keyword       | Meaning           | English Equivalent | Example                                      |
| ------------- | ----------------- | ------------------ | -------------------------------------------- |
| `haddii`      | If statement      | `if`               | `haddii (x > 10) { bandhig("Weyn") }`        |
| `haddii_kale` | Else if statement | `else if`          | `haddii_kale (x == 10) { bandhig("Dhexe") }` |
| `ugudambeyn`  | Else statement    | `else`             | `ugudambeyn { bandhig("Yar") }`              |
| `dooro`       | Switch statement  | `switch`           | `dooro (x) { xaalad 1 { bandhig("Hal") } }`  |
| `xaalad`      | Case clause       | `case`             | `xaalad "A" { bandhig("Case A") }`           |

## Loop Keywords

| Somali Keyword | English Equivalent | Description             | Example                                    |
| -------------- | ------------------ | ----------------------- | ------------------------------------------ |
| `kuceli`       | `for`              | For loop                | `kuceli (i 1 ilaa 5) { bandhig(i) }`       |
| `ilaa`         | `to`               | Loop range end          | `kuceli (i 1 ilaa 5) { bandhig(i) }`       |
| `::`           | `step`             | Loop increment step     | `kuceli (i 1 ilaa 10 :: 2) { bandhig(i) }` |
| `intay`        | `while`            | While loop              | `intay (x < 5) { bandhig(x) }`             |
| `jooji`        | `break`            | Exit from a loop        | `haddii (x == 3) { jooji }`                |
| `soco`         | `continue`         | Skip one loop iteration | `haddii (x == 3) { soco }`                 |

## Function Keywords

| Keyword | Meaning              | English Equivalent | Example                            |
| ------- | -------------------- | ------------------ | ---------------------------------- |
| `hawl`  | Function declaration | `function`         | `hawl isuGee(a, b) { celi a + b }` |
| `celi`  | Return statement     | `return`           | `celi x * 2`                       |

## Error Handling Keywords

| Keyword    | Meaning            | English Equivalent | Example                             |
| ---------- | ------------------ | ------------------ | ----------------------------------- |
| `isku_day` | Try block          | `try`              | `isku_day { /* code */ }`           |
| `qabo`     | Catch block        | `catch`            | `qabo (khalad) { bandhig(khalad) }` |
| `throw`    | Throw an exception | `throw`            | `throw "Error message"`             |

## Object-Oriented Programming Keywords

| Keyword     | Meaning                       | English Equivalent | Example                                              |
| ----------- | ----------------------------- | ------------------ | ---------------------------------------------------- |
| `fasalka`   | Class declaration             | `class`            | `fasalka Qof { /* properties and methods */ }`       |
| `nafta`     | Reference to current instance | `this`             | `nafta.magac = magac`                                |
| `ka_dhaxal` | Inheritance                   | `extends`          | `fasalka Ardayga ka_dhaxal Qof { /* class body */ }` |
| `cusub`     | New object instantiation      | `new`              | `door ardayga = cusub Ardayga()`                     |

## Module Keywords

| Keyword   | Meaning          | English Equivalent | Example                 |
| --------- | ---------------- | ------------------ | ----------------------- |
| `ka_keen` | Import statement | `import`           | `ka_keen "math_lib.so"` |

## Special Values

| Somali Value | English Equivalent | Description         | Example                  |
| ------------ | ------------------ | ------------------- | ------------------------ |
| `run`        | `true`             | Boolean true value  | `haddii (run) { ... }`   |
| `been`       | `false`            | Boolean false value | `haddii (!been) { ... }` |
| `maran`      | `null`             | Empty/null value    | `door val = maran`       |

## Data Types

| Somali Type | English Equivalent | Description     | Example                          |
| ----------- | ------------------ | --------------- | -------------------------------- |
| `tiro`      | `int`/`number`     | Integer numbers | `tiro age = 25`                  |
| `jajab`     | `float`/`decimal`  | Decimal numbers | `jajab pi = 3.14`                |
| `qoraal`    | `string`           | Text values     | `qoraal name = "Ahmed"`          |
| `bool`      | `boolean`          | Truth values    | `bool isValid = run`             |
| `liis`      | `list`/`array`     | List of items   | `liis numbers = [1, 2, 3]`       |
| `walax`     | `object`           | Key-value pairs | `walax person = { name: "Ali" }` |

## Operators

| Somali Operator | English Equivalent | Description              | Example                   |
| --------------- | ------------------ | ------------------------ | ------------------------- |
| `+`             | `+`                | Addition                 | `x = a + b`               |
| `-`             | `-`                | Subtraction              | `x = a - b`               |
| `*`             | `*`                | Multiplication           | `x = a * b`               |
| `/`             | `/`                | Division                 | `x = a / b`               |
| `%`             | `%`                | Modulo                   | `x = a % b`               |
| `==`            | `==`               | Equal to                 | `haddii (a == b) {...}`   |
| `!=`            | `!=`               | Not equal to             | `haddii (a != b) {...}`   |
| `>`             | `>`                | Greater than             | `haddii (a > b) {...}`    |
| `<`             | `<`                | Less than                | `haddii (a < b) {...}`    |
| `>=`            | `>=`               | Greater than or equal to | `haddii (a >= b) {...}`   |
| `<=`            | `<=`               | Less than or equal to    | `haddii (a <= b) {...}`   |
| `&&`            | `&&`               | Logical AND              | `haddii (a && b) {...}`   |
| `\|\|`          | `\|\|`             | Logical OR               | `haddii (a \|\| b) {...}` |
| `!`             | `!`                | Logical NOT              | `haddii (!a) {...}`       |

> **Note:** Soplang supports the use of comparison operators directly in expressions without requiring additional parentheses. For example, `door x = a > b` is valid syntax to store the result of a comparison in a variable.

## Built-in Functions

| Function  | Meaning              | English Equivalent | Example                                  |
| --------- | -------------------- | ------------------ | ---------------------------------------- |
| `bandhig` | Print to console     | `print`            | `bandhig("Salaan, Adduunka!")`           |
| `gelin`   | Read input from user | `input`            | `door magac = gelin("Magacaaga geli: ")` |
| `nooc`    | Get type of variable | `typeof`           | `bandhig(nooc(magac))`                   |
| `tiro`    | Convert to number    | `int`/`float`      | `door n = tiro("5")`                     |
| `qoraal`  | Convert to string    | `str`              | `door s = qoraal(25)`                    |
| `bool`    | Convert to boolean   | `bool`             | `door b = bool(1)`                       |
| `liis`    | Create a list        | `list/array`       | `door list = liis(1, 2, 3)`              |
| `walax`   | Create an object     | `object/dict`      | `door obj = walax(name: "Ali", age: 25)` |

## List Methods

| Method        | English Equivalent        | Description                 | Example                           |
| ------------- | ------------------------- | --------------------------- | --------------------------------- |
| `dherer()`    | `length()`                | Get list length             | `numbers.dherer()`                |
| `kudar()`     | `push()` or `append()`    | Add item to end             | `numbers.kudar(5)`                |
| `kasaar()`    | `pop()`                   | Remove and return last item | `door last = numbers.kasaar()`    |
| `kudar(liis)` | `concat()`                | Concatenate lists           | `door all = list1.kudar(list2)`   |
| `leeyahay(x)` | `contains()`/`includes()` | Check if item exists        | `haddii (list.leeyahay(x)) {...}` |
| `nuqul()`     | `copy()`                  | Create a shallow copy       | `door copy = list.nuqul()`        |
| `nadiifi()`   | `clear()`                 | Remove all items from list  | `list.nadiifi()`                  |
| `rog()`       | `reverse()`               | Reverse the list in-place   | `list.rog()`                      |
| `habee()`     | `sort()`                  | Sort the list in-place      | `list.habee()`                    |

## Object Methods

| Method        | English Equivalent   | Description           | Example                               |
| ------------- | -------------------- | --------------------- | ------------------------------------- |
| `fure()`      | `keys()`             | Get all keys          | `door keys = obj.fure()`              |
| `leeyahay(x)` | `hasOwnProperty()`   | Check if key exists   | `haddii (obj.leeyahay("name")) {...}` |
| `tirtir(x)`   | `delete property`    | Delete a property     | `obj.tirtir("oldProp")`               |
| `kudar(obj)`  | `merge()`/`assign()` | Merge/copy properties | `door merged = obj1.kudar(obj2)`      |

## Error Message Terminology

| Somali Term | Meaning            | English Equivalent | Example Usage                                                     |
| ----------- | ------------------ | ------------------ | ----------------------------------------------------------------- |
| `Khalad`    | Error              | `Error`            | `Khalad lexer: Xaraf aan la filayn: @`                            |
| `sadar`     | Line (in code)     | `line`             | `ee sadar 12, goobta 18`                                          |
| `goobta`    | Position (in code) | `position`         | `ee sadar 12, goobta 18`                                          |
| `lexer`     | Lexical analyzer   | `lexer`            | `Khalad lexer: Xaraf aan la filayn: @`                            |
| `parser`    | Syntax analyzer    | `parser`           | `Khalad parser: Waxaa la filayay ')', laakiin waxaa la helay '+'` |
| `runtime`   | Execution time     | `runtime`          | `Khalad runtime: Ma suurtogali karto qeybinta eber`               |
| `nooc`      | Type               | `type`             | `Khalad nooc: Qiimaheeda '10' ma ahan qoraal`                     |

## Special Syntax

| Syntax  | Meaning             | English Equivalent | Example                               |
| ------- | ------------------- | ------------------ | ------------------------------------- |
| `//`    | Single-line comment | `//`               | `// Tani waa comment`                 |
| `/* */` | Multi-line comment  | `/* */`            | `/* Tani waa comment dheer */`        |
| `{ }`   | Code block          | `{ }`              | `haddii (x > 10) { bandhig("Weyn") }` |
| `( )`   | Expression grouping | `( )`              | `(a + b) * c`                         |
| `[ ]`   | List/array access   | `[ ]`              | `numbers[0]`                          |
| `.`     | Property access     | `.`                | `person.name`                         |
