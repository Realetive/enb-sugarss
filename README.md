enb-sugarss
===========

Usage:
```bash
npm i --save-dev enb-sugarss
```

```js
nodeConfig.addTech(
    [require('enb-sugarss/techs/enb-sugarss'), {
        comments : true,
        sourcemap : true,
        plugins : [require('cssnext')()]
    } ],
);
```

**NB!** `enb-sugarss` contain `postcss-import` and you don't need to add it to your dependencies.