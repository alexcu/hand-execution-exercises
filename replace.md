# Function: `???`

- __Returns:__ Boolean
- __Parameters:__
  - `data`, an array of Integer passed in by reference;
  - `sz`, an Integer (C only);
  - `num`, an Integer;
  - `new`, an Integer

## Steps

0. Assign `result` to `false`
1. For each element in the array `data` check if the current value is equal to `num`
2. If so, the current value is now equal to `new` and result is now `true`

### Hand Execution Data

  data: [1, 4, 1, 2, 5, 1, 8]

---

  sz: 7

---

  num: 1
