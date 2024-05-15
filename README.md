`minify` outputs incorrect javascript when using `String.raw`.
To reproduce:

run the raw javascript:

```
$ node main.js
true
```

then minify, and run minified version:

```
$ minify main.js > main.out.js
$ node main.out.js
false
```
