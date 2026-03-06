# [@notos9312/vue3-ts-template](https://github.com/notos9312/vue3-ts-template)

- Base on the **[Vite](https://vite.dev/)** officially recommended `vue-ts` template
- Use **[Vue-Router](https://github.com/vuejs/router)** as the Router for **[Vue](https://github.com/vuejs/core)**
- Use **[Pinia](https://github.com/vuejs/pinia)** as the Store for **[Vue](https://github.com/vuejs/core)**
- Use **[@antfu/eslint-config](https://github.com/antfu/eslint-config)** as Linter and Formatter
- Use **[husky](https://github.com/typicode/husky)** and **[commitlint](https://github.com/conventional-changelog/commitlint)** as CLI

## Dev

```bash
pnpm run dev
```

## Build

```bash
pnpm run build
```

## ESLint

use **[@antfu/eslint-config](https://github.com/antfu/eslint-config)**

## Lint the code in project

```bash
pnpm run lint:fix
```

## View what rules are enabled

```bash
npx @eslint/config-inspector
```

## Commitlint hint

```bash
feat:     新功能
fix:      修复 bug
docs:     文档修改
style:    代码格式修改（不影响逻辑）
refactor: 代码重构
test:     测试相关
chore:    构建/工具/依赖更新
```

## Style

Recommend **[UnoCSS](https://github.com/unocss/unocss)** or **[tailwindcss](https://github.com/tailwindlabs/tailwindcss)**
