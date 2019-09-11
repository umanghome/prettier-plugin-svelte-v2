# Prettier for Svelte v2 (strictly v2) components

Format your svelte components using prettier.

## Why the Fork

This repo is forked from [UnwrittenFun/prettier-plugin-svelte](https://github.com/UnwrittenFun/prettier-plugin-svelte). The point in the original repo where v2 support was dropped has bugs which were fixed _after_ the support was dropped, so there doesn't exist any prettier plugin to properly format Svelte v2 code at the time of this writing.

## Features

-   Format your html, css, and javascript using prettier
-   Format Svelte syntax, e.g. each loops, if statements, await blocks, etc.
-   Format the javascript expressions embedded in the svelte syntax
    -   e.g. expressions inside of `{}`, event bindings `on:click=""`, and more
-   Supports Svelte v2 and v3

## How to use

Install prettier-plugin-svelte as a dev dependency in your project.

Then format your code using prettier cli. You may need to add `--plugin-search-dir=.`

```
prettier --write --plugin-search-dir=. ./**/*.html
```
