# Function: `???`

Write the code out for the following function in Pascal or C. Then hand execute the code you
have written.

Once you have done that, give a name for this function based on what you think
it does.

## Details

### Return Type

The function returns a **Boolean** value.

### Parameters

- **`data`**, an array of Integers **passed in by reference**
- **`numb`**, an Integer
- **`new`**, an Integer

and, if you decide to use C:

- **`size`**, an Integer

## Steps

1. Assign `result` to `false`.
2. For each element in the array `data`, check if the current value is equal to `numb`.
3. If so, the current value, `data[i]`, is now equal to `new` and result is now `true`.

### Hand Execution Data

- **`data`** = `[1, 4, 1, 2, 5, 1, 8]`
- **`size`** = `7`
- **`numb`** = `1`
- **`new`**  = `0`

### Example Result

```
data   is now = [0, 4, 0, 2, 5, 0, 8]
result is now = true
```
