# Mum's-Website

A simple website I built for my Mum. Has a basic landing page, and a markdown blog. The Markdown will then be converted to standard HTML

## How it works.

Using the `markdown-styles` module we're able to quickly translate a folder-like structure into properly style HTML. `markdown-styles` uses the tried and true `handlebars` module, as such we can further add more templates.

As such, assuming the website looks like so:

```
./
├── Publications/
│   ├── index.md
│   ├── B.md
│   ├── C.md
│   └── D.md
├── Books/
│   ├── index.md
│   ├── B.md
│   ├── C.md
│   └── D.md
└── etc.../
    └── ...
```

running the command `generate-md --layout ./my-layout --input . --output ./output` will generate the appropriate `HTML`, 
which can then easily be hosted on a github page.

This can be done with a simple powershell script (so Mum will just have to alter the content of the text files and double click
to update)

## TODO

 * The landing page

