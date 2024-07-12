# test-sveltekit-storybook

Created with

```bash
pnpm dlx create-turbo@latest -e with-svelte test-sveltekit-storybook # choose pnpm
```

> Manually added a `.gitignore` file too.

## Reproduce error

```bash
cd test-sveltekit-storybook/packages/ui
pnpm dlx storybook init  # choose Vite
```

The error output produced can be seen [here](./storybook-init-error.txt)

## Stack

- `pnpm -v` : `9.4.0`
- `node -v` : `v20.14.0`