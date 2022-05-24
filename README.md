## hello-world

- npm
- can use transitive dependencies

## hello-world-pnpm

- uses pnpm
- links in `node_modules`
- `node_modules` not flat, but hierarchical
- can not use transitive deps

## hello-world-yarn

- classic yarn
- flat `node_modules`
- can use transitive dependencies

## hello-world-yarn-berry-node-linker

- yarn 2 ("berry")
- zero-install (`.cache` in git)
- with `node_modules` folder `linker` in `.yarnrc.yml`
- can use transitive deps

## hello-world-yarn-berry-pnp

- yarn 2 ("berry") with pnp and zero-install
- no `node_modules` at all!
- Node must be started via `scripts` in `package.json`
- Tools (IDE, TS, ...) must support pnp
- can not use transitive dependencies
