# Windstrap

Tailwind CSS with Bootstrap JS

## Installation

```sh
npm install windstrap --save
```

## Usage

### For CSS

Requires Tailwind CSS 2. Tailwind CSS is not included in this package. Learn how to [install tailwind here](https://tailwindcss.com/docs/installation/).

Require the installed plugin directly to your Tailwind config:

```js
// tailwind.config.js
plugins: [require("windstrap")],
```

### For JS

Requires Bootstrap JS 5. Bootstrap JS is not included in this package. Learn how to [install bootstrap js here](https://getbootstrap.com/docs/5.0/getting-started/introduction/#js).

## Documentation

View full documentation at [https://windstrap.netlify.app](https://windstrap.netlify.app).

## Bugs

Found a bug? [Please open a new issue](https://github.com/praveenjuge/windstrap/issues/new).

## Development

You need [Hugo](https://gohugo.io/) to run the dev server. If you have [Homebrew](https://brew.sh/) you can do the following:

```sh
brew install hugo
```

Check this [Hugo installation page](https://gohugo.io/getting-started/installing/) for installing on other systems.

Then clone the repo, install dependencies, and start the server locally.

```sh
git clone https://github.com/praveenjuge/windstrap.git
cd kutty
npm install
npm start
```

Open [`http://localhost:1313`](http://localhost:1313) in your browser.

| Scripts              | Description                                     |
| -------------------- | ----------------------------------------------- |
| `npm start`          | Starts a local Hugo server and Tailwind Watcher |
| `npm run production` | For generating production docs files            |

## License

See the [LICENSE](https://github.com/praveenjuge/windstrap/blob/master/LICENSE) file.
