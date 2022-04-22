# Stylelint Config 

## Installation 

Install stylelint-reusable-config:

```
npm install --save-dev @peter-popluhar/stylelint-reusable-config
```

Then, add "@peter-popluhar/stylelint-reusable-config" to the "extends" array in your .stylelintrc.* file. Make sure to put it last, so it gets the chance to override other configs.

```js
{
  "extends": [
    "some-other-config-you-use",
    "@peter-popluhar/stylelint-reusable-config"
  ]
}
```
