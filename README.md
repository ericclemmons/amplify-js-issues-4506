# amplify-js-issues-4506

> https://github.com/aws-amplify/amplify-js/issues/4506

`npm run start` has an error:

```console
❯ npm run start

> amplify-test@1.0.0 start /private/tmp/4506
> parcel index.js --open

Server running at http://localhost:1234
🚨  /private/tmp/4506/node_modules/@aws-amplify/core/lib-esm/Util/Reachability.js:1:28: Cannot resolve dependency 'zen-observable'
> 1 | import * as Observable from 'zen-observable';
    |                            ^
  2 | var ReachabilityNavigator = /** @class */ (function () {
  3 |     function ReachabilityNavigator() {
  4 |     }
```
