# Shared syncpack configuration

The purpose of the [syncpack](https://www.npmjs.com/package/syncpack) is formatting package json and validating dependencies versions.

---

## Contents

- [Setup](#setup)
- [Usage](#usage)
- [Donation](#donation)
- [License](#license)

## Setup

- Add workspace reference to `@flixlix/config-syncpack` and its peer dependencies:

  ```sh
  pnpm add -w @flixlix/config-syncpack syncpack
  ```

- Add syncpack configuration file:

  ```js
  // .syncpackrc.js

  module.exports = require('@flixlix/config-syncpack');
  ```

- Add syncpack scripts:

  ```jsonc
  // package.json

  "scripts": {
    ...
    "syncpack:fix": "syncpack format && syncpack fix-mismatches"
    ...
  }
  ```

## Usage

- Manual usage from command line:

  ```sh
  pnpm format:check .
  pnpm format:fix .
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
