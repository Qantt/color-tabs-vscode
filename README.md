# ColorTabs for vscode

[![MarketplaceVersion](https://vsmarketplacebadge.apphb.com/version/orepor.color-tabs-vscode-ext.svg)](https://marketplace.visualstudio.com/items?itemName=orepor.color-tabs-vscode-ext#overview)
[![MarkerplaceDownloads](https://vsmarketplacebadge.apphb.com/downloads/orepor.color-tabs-vscode-ext.svg)](https://marketplace.visualstudio.com/items?itemName=orepor.color-tabs-vscode-ext#overview)

![Alt Text](./docs/example_gif.gif)

## Use Cases

If you're working on a monorepo and using vscode, this extension can help you quickly understand if the current file is where you want to be.

For example your repo has both server and client, so this extension will color the client file tabs in one color, and the server file tabs in another.

Another use case is for repos that have both reactJS and react-native files.
Many times the files have the same names but are just in different directories like `mobile/Component.tsx` and `web/Component.tsx`.
With this extension you can easily differntiate between the two.



## Extension Settings

This extension contributes the following settings:

* `colorTabs.config`:  list of mappings from path to color         
"default": [{"regex": ".*\/web\/.*", "color": "#ff0000"},{"regex": ".*\/mobile\/.*", "color":  "#00ff00"}],

