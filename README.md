# base-ui-css-intellisense-data

Versioned data releases for the [Base UI CSS Intellisense](https://github.com/IdoS350/base-ui-css-intellisense) VS Code extension.

## What's here

Each release is tagged `base-ui-v{version}` and contains a single asset — `base-ui-attributes.json` — generated from the [Base UI](https://github.com/mui/base-ui) source at that version. The extension fetches this file at runtime to power CSS variable and data attribute completions.

## Releasing

Trigger the **Publish Data Release** workflow manually from the Actions tab, passing the Base UI version (e.g. `1.2.3`). The workflow will generate the data from that version's source and publish it as a new release.
