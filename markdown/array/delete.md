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

and, if you decide to use C:

- **`size`**, an Integer

## Steps

1. Assign `result` to `false`.
2. For each element in the array `data` check if the current value, `data[i]`, is equal to `numb`.
3. If so, `result` is now `true` and for each value starting at this current value, `data[j]`, ending before the very last value in the array `data`, assign that value to this loop's current value's next value, i.e., `data[j] := data[j+1]`.
4. The last value in `data` is equal to `0`.

## Hand Execution Data

- **`data`** = `[5, 6, 7, 8, 9, 10, 11, 12]`
- **`numb`** = `8`
- **`size`** = `8`

### Example Result

```
data   is now = [5, 6, 7, 9, 10, 11]
result is now = true
```
