# isIt67.js

The most computationally extravagant way to check if a number equals 67. Now in javascript.

## Installation

Just download `isIt67.js` and place it in your JavaScript project (or don't).

## Import

### ES Modules (React, Vue, Angular, modern Node.js)

```javascript
import isIt67 from './isIt67.js';
// or
import isIt67 from 'is-it-67';
```

### CommonJS (Node.js)

```javascript
const isIt67 = require('./isIt67.js');
```

### Browser (vanilla)

```html
<script src="path/to/isIt67.js"></script>
<script>
  // isIt67 is available globally
  console.log(isIt67(67));
</script>
```

## API

### `isIt67(value)`

Returns `true` if the value is exactly the number `67`, otherwise `false`.

**Parameters:**
- `value` (any) - The value to test

**Returns:**
- `boolean` - `true` only for the number `67`

## Usage Examples

### Basic

```javascript
import isIt67 from './isIt67.js';

console.log(isIt67(67));   // true
console.log(isIt67(42));   // false
console.log(isIt67(100));  // false
```

### Real World (Please Don't)

```javascript
// Age verification for a very specific club
const age = 67;
if (isIt67(age)) {
  console.log("Welcome to the 67 Club. The password is 'sixty-seven'.");
} else {
  console.log("Come back when you're 67. Or 67. Not 66. Not 68. Exactly 67.");
}

// Secret code validation
const secretCode = 67;
if (isIt67(secretCode)) {
  activatePortal();
} else {
  console.log("Wrong code. The universe remains closed.");
}
```

### Examples & Outputs

```javascript
const isIt67 = require('./isIt67.js');

// Example 1: The imposter
console.log(isIt67("67"));
// Output: false
// Explanation: Strings are not numbers. Even if they look like numbers. Stop trying.

// Example 2: Floating point betrayal
console.log(isIt67(67.0000000000001));
// Output: false
// Explanation: The library has no mercy for rounding errors.

// Example 3: The classic mix-up
const meaningOfLife = 42;
console.log(isIt67(meaningOfLife));
// Output: false
// Explanation: 42 is the answer. Just not to this question.

// Example 4: Boolean confusion
console.log(isIt67(true));
// Output: false
// Explanation: true is 1. false is 0. Neither is 67. Basic math.

// Example 5: Array chaos
console.log(isIt67([67]));
// Output: false
// Explanation: "But it's an array containing 67!" - You
// "Don't care." - isIt67

// Example 6: Object deception
console.log(isIt67({ value: 67, isSixtySeven: true }));
// Output: false
// Explanation: The library is not impressed by your objects.

// Example 7: Null and void
console.log(isIt67(null));
// Output: false
// Explanation: null is nothing. 67 is something. These are different.

// Example 8: Undefined behavior
console.log(isIt67(undefined));
// Output: false
// Explanation: Even the library doesn't know what you meant.

// Example 9: The off-by-one tragedy
for (let i = 66; i <= 68; i++) {
  console.log(`${i}: ${isIt67(i)}`);
}
// Output:
// 66: false
// 67: true
// 68: false
// Explanation: Only one winner. The others? Simply losers.

// Example 10: The NaN nightmare
console.log(isIt67(NaN));
// Output: false
// Explanation: "Not a Number" is indeed not 67. We agree on something.
```

### Edge Cases

```javascript
// Scientific notation? No.
console.log(isIt67(6.7e1));   // false (it's 67 but written weird)
console.log(isIt67(0x43));    // false (hex for 67)
console.log(isIt67(0b1000011)); // false (binary for 67)

// Only primitive number 67 passes. No exceptions.
```

## How It Works (Or Doesn't)

Internally, this library:

1. Encrypts your number using a Fibonacci cipher
2. Rotates it through hyperbolic space 13 times
3. Runs it through a Mandelbrot transformation
4. Checks Goldbach's conjecture on the result
5. Applies quantum entanglement simulation
6. Performs recursive chaos encoding
7. Validates palindromes recursively
8. Questions its own sanity
9. Returns `true` if you gave it `67`

Everything else gets `false`.

## Performance

Each call takes approximately 42ms and consumes 6.7KB of memory.

For comparison, `number === 67` takes 0.0000001ms.

Choose wisely.

## Tests

```javascript
// The entire test suite
console.assert(isIt67(67) === true, "Test failed: 67 should be true");
console.assert(isIt67(66) === false, "Test failed: 66 should be false");
console.assert(isIt67("67") === false, "Test failed: '67' should be false");
console.log("All tests pass. Somehow.");
```

## FAQ

**Q: Does it work with 67?**
A: Yes.

**Q: Does it work with 67.0?**
A: Also yes. But only if you pass it as a number.

**Q: Why is it so slow?**
A: It's not slow. It's *dramatic*.

**Q: Can I use this in production?**
A: You can. But your coworkers will ask questions.

**Q: What questions?**
A: "Why?" and "Are you okay?" mostly.
---
