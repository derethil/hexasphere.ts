# hexasphere

A TypeScript port of [Hexasphere.js](https://github.com/arscan/hexasphere.js) -
a JavaScript library for generating hexagonal sphere subdivisions (geodesic
polyhedron).

## Installation

```bash
npm install hexasphere
```

## Usage

This library provides the same API as the original hexasphere.js but with full
TypeScript support:

```typescript
import { Hexasphere } from "hexasphere";

const sphere = new Hexasphere(radius, subdivisions, hexSize);
```

For detailed usage instructions, examples, and API documentation, please refer
to the
[original hexasphere.js repository](https://github.com/arscan/hexasphere.js).

## TypeScript Support

This package includes TypeScript definitions and is built with modern ES2020
target for optimal compatibility.

## License

MIT License - see [LICENSE](LICENSE) file for details.

Original hexasphere.js: Copyright (c) 2014-2017 Robert Scanlon\
TypeScript port: Copyright (c) 2025 Jaren Glenn
