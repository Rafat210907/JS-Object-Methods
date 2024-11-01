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

## 4. Object.assign()
- *Purpose*: Copies the values of all enumerable own properties from one or more source objects to a target object.
- *Returns*: The target object.
- *Example*:
    ```js
    const target = {a: 1};
    const source = {b: 2};
    const result = Object.assign(target, source); // {a: 1, b: 2}
    ```
## 5. Object.freeze()
- *Purpose*: Freezes an object, preventing new properties from being added and existing properties from being modified or deleted.
- *Returns*: The frozen object.
- *Example*:
    ```js
    const obj = {a: 1};
    Object.freeze(obj);
    obj.a = 2; // Error in strict mode, ignored otherwise
    ```
