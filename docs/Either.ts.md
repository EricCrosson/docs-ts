---
title: Either.ts
nav_order: 3
---

# \_right

**Signature** (function)

```ts
export const _right = <L, A>(): Prism<Either<L, A>, A> => ...
```

# \_left

**Signature** (function)

```ts
export const _left = <L, A>(): Prism<Either<L, A>, L> => ...
```