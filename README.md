[@zokugun/namegen-lite](https://github.com/zokugun/node-namegen-lite)
=====================================================================

[![License: MIT](https://img.shields.io/badge/license-MIT-blue)](./LICENSE)
[![NPM Version](https://img.shields.io/npm/v/@zokugun/namegen-lite?color=brightgreen)](https://www.npmjs.com/package/@zokugun/namegen-lite)
[![NodeJS Version](https://img.shields.io/badge/node.js-%3E%3D%2018.20-green)](#requirements)
[![Modules](https://img.shields.io/badge/modules-ESM%20%7C%20CJS-green)](#requirements)
[![Ko-fi](https://img.shields.io/badge/Ko--fi-f87171?logo=kofi&logoColor=white)](https://ko-fi.com/daiyam)
[![Liberapay](https://img.shields.io/badge/Liberapay-facc15?logo=liberapay&logoColor=black)](https://liberapay.com/daiyam/donate)
[![PayPal](https://img.shields.io/badge/PayPal-5277C3?logo=paypal&logoColor=white)](https://paypal.me/daiyam99)

> This utility creates randomized names using internal word lists, producing results like `misty-river-452` for clear labeling.

About this project
------------------

`@zokugun/namegen-lite` is a TypeScript-first port and fork of [`wwwy3y3/haiku`](https://github.com/wwwy3y3/haiku).

Features
--------

- **Standardized Format**: Outputs names in an adjective-noun-number pattern.
- **Lightweight Design**: Focuses on core functionality with minimal overhead.
- **Descriptive Labels**: Creates names that are easy for humans to read and recognize.
- **Unique Identifiers**: Uses numeric suffixes to help prevent name collisions.

Installation
------------

```bash
npm add @zokugun/namegen-lite
```

Requirements
------------

- **Node.js**: `v18.20` or higher
- **Modules**: ECMAScript Modules (`ESM`) or CommonJS (`CJS`)

Quick Start
-----------

### Basic Usage

Generate a single unique string to use as an ID or a temporary filename.

```typescript
import { namegen } from 'node-namegen-lite';

const id = namegen();

console.log(id);
// 'damp-snowflake-491'
```

API Reference
-------------

```typescript
function namegen(): string;
```

Contributions
-------------

Contributions are most welcome. Please:

- Open issues and feature requests under the repository discussions.
- Follow the [`CONTRIBUTING.md`](./CONTRIBUTING.md).

Donations
---------

Support this project by becoming a financial contributor.

<table>
   <tr>
      <td><img src="https://raw.githubusercontent.com/daiyam/assets/master/icons/256/funding_kofi.png" alt="Ko-fi" width="80px" height="80px"></td>
      <td><a href="https://ko-fi.com/daiyam" target="_blank">ko-fi.com/daiyam</a></td>
   </tr>
   <tr>
      <td><img src="https://raw.githubusercontent.com/daiyam/assets/master/icons/256/funding_liberapay.png" alt="Liberapay" width="80px" height="80px"></td>
      <td><a href="https://liberapay.com/daiyam/donate" target="_blank">liberapay.com/daiyam/donate</a></td>
   </tr>
   <tr>
      <td><img src="https://raw.githubusercontent.com/daiyam/assets/master/icons/256/funding_paypal.png" alt="PayPal" width="80px" height="80px"></td>
      <td><a href="https://paypal.me/daiyam99" target="_blank">paypal.me/daiyam99</a></td>
   </tr>
</table>

License
-------

Copyright &copy; 2026-present Baptiste Augrain

Licensed under the [MIT license](https://opensource.org/licenses/MIT).
