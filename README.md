<p>
  <a href="https://svelte.dev">
	<img alt="Cybernetically enhanced web apps: Svelte" src="https://svelte-assets.surge.sh/banner.png">
  </a>

  <a href="https://www.npmjs.com/package/svelte">
    <img src="https://img.shields.io/npm/v/svelte.svg" alt="npm version">
  </a>

  <a href="https://packagephobia.now.sh/result?p=svelte">
    <img src="https://packagephobia.now.sh/badge?p=svelte" alt="install size">
  </a>

  <a href="https://travis-ci.org/sveltejs/svelte">
    <img src="https://api.travis-ci.org/sveltejs/svelte.svg?branch=master"
         alt="build status">
  </a>

  <a href="https://github.com/sveltejs/svelte/blob/master/LICENSE">
    <img src="https://img.shields.io/npm/l/svelte.svg" alt="license">
  </a>
</p>


## What is Svelte?

Svelte is a new way to build web applications. It's a compiler that takes your declarative components and converts them into efficient JavaScript that surgically updates the DOM.

Learn more at the [Svelte website](https://svelte.dev), or stop by the [Discord chatroom](https://svelte.dev/chat).


## Development

Pull requests are encouraged and always welcome. Don't be afraid to [Pick an issue](https://github.com/sveltejs/svelte/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc) and help us out!

To work on Svelte locally:

Clone repo:
```bash
$ git clone https://github.com/sveltejs/svelte.git
```

Install dependencies:
```bash
$ cd svelte
```
```bash
$ npm install
```

To build the compiler, and all the other modules included in the package:

```bash
$ npm run build
```

To watch for changes and continually rebuild the package (this is useful if you're using [npm link](https://docs.npmjs.com/cli/link.html) to test out changes in a project locally):

```bash
$ npm run dev
```

The compiler is written in [TypeScript](https://www.typescriptlang.org/), but don't let that put you off — it's basically just JavaScript with type annotations. You'll pick it up in no time. If you're using an editor other than [Visual Studio Code](https://code.visualstudio.com/) you may need to install a plugin in order to get syntax highlighting and code hints etc.


### Running Tests

```bash
$ npm run test
```

To filter tests, use `-g` (aka `--grep`). For example, to only run tests involving transitions:

```bash
$ npm run test -- -g transition
```


## Svelte.dev

The source code for https://svelte.dev, including all the documentation, lives in the [site](site) directory. The site is built with [Sapper](https://sapper.svelte.dev). 

To develop locally:

```bash
$ cd site
```
```bash
$ npm install && npm run update
```
```bash
$ npm run dev
```


## License

[MIT](LICENSE)

