List authors and contributors of your npm dependencies.

# Use

To run with `npx`:

```bash
cd your-npm-project
npx npm-authors-contributors
```

To install and use `npm-authors-contributors` globally:

```bash
npm install --global licensee
cd your-npm-project
npm-authors-contributors
```

To install as a development dependency of your package:

```bash
cd your-npm-project
npm install --save-dev npm-authors-contributors
```

For output as newline-delimited JSON objects, for further processing:

```bash
cd your-npm-project
npm-authors-contributors --ndjson
```

# JavaScript Module

The package exports an asynchronous function of three arguments:

1. A configuration object.

2. The path of the package to check.

3. An error-first callback that yields an array of objects, one per author and contributor.
