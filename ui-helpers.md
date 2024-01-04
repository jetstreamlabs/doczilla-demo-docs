---
title: UI Helpers & Examples
description: Learn about all the features and get some examples of styles and components in Doczilla.
tags:
  - UI
  - examples,
  - Doczilla
---

[[toc]]

## Learn How to Decorate Your Docz {.doc-heading}

We've added a bunch of great extensions by default to allow you to create beautiful documentation right out of the box.

### Code Groups {.doc-heading}

For those who need to display clode blocks in different programming languages you can use the CodeGroup Container extension to easily create multiple language variations.

Generate these like so:

````md
:::: code-group#example
@tab:active js#javascript

```js
/**
 * @type {import('vitepress').UserConfig}
 */
const config = {
  // ...
};

export default config;
```

@tab ts#typescript

```ts
import type { UserConfig } from 'vitepress';

const config: UserConfig = {
  // ...
};

export default config;
```

::::
````

This will produce the below Code Group container.

:::: code-group#example
@tab:active js#javascript

```js
/**
 * @type {import('vitepress').UserConfig}
 */
const config = {
  // ...
};

export default config;
```

@tab ts#typescript

```ts
import type { UserConfig } from 'vitepress';

const config: UserConfig = {
  // ...
};

export default config;
```

::::

### Stateful Containers {.doc-heading}

Use these colorful containers to generate stateful messages for your users anytime you need to draw attention to a specific area of your docz.

These are super simple to make in markdown, just use the `:::` opening and closing tags, followed by a style and an optional title.

```md
::: info another title
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
:::
```

::: info another title
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
:::

::: note
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
:::

:::
Offendit eleifend moderatius ex vix, quem odio mazim et qui, purto expetendis cotidieque quo cu, veri persius vituperata ei nec. Et mazim recteque nam.
:::

::: warning
Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Vivendum intellegat et qui, ei denique consequuntur vix.
:::

::: tip
Offendit eleifend moderatius ex vix, quem odio mazim et qui, purto expetendis cotidieque quo cu, veri persius vituperata ei nec. Et mazim recteque nam.
:::

::: danger
Scripta periculis ei eam, te pro movet reformidans. Scripta periculis ei eam, te pro movet reformidans. Qui gloriatur scribentur et, id velit verear mel, cum no porro debet.
:::

::: abstract requirements

- Endpoint: `/api/2.1/details/{id}`
- Method: `GET`
- Params:
  - Allowed: `record id in endpoint url`
  - Required: `record id in endpoint url`

:::

Dicit dicant quaestio pri eu, no principes persecuti liberavisse sit. Sonet tibique sea et. Pri posse graeco definitiones cu, id eam populo quaestio adipiscing, usu quod malorum te. Vivendum intellegat et qui, ei denique consequuntur vix. Scripta periculis ei eam, te pro movet reformidans. Scripta periculis ei eam, te pro movet reformidans. Offendit eleifend moderatius ex vix, quem odio mazim et qui, purto expetendis cotidieque quo cu, veri persius vituperata ei nec.
