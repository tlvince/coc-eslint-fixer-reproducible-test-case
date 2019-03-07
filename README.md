# coc-eslint-fixer-reproducible-test-case

> Test case for eslint plugins autofix

coc diagnostics message:

```
[eslint prettier/prettier] [E] Delete `;;;;;` (prettier/prettier)
```

Expected output on write:

```js
a();
```

The following works as expected:

```
❯ yarn eslint --fix .
```

## CocInfo

```
## versions

vim version: NVIM v0.3.1
node version: v10.15.1
coc.nvim version: 0.0.58
term: iTerm.app
platform: darwin

## Error messages

## Output channel: watchman
[Info  - 11:08:30 AM] watchman watching project /Users/tomvincent/dev/coc-eslint-fixer-reproducible-test-case
[Info  - 11:08:30 AM] subscribing "**/.eslintr{c.js,c.yaml,c.yml,c,c.json}" in /Users/tomvincent/dev/coc-eslint-fixer-reproducible-test-case
[Info  - 11:08:30 AM] subscribing "**/.eslintignore" in /Users/tomvincent/dev/coc-eslint-fixer-reproducible-test-case
[Info  - 11:08:30 AM] subscribing "**/package.json" in /Users/tomvincent/dev/coc-eslint-fixer-reproducible-test-case
[Info  - 11:08:32 AM] subscribing "**/[tj]sconfig.json" in /Users/tomvincent/dev/coc-eslint-fixer-reproducible-test-case
[Info  - 11:08:32 AM] subscribing "**/package.json" in /Users/tomvincent/dev/coc-eslint-fixer-reproducible-test-case
[Info  - 11:08:32 AM] subscribing "**/*.ts" in /Users/tomvincent/dev/coc-eslint-fixer-reproducible-test-case
[Info  - 11:08:32 AM] subscribing "**/*.js" in /Users/tomvincent/dev/coc-eslint-fixer-reproducible-test-case

## Output channel: tsserver
[Info  - 11:08:32 AM] Forking TSServer
PATH: /Users/tomvincent/bin:/Users/tomvincent/.cabal/bin:/Users/tomvincent/bin:/Users/tomvincent/.local/bin:/Users/tomvincent/.rbenv/shims:/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin:/usr/local/share/npm/bin:/Users/tomvincent/Library/Python/2.7/bin:/Users/tomvincent/Library/Python/3.5/bin 
[Info  - 11:08:32 AM] Started TSServer
{
  "path": "/Users/tomvincent/.config/coc/extensions/node_modules/typescript/lib",
  "_pathLabel": "",
  "_api": {
    "versionString": "3.3.3333",
    "version": "3.3.3333"
  }
}

## Output channel: eslint
[Info  - 11:08:32 AM] ESLint server running in node v10.15.1
[Info  - 11:08:33 AM] ESLint library loaded from: /Users/tomvincent/dev/coc-eslint-fixer-reproducible-test-case/node_modules/eslint/lib/api.js
```


## Author

© 2019 Tom Vincent <git@tlvince.com> (https://tlvince.com)

## License

Released under the [MIT license](http://tlvince.mit-license.org).
