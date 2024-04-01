<h1 align="center">eslint-preset-prettier</h1>

<p align="center">The easiest way to use Prettier for linting. Which is what you should do. 🧹</p>

<p align="center">
	<a href="https://github.com/JoshuaKGoldberg/eslint-preset-prettier/blob/main/.github/CODE_OF_CONDUCT.md" target="_blank"><img alt="🤝 Code of Conduct: Kept" src="https://img.shields.io/badge/%F0%9F%A4%9D_code_of_conduct-kept-21bb42" /></a>
	<a href="https://github.com/JoshuaKGoldberg/eslint-preset-prettier/blob/main/LICENSE.md" target="_blank"><img alt="📝 License: MIT" src="https://img.shields.io/badge/%F0%9F%93%9D_license-MIT-21bb42.svg"></a>
	<a href="http://npmjs.com/package/eslint-preset-prettier"><img alt="📦 npm version" src="https://img.shields.io/npm/v/eslint-preset-prettier?color=21bb42&label=%F0%9F%93%A6%20npm" /></a>
	<img alt="💪 TypeScript: Strict" src="https://img.shields.io/badge/%F0%9F%92%AA_typescript-strict-21bb42.svg" />
</p>

<p align="center">
	<em>
		🧹 See <a href="https://github.com/typescript-eslint/typescript-eslint/issues/8814">typescript-eslint##8814 Docs: Prioritize formatting rules over other, less-important ones in docs</a> for more information. 🧹
	</em>
</p>

## Usage

First install this development utility as a production dependency:

```shell
npm i eslint-preset-prettier
```

Then, replace the contents of your ESLint configuration file with:

```ts
import { config } from "eslint-preset-prettier";

export default config();
```

<!-- You can remove this notice if you don't want it 🙂 no worries! -->

> 💙 This package was templated with [`create-typescript-app`](https://github.com/JoshuaKGoldberg/create-typescript-app).
