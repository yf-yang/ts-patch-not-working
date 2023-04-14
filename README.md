# Package Management Tool

- pnpm

# To Reproduce

```
pnpm i
pnpm ts-patch install
pnpm tspc
```

# The Problem
In generated `build/file1.d.ts`, import path is not transformed (still `@/file2`)