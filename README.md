# generator-react-express

> [Yeoman](http://yeoman.io) generator for [React](http://facebook.github.io/react/) and [express](http://expressjs.com/)

Builds a simple project to help you get started with React on the client, express for the server and browserify to pull it all together.

JSX and ES6 are transpiled by Babel. The `object-assign` babel plugin is also included.


## Getting Started

Install the generator:

```bash
npm install -g generator-react-express
```

Then run the generator:

```bash
yo react-express
```

... and follow the prompts.


### Includes `react/addons`

To avoid a nasty bug that can happen when `react/addons` is used without being declared in the common bundle, it is included by default.

If you don't need the additional addons in your project, remove that line from the `client/config.js` file in your project to reduce your common bundle size.


## Feedback?

I'd love to hear it. Open an issue or submit a PR.


## License

MIT
