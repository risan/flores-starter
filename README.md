# Flores Starter

Flores starter template for blog.

## Documentation

Checkout [Flores repository](https://github.com/risan/flores#flores) for a complete documentation.

## Getting Started

### 1. Download the Starter Template

Run the following command on your terminal to download [Flores starter template](https://github.com/risan/flores-starter).

```bash
$ wget https://github.com/risan/flores-starter/archive/master.zip \
    -O master.zip && \
    unzip master.zip && \
    mv flores-starter-master my-blog && \
    rm master.zip
```

It will automatically download the starter template and unzip it to `my-blog` directory.

Or you can also [download the starter template](https://github.com/risan/flores-starter/archive/master.zip) and unzip it manually.

### 2. Install All Dependencies

Within your project directory, run the following command to install all dependencies:

```bash
$ npm install
```

### 3. Generate the Website

Run the following command to generate your website for production:

```bash
$ npm run build
```

For development purpose, you can preview your generated website with the built-in server:

```bash
$ npm run serve
```

Flores also comes with file watcher that can rebuild your website and reload the browser automatically:

```bash
$ npm run build
```

## Related

* [flores](https://github.com/risan/flores): Flores core JavaScript module.
* [flores-cli](https://github.com/risan/flores-cli): Flores CLI tool.

## License

[MIT](https://github.com/risan/flores-starter/blob/master/LICENSE) © [Risan Bagja Pradana](https://bagja.net)
