**Questions with answers**

1. What are some differences between interfaces and types in TypeScript?
**Answer:**

Use `interface` for objects/classes.
Use `type` when you need more flexibility like unions or tuples.

`interface` supports merging.
`type` does not support merging.

`interface` more readable for object shapes.
`type` more flexible, especially for complex types.

3. Explain the difference between `any`, `unknown`, and `never` types in TypeScript.

**Answer:**
`any`: Accepts anything, no type checks.
`unknown`: Accepts anything, but you must check before use.
`never`: A type for something that never returns.