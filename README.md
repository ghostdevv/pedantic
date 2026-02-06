# @rlly/pedantic

```bash
pnpm add -D -w @rlly/pedantic oxlint
# optionally install
pnpm add -D -w oxlint-tsgolint @e18e/eslint-plugin
```

```json
{
	"$schema": "./node_modules/oxlint/configuration_schema.json",
	"extends": [
		"./node_modules/@rlly/pedantic/oxlint/core.json", // <-- always recommended
		"./node_modules/@rlly/pedantic/oxlint/e18e.json",
		"./node_modules/@rlly/pedantic/oxlint/type-aware.json",
		"./node_modules/@rlly/pedantic/oxlint/vitest.json",
		"./node_modules/@rlly/pedantic/oxlint/library.json"
	]
}
```
