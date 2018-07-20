# Firebase Web Codelab - Start code

This folder contains the starting code for the [Firebase: Build a Real Time Web Chat App Codelab](https://codelabs.developers.google.com/codelabs/firebase-web/).

If you'd like to jump directly to the end and see the finished code head to the [web](../web) directory.

## Installation

```
$ npm -g install firebase-tools
$ firebase login
$ firebase use --add
```

## Start a local server

```
$ firebase serve
```

## Deploy code and assets

```
$ firebase deploy --only database
$ firebase deploy --only storage
$ firebase deploy --except functions
```

## Stop serving web traffic

```
$ firebase hosting:disable
```
