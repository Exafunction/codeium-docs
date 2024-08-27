# Codeium Docs

Welcome to the Codeium docs page source code.
The docs serve as a reference point for Codeium usage, across all surfaces of the product:
our VS Code extension, our JetBrains plugin, our PR review system Forge, our Chrome extension, our Enterprise deployment guides, and more.
It is currently under construction!

### Development

We use [Mintlify](https://mintlify.com/) as our docs provider.
To develop locally and preview the changes, install the [Mintlify CLI](https://www.npmjs.com/package/mintlify).

```bash
npm i mintlify
```

Run the following command at the root of this repo (where `mint.json` is)

```bash
npx mintlify dev
```


#### Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `mint.json`
