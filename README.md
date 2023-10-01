# WeridScript
JavaScript but ~~weirder~~ better. WeridScript adds all the features that JavaScript misses and removes all the features that make using JavaScript a pain, if something is not clarified then it is the same as it would be in JavaScript (Node).

## Values
A value is anything you can manipulate. Values include simple things like numbers, text and switches. They are case-insensitive.
```
> 1 // This is a number
Object Number
> "Hello!" // This is a text (you must use double quotes)
Object Text
> true, False // These are switches
Object Switch
> On, off // These are also switches
Object Switch
> down, Up // These are of course also switches
Object Switch
> Good, bad // These are of course also switches
Object Switch
```
In WeridScript everything is an object even from the ~~interpreter~~ compiler's point of view. (WeridScript is compiled and the WeridScript interpreter is actually your input becing compiled in real-time blazingly fast through groundbreaking modern technologies)

## Arrays
Arrays are lists of values and are always immutable. Every item in an array must ~~be the same type~~ not be the same type.

```
> [1, 2, 3]
Object Array
```

## Operators
An operator is anything that can be used to manipulate a value. The operators are add, subtract, floor divide, concatenate, set, ~~and even multiply~~. WeridScript doesn't have multiplication as it is just repeatedly adding.

```
> 1+1
Object Add
> 4-2
Object Subtract
> 10/2
Object Divide
> 10//3
Object FloorDivide
> "hey"++"hey"
Object Concentate
> "hey"++on
Object Concentate
```

The result of an operator is of course an object. ~~(This will change in the future because the No Objects Foundation has required us to delete objects from WeridScript)~~

## Getting And Setting Values

To set a value to another value like setting a text to a number we use the set operator. Note that setting values like numbers or switches might cause confusion.

```
> "var"=42
42
> 2=3
3
> on="hey"
"hey"
```

To get a value, use the representation function.

```
> 2
Object Number
> 2.repr()
3
```

## Loops

We found out that the only loop actually needed is the while loop so we have removed all loops except the while loop. We also found out that indentation makes a huge different in the size of a project especially in projects with 2000 dependencies and 10000 dependencies if we count the dependencies of those dependencies and that is a common thing, so we have removed indentation.

```
> "n"=0
[Object Number]
> while (n<10) {
... "n"=n+1
... }
[Object Number]
```

We have a "forever" loop however since most languages are missing this essential loop somehow.

```
> forever {
... console.log("DADDY, I am famous! Look I am getting mentioned in the GitHub repo of WeridScript! This is the best day in my life as a function")
... }
DADDY, I am famous! Look I am getting mentioned in the GitHub repo of WeridScript! This is the best day in my life as a function
DADDY, I am famous! Look I am getting mentioned in the GitHub repo of WeridScript! This is the best day in my life as a function
DADDY, I am famous! Look I am getting mentioned in the GitHub repo of WeridScript! This is the best day in my life as a function
...
```
(69 more times before ~~we bothered to hit Control-C~~ the machine started functioning properly again have been hidden)

To do the "for" and "for each" loops, you can use the following code.

```
> // For
> "i"=0
[Object Number]
> while (i<11) {
... console.log(i)
... "i"=i+1
... }
0
1
2
3
4
5
6
7
8
9
10
11
>
> // For each
> array=[1, 2, 3]
> "i"=0
> while (i<array.length) {
...  console.log(array[i])
...  "i"=i+1
... }
1
2
3
3
```

## Functions

Functions can be called the same as in JavaScript but defining functions in WeridScript is much ~~more weirder~~ more better. You can use any keyword from any other language to define functions. function, func, fun, fn, def, define, to name a few. You can also choose one universal keyword by setting the universal function keyword option at the start of your program.

```
> "__universalfunctionkeyword__"="fun"
[Object Text]
> fun add (a, b) -> { return a+b }
[Object Function]
> add(2, 2)
[Object Number]
```

You need to point the arguments to the function body which we think makes it much clear that the arguments take effect in the function body which could be unclear otherwise.

## Classes

~~There is no such thing as classes, OOP is terrible!~~ To create a class we first need to create an object and use the `Prototype` object to create a prototype from that object and create a new object which extends the prototype to create an instance.

```
> "animal"={"name": null, "age": null, "type": null}
[Object Object]
> "animap"=Prototype(animal)
[Object Prototype]
> "instance"=animap.extend(name="John", age=10, type="Dog")
[Object Object]
> console.log(instance.name) // John
[Object Text]
> console.log(instance.age) // 10
[Object Number]
> console.log(instance.type) // Dog
[Object Text]
```

## typeof
A lot of confusion can come from the types in JavaScript so we have improved it and the typeof ~~operator~~ function in WeridScript is way ~~weirder~~ better!

```
> typeof(2)
[Object Number]
> typeof(typeof(2))
[Object Object]
> typeof(typeof(typeof(2)))
[Object Array]
> typeof(typeof(typeof(typeof(2))))
[Object Object]
> typeof(typeof)
[Object Function]
> typeof(typeof)++"hey"
[Object Function, Object Text]
> typeof(typeof)++typeof(typeof)
[Object Function, [Object Function]]
> typeof(Object)
[Object __internals__.object]
> typeof(__internals__.object)
Uncaught ReferenceError: __internals__.object is not defined
```

## Compiler
~~The compiler is currently at [REDACTED]~~
A group of birds destroyed our servers so you cannot download the compiler right now, we are aiming to bring the compiler back in -1 days.

## Where To Go From Here?
You can look at the `src` directory to get the source code of the compiler or look at the `resc` directory for resources.

## Suggestions
You can suggest improvements using issues and implement them yourself using pull requests!
