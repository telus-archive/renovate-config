# Renovate Config

[![version][npm-image]][npm-url] [![Build Status][circle-image]][circle-url]

> TELUS preset configs for [Renovate][].

Renovate helps us to keep our dependencies up to date. It will periodically create Pull Requests every week to install new versions of any dependencies with updates. Renovate is fully configurable and developers can control its behaviour in their repositories using the PRs it makes. Close a PR to have it ignore updates for that dependency, or leave it open if you want upgrade it later and Renovate will rebase the branch to keep it from getting stale.

## Usage

Create a `.renovate.json` file in your repository, with the following content:

###### `.renovate.json`

```json
{
  "extends": [
    "@telus"
  ]
}
```

You can find the configuration in [`package.json`](./package.json).

Review [Full configuration docs](https://renovatebot.com/docs/configuration-options/)

---
> Github: [@telus](https://github.com/telus) &bull; 
> Twitter: [@telusdigital](https://twitter.com/telusdigital)

[circle-url]: https://circleci.com/gh/telus/renovate-config
[circle-image]: https://img.shields.io/circleci/project/github/telus/renovate-config/master.svg?style=for-the-badge&logo=circleci

[npm-url]: https://www.npmjs.com/package/@telus/renovate-config
[npm-image]: https://img.shields.io/npm/v/@telus/renovate-config.svg?style=for-the-badge&logo=npm
