# Developer [Tomek Sułkowski](https://twitter.com/sulco)

### Tip # 1

When you return an array, **TypeScript** infers the type as an `Array` of included types (see attached code)
If you want this value to be inferred as a Tuple instead, add `as const` to the return statement

![tip-one](./media/sulco/1.jpeg)