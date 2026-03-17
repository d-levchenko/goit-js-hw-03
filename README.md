# goit-js-hw-03

JavaScript homework focusing on working with arrays and functions.

## Tasks

### Task 1: `slugify(title)`

Converts a title string into a URL-friendly slug format.

- Converts the title to lowercase
- Replaces spaces with hyphens
- Example: `"Arrays for beginners"` → `"arrays-for-beginners"`

**File:** [js/task-1.js](js/task-1.js)

---

### Task 2: `makeArray(firstArray, secondArray, maxLength)`

Concatenates two arrays and returns the first `maxLength` elements from the
result.

- Combines two arrays using `concat()`
- Returns only the first `maxLength` elements
- Example: `makeArray(['Mango', 'Poly'], ['Ajax', 'Chelsea'], 3)` →
  `["Mango", "Poly", "Ajax"]`

**File:** [js/task-2.js](js/task-2.js)

---

### Task 3: `filterArray(numbers, value)`

Filters an array of numbers and returns all numbers greater than a specified
value.

- Uses the `filter()` method to find numbers greater than the value
- Returns a new array with filtered results
- Example: `filterArray([1, 2, 3, 4, 5], 3)` → `[4, 5]`

**File:** [js/task-3.js](js/task-3.js)
