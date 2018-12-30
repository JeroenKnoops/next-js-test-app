# Test application to test bug

This application is a test app for a ticket on next.js; https://github.com/zeit/next.js/issues/5957

## Run

``` 
$ npm
$ npm run dev 
```

## Run with own environment

Go to own fork of next.js

```
$ yarn
$ cd packages/next-server
$ npm link
$ cd ../next
$ npm link
$ npm link next-server
```

Go to app

```
$ npm
$ npm link next
$ npm run dev
```

Now you're running this test app with your own next.js environment.


