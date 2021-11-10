# Initialize sass
## Create a npm package
```
npm init
```

## Add sass dev dependencies
```
npm install -D node-sass
```

## Add build script in package.json
```json
"scripts": {
	"build-css": "node-sass src/scss -w -o src"
}
```


# Run command
```
npm run build-css
```
