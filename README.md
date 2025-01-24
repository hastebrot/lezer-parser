# lezer-parser

**development:**

- `❯ bun build sources/lezer-common/src/index.ts --outfile dist/lezer-common.js --minify --packages=external`
- `❯ bun build sources/lezer-generator/src/index.ts --outfile dist/lezer-generator.js --minify --packages=external`
- `❯ bun build sources/lezer-lr/src/index.ts --outfile dist/lezer-lr.js --minify --packages=external`
- `❯ brotli dist/*.js --force`

```shell
❯ brew install eza
❯ eza --long --bytes --time-style=long-iso --no-user dist/
.rw-r--r--@ 27,490 2025-01-24 11:59 lezer-common.js
.rw-r--r--@  8,746 2025-01-24 11:59 lezer-common.js.br
.rw-r--r--@ 78,858 2025-01-24 12:00 lezer-generator.js
.rw-r--r--@ 23,254 2025-01-24 12:00 lezer-generator.js.br
.rw-r--r--@ 27,110 2025-01-24 12:00 lezer-lr.js
.rw-r--r--@  8,346 2025-01-24 12:00 lezer-lr.js.br
```

**references:**

- https://lezer.codemirror.net/
- https://lezer.codemirror.net/docs/guide/
- https://github.com/lezer-parser
- https://unpkg.com/browse/@lezer/common@1.2.3/
- https://unpkg.com/browse/@lezer/generator@1.7.2/
- https://unpkg.com/browse/@lezer/lr@1.4.2/
