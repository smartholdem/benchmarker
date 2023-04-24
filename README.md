# benchmarker

This package provides a wrapper around Benchmark.js with sane defaults and formatting.

## Installation

```bash
yarn add @smartholdem/benchmarker --dev
```

## Usage

```ts
import { benchmarker } from "@smartholdem/benchmarker";

benchmarker("utils", [
	{
		name: "map",
		scenarios: require("./map"),
	},
	{
		name: "filter",
		scenarios: require("./filter"),
	},
	{
		name: "reduce",
		scenarios: require("./reduce"),
	},
]);
```

## Testing

```bash
yarn test
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## License

Benchmarker is an open-sourced software licensed under the [MIT](LICENSE.md).
