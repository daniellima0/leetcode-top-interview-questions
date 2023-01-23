# Easy Collection

## Array Section

### Remove Duplicates from Sorted Array

```js
var removeDuplicates = function (nums) {
	let lastItem,
		duplicatesCounter = 0;

	for (let i = 1; i < nums.length; i++) {
		lastItem = nums[i - 1];
		currentItem = nums[i];

		if (lastItem == currentItem) {
			nums.splice(i, 1);
			i -= 1;
			duplicatesCounter++;
		}
	}

	return nums.length;
};
```

### Best Time to Buy and Sell Stock II

```js


```
