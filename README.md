# Reproduce steps

Type `webpack ./entry.js bundle.js`

See error:

```
Hash: 2327717c43c942fb0689
Version: webpack 1.4.0-beta8
Time: 119ms
Asset  Size  Chunks             Chunk Names
bundle.js  6424       0  [emitted]  main
   [0] ./entry.js 71 {0} [built]
       + 3 hidden modules

ERROR in ./~/css-loader!./~/sass-loader!./style.scss
Module build failed:
@ ./~/style-loader!./~/css-loader!./~/sass-loader!./style.scss 4:14-251
```
