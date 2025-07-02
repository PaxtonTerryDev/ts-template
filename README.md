# TS Template

A very basic typescript template with a very standard setup.

## Overview

I made this for my own development uses, but you are free to use it as well. It comes setup with some pretty basic tsconfig options - things like path resolution / aliasing (using the `"@/*"` alias), `dist/` output directory and `src/` root directory.

## Getting Started

Just run:

```bash
npm i
```

Then you can just run:

```bash
npm run dev
```

to get started. It will compile your code and watch for changes, then use `tsx` to execute the `src/index.ts` file.
