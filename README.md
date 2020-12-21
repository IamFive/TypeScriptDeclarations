# Dota 2 TypeScript declarations

TypeScript declarations for Dota 2 Custom Game
[Lua](https://github.com/ModDota/TypeScriptDeclarations/tree/master/packages/dota-lua-types) and
[Panorama](https://github.com/ModDota/TypeScriptDeclarations/tree/master/packages/panorama-types)
API, generated from [dota-data](https://github.com/ark120202/dota-data) dumps.

Check out our [addon template](https://github.com/ModDota/TypeScriptAddonTemplate) for usage
examples.

### Updating after a DOTA2 update

1. Update https://github.com/ModDota/dota-data and publish a new package version
2. Update the `@moddota/dota-data` package version in `package.json`
3. `yarn install`
4. `yarn build`
5. Commit
6. TODO how to publish type packages
