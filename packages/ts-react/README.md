# Shared typescript configuration

The purpose of the [typescript](https://www.typescriptlang.org/) is to add strong typing to `javascript`.

> This configuration targets **lib react** packages.

---

## Contents

- [Setup](#setup)
- [Donation](#donation)
- [License](#license)

## Setup

- Add workspace reference to `@flixlix/config-ts-react` and its peers dependencies:

  ```sh
  pnpm add -w @flixlix/config-ts-react typescript react react-dom @types/node @types/react @types/react-dom
  ```

- Add typescript configuration file

  ```jsonc
  // packages/bar/tsconfig.json

  {
    "extends": "@flixlix/config-ts-react",
    "compilerOptions": {
      "baseUrl": "src",
      "rootDir": "src"
    },
    "include": ["src"]
  }
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
