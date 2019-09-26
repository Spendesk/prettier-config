# `@spendesk/prettier-config`

Shared [prettier](http://prettier.io) config at Spendesk.

## Using it

Make sure you have access to Github's package registry.
Then, add `@spendesk/prettier-config` to your `devDependencies` (with `yarn add --dev @spendesk/prettier-config`).
Finally, in the `package.json` file of your package, add the following key:

```json5
{
  // ...
  "prettier": "@spendesk/prettier-config",
  // ...
}
```
