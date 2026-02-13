# [@notos9312/vue3-ts-template](https://github.com/notos9312/vue3-ts-template)

- Base on the [Vite](https://vite.dev/) officially recommended `vue-ts` template
- Use [Vue-Router](https://github.com/vuejs/router) as the Router for [Vue](https://github.com/vuejs/core)
- Use [Pinia](https://github.com/vuejs/pinia) as the Store for [Vue](https://github.com/vuejs/core)
- Use [@antfu/eslint-config](https://github.com/antfu/eslint-config) as Linter and Formatter
- Use [lint-staged](https://github.com/lint-staged/lint-staged) and [simple-git-hooks](https://github.com/toplenboren/simple-git-hooks) as CLI

## Dev

```bash
pnpm run dev
```

## Build

```bash
pnpm run build
```

## ESLint

use [antfu/eslint-config](https://github.com/antfu/eslint-config)

## Lint the code in project

```bash
pnpm run lint:fix
```

## View what rules are enabled

```bash
npx @eslint/config-inspector
```

## Lint Staged

If you want to apply lint and auto-fix before every commit, this template use [lint-staged](https://github.com/lint-staged/lint-staged) and [simple-git-hooks](https://github.com/toplenboren/simple-git-hooks) (they are already in the `package.json`).

Run the CLI script to update the git hooks with the commands from the config:

```bash
npx simple-git-hooks
```
