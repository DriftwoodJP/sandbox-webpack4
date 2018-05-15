# sandbox-webpack4

See "[Getting Started](https://webpack.js.org/guides/getting-started/)".

```prettyprinted
% npx webpack                                                                                                     (git)-[master]
Hash: 1908a4aeab64bbadfec0
Version: webpack 4.8.3
Time: 12593ms
Built at: 2018/05/15 16:26:42
  Asset    Size  Chunks             Chunk Names
main.js  70 KiB       0  [emitted]  main
Entrypoint main = main.js
[1] (webpack)/buildin/module.js 519 bytes {0} [built]
[2] (webpack)/buildin/global.js 509 bytes {0} [built]
[3] ./src/index.js 264 bytes {0} [built]
    + 1 hidden module

WARNING in configuration
The 'mode' option has not been set, webpack will fallback to 'production' for this value. Set 'mode' option to 'development' or 'production' to enable defaults for each environment.
You can also set it to 'none' to disable any default behavior. Learn more: https://webpack.js.org/concepts/mode/

% npx webpack --config webpack.config.js                                                                          (git)-[master]
Hash: c6b3df7ac5eafdedfca1
Version: webpack 4.8.3
Time: 13402ms
Built at: 2018/05/15 16:30:35
    Asset    Size  Chunks             Chunk Names
bundle.js  70 KiB       0  [emitted]  main
Entrypoint main = bundle.js
[1] (webpack)/buildin/module.js 519 bytes {0} [built]
[2] (webpack)/buildin/global.js 509 bytes {0} [built]
[3] ./src/index.js 264 bytes {0} [built]
    + 1 hidden module

WARNING in configuration
The 'mode' option has not been set, webpack will fallback to 'production' for this value. Set 'mode' option to 'development' or 'production' to enable defaults for each environment.
You can also set it to 'none' to disable any default behavior. Learn more: https://webpack.js.org/concepts/mode/

% npm run build                                                                                                   (git)-[master]

> sandbox-webpack4@1.0.0 build /Users/****/projects_github/sandbox-webpack4
> webpack

Hash: c6b3df7ac5eafdedfca1
Version: webpack 4.8.3
Time: 1131ms
Built at: 2018/05/15 16:31:44
    Asset    Size  Chunks             Chunk Names
bundle.js  70 KiB       0  [emitted]  main
Entrypoint main = bundle.js
[1] (webpack)/buildin/module.js 519 bytes {0} [built]
[2] (webpack)/buildin/global.js 509 bytes {0} [built]
[3] ./src/index.js 264 bytes {0} [built]
    + 1 hidden module

WARNING in configuration
The 'mode' option has not been set, webpack will fallback to 'production' for this value. Set 'mode' option to 'development' or 'production' to enable defaults for each environment.
You can also set it to 'none' to disable any default behavior. Learn more: https://webpack.js.org/concepts/mode/
```
