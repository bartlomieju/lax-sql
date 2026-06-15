# lax-sql

Dialect-agnostic SQL formatter. Usable as a Rust library or as a dprint plugin.

> **Source of truth: the [`lax`](https://github.com/bartlomieju/lax) monorepo
> (`crates/lax-sql`).** This repository only hosts the published dprint Wasm
> plugin releases; it carries no source of its own.

## Use as a dprint plugin

```jsonc
// dprint.json
{
  "plugins": ["https://plugins.dprint.dev/bartlomieju/lax-sql-0.2.1.wasm"]
}
```

Or run `dprint config add bartlomieju/lax-sql` to pull in the latest version.
