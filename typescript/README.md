# isIt67.ts

## The TypeScript Library That Questions Reality

### Installation

It's just one file

### Import

```typescript
import isIt67 from './is-it-67.ts';
```

### API Reference

#### `isIt67(value: unknown): boolean`

Synchronous validation. Returns `true` only for the number `67`.

```typescript
console.log(isIt67(67));   // true
console.log(isIt67(42));   // false
console.log(isIt67("67")); // false
console.log(isIt67([67])); // false
```

#### `isIt67.async(value: unknown): Promise<boolean>`

Asynchronous validation with quantum entanglement simulation.

```typescript
const result = await isIt67.async(67);
console.log(result); // true
```

#### `isIt67.withConfidence(value: unknown): Promise<{ result: boolean; confidence: number }>`

Returns both the result and a confidence percentage.

```typescript
const { result, confidence } = await isIt67.withConfidence(67);
console.log(result);      // true
console.log(confidence);  // 99.9999997
```

#### `isIt67.debug(value: unknown): Promise<ValidationResult>`

Full debug information including quantum decoherence metrics.

```typescript
const debug = await isIt67.debug(67);
console.log(debug.isValid);           // true
console.log(debug.confidence);        // 99.9999997
console.log(debug.quantumDecoherence); // 0.0000003
```

### Usage Examples

#### Basic TypeScript with Type Safety

```typescript
import isIt67 from './isIt67';

const secretCode: unknown = 67;

if (isIt67(secretCode)) {
  console.log("Access granted to the 67 dimension");
} else {
  console.log("Access denied. You are not 67.");
}
```

#### Async/Await Pattern

```typescript
import isIt67 from './isIt67';

async function validateTheMeaningOfLife() {
  const numbers = [66, 67, 68];
  
  for (const num of numbers) {
    const isValid = await isIt67.async(num);
    console.log(`${num} is 67: ${isValid}`);
  }
}

validateTheMeaningOfLife();
// Output:
// 66 is 67: false
// 67 is 67: true
// 68 is 67: false
```

#### With Confidence Scoring

```typescript
import isIt67 from './isIt67';

async function nuclearLaunchCode(code: number) {
  const { result, confidence } = await isIt67.withConfidence(code);
  
  if (result && confidence > 99.9) {
    console.log("Code verified. Launch sequence initiated.");
  } else if (result) {
    console.log("Quantum decoherence detected. Manual override required.");
  } else {
    console.log("Invalid code. Aborting.");
  }
}

await nuclearLaunchCode(67);
```

#### Examples & Outputs

```typescript
import isIt67 from './isIt67';

// Example 1: The imposter strikes again
console.log(isIt67("67"));
// Output: false
// TypeScript knows this is a string. The library knows. Why don't you?

// Example 2: Floating point existential crisis
console.log(isIt67(67.0000000000001));
// Output: false
// "Close enough" is not a mathematical proof.

// Example 3: The off-by-one family reunion
for (let i = 65; i <= 69; i++) {
  console.log(`${i}: ${isIt67(i)}`);
}
// Output:
// 65: false
// 66: false
// 67: true
// 68: false
// 69: false
// Explanation: Only one child is loved equally.

// Example 4: Array abuse (TypeScript can't save you)
console.log(isIt67([67]));
// Output: false
// TypeScript: "This is an array"
// You: "But it contains 67"
// Library: "I said NO"

// Example 5: Object delusion
console.log(isIt67({ value: 67, isSixtySeven: true }));
// Output: false
// TypeScript: "This is an object with properties"
// Library: "I don't read resumes"

// Example 6: The null pointer paradox
console.log(isIt67(null));
// Output: false
// Explanation: null is the absence of value. 67 is a value. Different things.

// Example 7: Undefined behavior
console.log(isIt67(undefined));
// Output: false
// TypeScript: "This is undefined"
// Library: "So is your purpose for using this library"

// Example 8: NaN escaping the asylum
console.log(isIt67(NaN));
// Output: false
// Explanation: Not a Number is indeed not 67. Finally, we agree.

// Example 9: Boolean identity crisis
console.log(isIt67(true));
console.log(isIt67(false));
// Output: false
// Output: false
// Explanation: true + false = 1, not 67. Math is hard.

// Example 10: Async chaos
const results = await Promise.all([
  isIt67.async(66),
  isIt67.async(67),
  isIt67.async(68)
]);
console.log(results);
// Output: [false, true, false]
// Explanation: Even quantum mechanics agrees that 67 is special.
```

### Type Definitions

```typescript
// If you need the types separately
import type { ValidationResult } from 'is-it-67-ts';

const debugInfo: ValidationResult = {
  isValid: true,
  confidence: 99.9999997,
  quantumDecoherence: 0.0000003
};
```

### Why TypeScript?

Because even with all this complexity, type safety matters.

```typescript
// This won't compile. TypeScript saves you from yourself.
// isIt67(67).map(x => x * 2); // Error: boolean has no map method

// This is fine
const result = isIt67(67);
if (result === true) {
  console.log("It's 67. TypeScript confirmed it.");
}
```

### Performance Notes

- Synchronous: ~42ms per call
- Async: ~67ms per call (quantum entanglement takes time)
- Memory usage: 6.7MB after 1000 calls (cached for quantum coherence)

### FAQ

**Q: Does TypeScript infer that 67 is 67?**
A: Yes. TypeScript knows 67 === 67. The library is for dramatic effect.

**Q: Can I use this with React?**
A: You can. Your components will re-render 67 times per second.

**Q: What about Deno?**
A: Deno supports TypeScript natively. The chaos is cross-platform.

**Q: Will this help me pass a code review?**
A: Your reviewers will have questions. Many questions.

### Contributing

Please do

---
