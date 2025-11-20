# `recheck-scalajs`

> [!NOTE]
>
> This is a custom distribution containing the scalajs build output of [`recheck`](https://github.com/makenowjust-labs/recheck/tree/main/packages/recheck) to enable consumers to build against an ESM build. See https://github.com/makenowjust-labs/recheck/issues/1619 for more info. When an ESM build is available in `recheck`, this repo/package will be archived.

## API

This distribution provides the following API:

```ts
// esm-recheck provides the original API
import { check } from '@regex-radar/recheck-scalajs';

// NOTE: this is the sync function, and can be computationally heavy and thus block any UI running on the same thread.
const result = check('a|ab+', 'g');
```

## Build

This repository/package is a distribution of the build output of `recheck`s compilation with scalajs as its target. similar to the native and jar build targets of `recheck`.

## `recheck`

For more information about `recheck` see:

-   [the official documentation](https://makenowjust-labs.github.io/recheck/docs/usage/as-javascript-library)
-   [the GitHub repository](https://github.com/makenowjust-labs/recheck)
