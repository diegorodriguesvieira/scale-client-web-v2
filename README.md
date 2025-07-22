This project uses:

- **React 19**
- **Vite 7**
- **TypeScript**
- **ESLint with type-aware rules**
- **Prettier formatting**

## Getting Started

```bash
npm install
npm start
```

## Linting & Formatting

- Run linter:
  ```bash
  npm lint
  ```
- Format code with Prettier:
  ```bash
  npm format
  ```

Lint is configured with:

- `@eslint/js`
- `typescript-eslint`
- `eslint-plugin-react-hooks`
- `eslint-plugin-react-refresh`
- `eslint-plugin-prettier` + `eslint-config-prettier`

Prettier rules:

```json
{
  "semi": true,
  "singleQuote": true,
  "printWidth": 100,
  "trailingComma": "all",
  "arrowParens": "avoid"
}
```

## TypeScript

Project uses two separate configs:

- `tsconfig.app.json` for the app (`src/`)
- `tsconfig.node.json` for config files like `vite.config.ts`
