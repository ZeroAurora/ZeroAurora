# Random Ideas

## unpm - Deno doesn't need a package manager

- `import bar from "https://example.com/github.com/foo/bar"`
- the server takes a git clone of `github.com/foo/bar` and find `mod.[ts,js]` in its main branch
- then, have it bundled with rollup and esbuild.
  - see https://github.com/rollup/rollup https://github.com/egoist/rollup-plugin-esbuild https://github.com/Swatinem/rollup-plugin-dts
- serve it
