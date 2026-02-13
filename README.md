# Vue 3 + TypeScript + Vite

This template should help get you started developing with Vue 3 and TypeScript in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

Learn more about the recommended Project Setup and IDE Support in the [Vue Docs TypeScript Guide](https://vuejs.org/guide/typescript/overview.html#project-setup).

## dev

```bash
pnpm run dev
```

## build

```bash
pnpm run build
```

## ESLint
use [antfu/eslint-config](https://github.com/antfu/eslint-config)

## lint the code in project

```bash
pnpm run lint:fix
```

## view what rules are enabled

```bash
npx @eslint/config-inspector
```

## Lint Staged

If you want to apply lint and auto-fix before every commit, this template use [lint-staged](https://github.com/lint-staged/lint-staged) and [simple-git-hooks](https://github.com/toplenboren/simple-git-hooks) (they are already in the `package.json`).

Run the CLI script to update the git hooks with the commands from the config:

```bash
npx simple-git-hooks
```
