# Stylelint Config 

## Installation 

Install stylelint-reusable-config:

```
npm install --save-dev @pp/stylelint-reusable-config
```

Then, add "@pp/stylelint-reusable-config" to the "extends" array in your .stylelintrc.* file. Make sure to put it last, so it gets the chance to override other configs.

```js
{
  "extends": [
    "some-other-config-you-use",
    "@pp/stylelint-reusable-config"
  ]
}
```
