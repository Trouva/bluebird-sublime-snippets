# bluebird-sublime-snippets
Sublime Text Bluebird snippets

## Installation

Save them to your `Packages/User` folder.

## API

- `then`:
```js
then(function($1) {
    $2
})$3
```

- `new`:
```js
new Bluebird(function(resolve, reject) {

});
```

- `catch`:
```js
catch(function(err) {
    $2
})$3
```

- `each`:
```js
each(function($1) {
    $2
})$3
```

- `map`:
```js
map(function($1) {
    $2
})$3
```

- `tap console`:
```js
tap(console.log.bind(console, $1))
```

