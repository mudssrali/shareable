# Developer [Carlos Caballero](https://twitter.com/Carlillo)

### Tip # 1

Getting an array of `unique` values is probably easier than you think.

![unique-elems](./media/carlillo/unique-elems.jpeg)

### Tip # 2

Ever need to filter falsy values (0, undefined, null, false, etc.) out of an array?  Just pass Boolean and all those falsy value go away!

![filter-undefined](./media/carlillo/filter-elems.jpeg)

### Tip # 3

`Object.fromEntries()` in ES10! Transform a list of key & value pairs into an object

![object-from-entries](./media/carlillo/object-from-entries.jpeg)

### Tip # 4

A stable sorting algorithm is when two objects with equal keys appear in the same order in the sorted output as they appear in the unsorted input

![stable-sort](./media/carlillo/stable-sort.jpeg)

### Tip # 5

Understanding Default Values with JavaScript's `Destructuring` 🧠🧠

> const { eyes = ' 👀' } = object

![stable-sort](./media/carlillo/destructing-default.jpeg)

### Tip # 6

Flatten Arrays in Vanilla JavaScript using `flat()` and `flatMap()`

![flat-map](./media/carlillo/flat-flatmap.jpeg)

### Tip # 7

`Function.toString()` in ES10! The `toString()` method returns a string representing the source code of the function

![to-string](./media/carlillo/func-tostring.jpeg)

### Tip # 8 Dynamic Import

Dynamic `import()` returns a promise for the module namespace object of the requested module. Therefore, imports can now be assigned to a variable using async/await.

![dynamic-import](./media/carlillo/func-tostring.jpeg)

### Tip # 9 Multi-Condition Checking

Multi condition checking! if input is '🔬', '📜', or '👊', call doSomething function then you can use a nice shorthand 👍

![multi-condition](./media/carlillo/multi-condition.jpeg)

Best Replies

- You could also just write `['🔬', '📜', '👊'].includes(input)` - there's no need for the comparison function. [Lenz Weber](https://twitter.com/phry)

### TIp # 10 Reduce and ReduceRight

The `reduceRight` method applies a function against an accumulator and each value of the array (from right-to-left) to reduce it to a single value.

![multi-condition](./media/carlillo/reduce-right.jpg)

### Tip # 11 Async Iteration in for...of

Asynchronous Iteration in ES2018! Asynchronous iterators  returns a promise for a { value, done } pair. we can now use the await keyword with for … of loops.

![async-forof](./media/carlillo/async-forof.jpeg)

- [Twelve ES10 Features in Twelve Simple Examples](https://medium.com/better-programming/twelve-es10-features-in-twelve-simple-examples-6e8cc109f3d3)

[:arrow_up: Back to top](#developer-carlos-caballero)