# pkg-test

Test with `npm run start`

It should build and then throw an `UNEXPECTED-15` error. Replace the relative path in `pkg.assets[0]` within `package.json` with a absolute path to the module. Then it should build correctly and run.
