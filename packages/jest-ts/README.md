# Shared jest configuration

The purpose of the [jest](https://jestjs.io/) is to test `javascript`.

> This configuration targets **lib typescript** packages.

---

## Contents

- [Setup](#setup)
- [Donation](#donation)
- [License](#license)

## Setup

- Add workspace reference to `@flixlix/config-jest-ts` and its peers dependencies:

  ```sh
  pnpm add -w @flixlix/config-jest-ts jest ts-jest @types/jest
  ```

- Add jest configuration file

  ```js
  // packages/baz/jest.config.js

  module.exports = require('@flixlix/config-jest-ts');
  ```

## Donation

If you found this project helpful, consider\
[**buying me a coffee**](https://www.buymeacoffee.com/flixlix), [**donate by paypal**](https://www.paypal.me/flixlix) or just [**leave a star**](../../../..)⭐\
Thanks for your support, it is much appreciated!

## License

[MIT](LICENSE) © [Luca Félix](https://github.com/flixlix)

---

[⬅ Back](../../README.md)

---
