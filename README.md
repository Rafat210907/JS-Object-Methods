# JS-Object-Methods
## 1. Object.keys()
- *Purpose*: Returns an array of a given object's own enumerable property names.
- *Returns*: An array of keys.
- *Example*:
    ```js
    const obj = {a: 1, b: 2, c: 3};
    const keys = Object.keys(obj); // ['a', 'b', 'c']
    ```

## 2. Object.values()
- *Purpose*: Returns an array of a given object's own enumerable property values.
- *Returns*: An array of values.
- *Example*:
    ```js
    const obj = {a: 1, b: 2, c: 3};
    const values = Object.values(obj); // [1, 2, 3]
    ```
## 3. Object.entries()
- *Purpose*: Returns an array of a given object's own enumerable property [key, value] pairs.
- *Returns*: An array of arrays containing key-value pairs.
- *Example*:
    ```js
    const obj = {a: 1, b: 2, c: 3};
    const entries = Object.entries(obj); // [['a', 1], ['b', 2], ['c', 3]]
    ```
