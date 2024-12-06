# eslint-config-ezze-prettier

[ESLint](http://eslint.org/) configuration for [Prettier](https://prettier.io/).

## Installation

```
pnpm add eslint@^9.16.0 eslint-config-prettier@^9.1.0 eslint-plugin-prettier@^5.2.1 prettier@^3.4.2 -D
```

## Usage

Create `eslint.config.js` file in your project and place the following there:

```typescript
import ezzePrettier from 'eslint-config-ezze-prettier';

export default [
  ...ezzePrettier
];
```

[Here](https://github.com/ezze/prettier-config-ezze) is the recommended configuration. It can be referred from project's `package.json`:

```json
{
  "prettier": "prettier-config-ezze"
}
```

See [Shareable configs](https://eslint.org/docs/latest/extend/shareable-configs) for more details.

## License

[MIT](LICENSE.md)
