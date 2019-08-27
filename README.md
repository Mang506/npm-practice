# npm-practice
Practicing with npm commands and packages.

## Nodejs 12.9.0 Error
Might get the following error when installing packages:

(node:21463) MaxListenersExceededWarning: Possible EventEmitter memory leak detected. 11 drain listeners added to [TLSSocket]. Use emitter.setMaxListeners() to increase limit

This is a current issue on Nodejs 12.9.0 (https://github.com/nodejs/node/issues/29239)

From the link above:

"When is a fix coming out?

Probably some time on August 27 2019 (UTC)."
