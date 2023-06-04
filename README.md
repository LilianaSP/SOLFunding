# SolFunding Revolutionizing: Harnessing the Power of Solana's Blockchain for Unprecedented Fundraising Opportunities. A Project Developed for SuperTeam's Hackathon. 
"Making Transactions to Multiple Foundations with Solana has never been easier"

### [Live Site](https://sol-funding.vercel.app/)


<img width="1422" alt="Screenshot 2023-06-04 at 11 45 10" src="https://github.com/LilianaSP/SOLFunding/assets/102379771/66fdc465-0d68-457f-bdff-48e52e17be5c">

# install-node

[![NPM version][npm-image]][npm-url]
[![build status][travis-image]][travis-url]
[![Test coverage][codecov-image]][codecov-url]
[![David deps][david-image]][david-url]
[![Known Vulnerabilities][snyk-image]][snyk-url]
[![npm download][download-image]][download-url]

[npm-image]: https://img.shields.io/npm/v/install-node.svg?style=flat-square
[npm-url]: https://npmjs.org/package/install-node
[travis-image]: https://img.shields.io/travis/node-modules/install-node.svg?style=flat-square
[travis-url]: https://travis-ci.org/node-modules/install-node
[codecov-image]: https://codecov.io/gh/node-modules/install-node/branch/master/graph/badge.svg
[codecov-url]: https://codecov.io/gh/node-modules/install-node
[david-image]: https://img.shields.io/david/node-modules/install-node.svg?style=flat-square
[david-url]: https://david-dm.org/node-modules/install-node
[snyk-image]: https://snyk.io/test/npm/install-node/badge.svg?style=flat-square
[snyk-url]: https://snyk.io/test/npm/install-node
[download-image]: https://img.shields.io/npm/dm/install-node.svg?style=flat-square
[download-url]: https://npmjs.org/package/install-node

Install node into node_modules.

---

## Install

```bash
$ npm i install-node -g
```

## Usage

Add `engines['install-node'] = ${version}` on your application's `package.json`:

```js
"engines": {
  "install-node": "^4.5.0"
}
```

- `${version}` follow semver, can be `4.5.0`, `~4.5.0` or `^4.5.0`.

Then run `install-node` command:

```bash
$ install-node
```

Now you can see `node` on `node_modules/.bin/node`.

```bash
$ ll node_modules/.bin/node
node_modules/.bin/node@ -> ../node/bin/node
```

## License

[MIT](LICENSE)
