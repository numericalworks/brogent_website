# Brogent website

A single-page site for [Brogent](../brogent/README.md).

## Preview

Open `index.html` directly, or serve the folder:

```sh
bunx serve .
# or
python3 -m http.server 8080
```

## Updating the download

`brogent.xpi` is copied from the extension project. After rebuilding the extension:

```sh
cp ../brogent/brogent.xpi brogent.xpi
```

The page uses `img/brogent_travelling.webp` for the hero and
`img/brogent_circular_logo.webp` as the favicon.
