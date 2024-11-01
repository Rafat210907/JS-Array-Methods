# JS-Array-Methods
## 1. `push()`
- **Purpose**: Adds one or more elements to the end of an array.
- **Returns**: New length of the array.
- **Example**:
    ```js
    let arr = [1, 2, 3];
    arr.push(4); // [1, 2, 3, 4]
    ```
## 2. `pop()`
- **Purpose**: Removes the last element from an array.
- **Returns**: The removed element.
- **Example**:
    ```js
    let arr = [1, 2, 3];
    arr.pop(); // [1, 2], returns 3
    ```

## 3. `shift()`
- **Purpose**: Removes the first element from an array.
- **Returns**: The removed element.
- **Example**:
    ```js
    let arr = [1, 2, 3];
    arr.shift(); // [2, 3], returns 1
    ```
## 4. `unshift()`
- **Purpose**: Adds one or more elements to the beginning of an array.
- **Returns**: New length of the array.
- **Example**:
    ```js
    let arr = [1, 2, 3];
    arr.unshift(0); // [0, 1, 2, 3]
    ```
## 5. `concat()`
- **Purpose**: Merges two or more arrays without modifying the original arrays.
- **Returns**: A new array.
- **Example**:
    ```js
    let arr1 = [1, 2];
    let arr2 = [3, 4];
    let result = arr1.concat(arr2); // [1, 2, 3, 4]
    ```
