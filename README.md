# pnpm-starter

A pnpm monorepo starter template with TypeScript, Biome, Turbo, and tsup.

## Use as Template

```sh
git clone https://github.com/shellicar/pnpm-starter.git my-project
cd my-project
rm -rf .git
git init
pnpm install
```

## Structure

- `packages/` — publishable packages
- `examples/` — example usage

## Scripts

| Command | Description |
|---|---|
| `pnpm build` | Build all packages |
| `pnpm dev` | Watch mode |
| `pnpm test` | Run tests |
| `pnpm type-check` | TypeScript type checking |
| `pnpm check` | Biome check (lint + format) |
| `pnpm ci` | Biome CI mode |
| `pnpm list-mismatches` | Syncpack version check |
| `pnpm updates` | Check for dependency updates |

## Customisation

After cloning:

1. Update `package.json` name fields
2. Update `.packagename` with your package directory name
3. Update `CHANGELOG.md` repository links
4. Update `packages/example/package.json` repository URLs
