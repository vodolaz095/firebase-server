# Changelog

## 0.4.0 - TBD

- Basic support for Firebase Security ruels

## 0.3.1 - 2015-08-18

- Bugfix: Wire protocol does not match Firebase server (fixes [#9](https://github.com/urish/firebase-server/issues/9), contributed by [azell](https://github.com/azell))

## 0.3.0 - 2015-07-21

- Implement `update()` (fixes [#5](https://github.com/urish/firebase-server/issues/5))
- Implement `transaction()`
- Bugfix: `remove()` triggers two value events (fixes [#6](https://github.com/urish/firebase-server/issues/6))

## 0.2.0 - 2015-06-12

- Upgrade `MockFirebase` to 0.11.0, as well as other dependencies.
- Bugfix: Value callbacks were always triggered with null first ([#2](https://github.com/urish/firebase-server/issues/2))

## 0.1.1 - 2015-05-23

- Fix a bug with supporting Firebase client library 2.2.4+ (fixes [#1](https://github.com/urish/firebase-server/issues/1))

## 0.1.0 - 2014-11-21

- Firebase 2.0 Support

## 0.0.2 - 2014-09-06

- Add `close()` method to stop the server
- Add `getData()` method that returns a copy of the server's data 
- Add functional tests
- Make logging optional (through `FirebaseServer.enableLogging()`)

## 0.0.1 - 2014-09-05

- Initial release
