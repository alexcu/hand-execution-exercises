# Function: `???`

- __Returns:__ Boolean
- __Parameters:__ 
 	- `data`, an array of Integer passed in by reference;
 	- `sz`, an Integer (C only);
	- `num`, an Integer

## Steps

0. Assign `result` to `false`
1. For each element in the array `data` check if the current value (`data[i]`) is equal to `num`
2. If so, `result` is now `true` and for each value starting at the current value (`data[i]`) ending before the very last value in the array `data` is now equal to this loop's current value's next value (`data[j] := data[j+1]`)
4. The last value in `data` is equal to `0`

### Hand Execution Data

	data: [5, 6, 7, 8, 9, 10, 11, 12]
	
---
	
	sz: 8
	
---

	num: 8