# @brang/mega-math

A simple and powerful library for performing basic mathematical operations.

---

## Features
- Addition, subtraction, multiplication, and division functions.
- Lightweight and easy to use.
- Written in TypeScript for type safety.

---

## Installation

You can install the package via npm or yarn:

### Using npm
```bash
npm install @brang/mega-math
```

### Using yarn
```bash
yarn add @brang/mega-math
```

---

## Usage

Here’s how to use the library:

### Importing the functions
```typescript
import { add, subtract, multiply, divide } from "@brang/mega-math";

// Perform addition
const sum = add(5, 10); // 15

// Perform subtraction
const difference = subtract(10, 5); // 5

// Perform multiplication
const product = multiply(5, 10); // 50

// Perform division
const quotient = divide(10, 5); // 2
```

### TypeScript Support
Since the package is written in TypeScript, it includes type definitions for all the functions:

```typescript
import { add } from "@brang/mega-math";

const sum: number = add(5, 10); // Works perfectly with TypeScript!
```

---

## API Reference

### `add(a: number, b: number): number`
Adds two numbers.

### `subtract(a: number, b: number): number`
Subtracts the second number from the first.

### `multiply(a: number, b: number): number`
Multiplies two numbers.

### `divide(a: number, b: number): number`
Divides the first number by the second. Throws an error if the divisor is `0`.

---

## Contributing

We welcome contributions! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

