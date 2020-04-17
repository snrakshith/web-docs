# Jest Introduction

### Its a framework for testing javascripts and it is built by `Facebook`.

- Jest combines the best parts of

  - Test Runner **`Mocha`**
  - Assertion Library **`Chai`**
  - Headless Browser **`Puppeter`**

- Naming conventions of the test files:

  - **`fileName.spec.js`**
  - **`fileName.test.js`**

## Some Usefull Commands:

```js
1. jest
2. jest -watch
```

---

## There are few concepts:

- Matchers
- Expect Function _`The complete testing logic goes in here!!.`_

---

1. ### Remember `1 Test File` is equal to `1 Test Suit`.

2. ### When dealing with `async data` always use ,

- _Assertions_
- _Return Statements_

---

- For references (objects) types use
  .toEqual() matcher

- For primitive types use
  .toBe() matcher

- For Regex expression use
  .toMatch() matcher

- For Array types use
  .toContain() matcher

---
