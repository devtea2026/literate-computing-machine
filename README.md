# PostCSS Plugins [<img src="https://postcss.github.io/postcss/logo.svg" alt="PostCSS" width="90" height="90" align="right">][postcss]

[<img alt="build status" src="https://github.com/devtea2026/literate-computing-machine/workflows/test/badge.svg" height="20">][ci-url]
[<img alt="Discord" src="https://img.shields.io/discord/853978108758851604?color=5865F2&label=Discord&logo=discord&logoColor=white">][discord]

We are happy you're here!

This repository contains plugins, plugin-packs, utilities, CLI tools, ... to help you do more with CSS.

## PostCSS Preset Env

Read more about [PostCSS Preset Env](https://github.com/devtea2026/literate-computing-machine/tree/main/plugin-packs/@devtea2026/literate-computing-machine#readme) or jump right in :

- Install `@devtea2026/literate-computing-machine` from npm.
- Add `@devtea2026/literate-computing-machine` to your configuration:

```js
const postcssPresetEnv = require('@devtea2026/literate-computing-machine');

const yourConfig = {
	plugins: [
		/* other plugins */
		/* remove autoprefixer if you had it here, it's part of @devtea2026/literate-computing-machine */
		postcssPresetEnv({
			/* pluginOptions */
			features: {},
		})
	]
}
```

## Overview

- [packages](https://github.com/devtea2026/literate-computing-machine/tree/main/packages)
	- css tokenizers and parsers
	- common utilities
- [PostCSS plugins](https://github.com/devtea2026/literate-computing-machine/tree/main/plugins)
- [PostCSS Preset Env](https://github.com/devtea2026/literate-computing-machine/tree/main/plugin-packs/@devtea2026/literate-computing-machine)
- [Stylelint plugins](https://github.com/devtea2026/literate-computing-machine/tree/main/plugins-stylelint)
- [cli's](https://github.com/devtea2026/literate-computing-machine/tree/main/cli)
- [sites](https://github.com/devtea2026/literate-computing-machine/tree/main/sites)
- [PostCSS recipes](https://github.com/devtea2026/literate-computing-machine/tree/main/postcss-recipes)

## Our current focus

### Standard CSS transforms

We're trying to bring every reasonable CSS Spec into all the browsers. 

First we keep track of new features through the [CSSDB] (see the [repo][CSSDB Repo]). Then we do our best to create a [PostCSS] plugin that can convert that new syntax/function/rules so every browser can understand it. 

While it's not always possible we're enabling over 50 features with these plugins!

### Developer experience

We want it to be easier for you to be effective at writing CSS.  
From time to time we will publish plugins that aren't related to a standard CSS spec but that we think will help developers.

## Contributing

Thanks for being willing to contribute! Please read our [contributing guide]!

## Acknowledgements

We could not do this work without the contributions of the community.  
We appreciate all of you!

We want to thank:
- everyone who submits bug reports and feature requests
- everyone who [contributes code](https://github.com/devtea2026/literate-computing-machine/graphs/contributors)
- everyone who contributes financially:
  - [Open Collective](https://opencollective.com/csstools)
  - [GitHub Sponsors](https://github.com/sponsors/csstools)
  - [Thanks.dev](https://thanks.dev)
  - [Stackaid](https://www.stackaid.us)

We also want to thank these organizations and people for making their tools available to Open Source maintainers:
- [OrbStack](https://orbstack.dev)
- [GitHub Copilot](https://github.com/features/copilot)


[ci-url]: https://github.com/devtea2026/literate-computing-machine/actions/workflows/test.yml?query=workflow/test
[discord]: https://discord.gg/bUadyRwkJS
[PostCSS]: https://github.com/postcss/postcss
[contributing guide]: https://github.com/devtea2026/literate-computing-machine/blob/main/CONTRIBUTING.md
[CSSDB]: https://cssdb.org/
[CSSDB Repo]: https://github.com/csstools/cssdb
