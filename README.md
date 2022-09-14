# npm-test-example-install

This package is for demonstrating NPM usage and its potential dangers only.

**DO NOT USE THIS PACKAGE IN YOUR APPLICATION!**

This package defines an `install` script that runs the `whoami` command. When you include `@madpah/npm-test-example-install` as a dependency
and run `npm i` you will see (on Unix systems) your username output.

This non-invasive PoC is designed to highlight an attack vector to poison the Software Supply Chain.

If you've seen this example and are wondering what you can do about it, the author recommends you take a look at [Nexus Firewall](https://www.sonatype.com/products/firewall).

Disclaimer: The author of this demonstration package works at Sonatype :-)