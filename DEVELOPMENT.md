# Development

Install [marp](https://marp.app) using `npm` for current user:

```command
$ npm install --save-dev @marp-team/marp-cli
```

## Live preview

```command
$ npx marp --theme-set ./style --html -s slides/ 
```

## Render HTML and PDF

```command
$ npx marp --theme ./style/think.css --html slides/de.md
```

```command
$ export CHROME_PATH="PATH"
$ npx marp --theme ./style/think.css --html slides/de.md --pdf
```
