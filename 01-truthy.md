# Truthy et Falsy

Oh la la Truthy c'est cringe.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla vulputate felis nec orci gravida, quis consectetur nisl interdum. Vestibulum cursus, enim ut vehicula varius, magna purus lacinia sem, vel mattis ipsum neque nec tellus. Aenean feugiat maximus dolor sed semper. Morbi eu turpis et arcu maximus placerat eu in eros. In non nisl ut justo varius eleifend vitae vel justo. Cras sed tellus ut diam egestas viverra in id mauris. Etiam tristique, felis vitae commodo rutrum, orci ex tincidunt est, id varius odio libero ut felis. Pellentesque porttitor consequat laoreet. Fusce semper tellus eu bibendum rutrum.

> ## MDN
> all values are truthy except false, 0, -0, 0n, "", null, undefined, and NaN

## Exercise

### Problem
What will be the result ?
```js
if (true) {
  console.log('true');
}
if ({}) {
  console.log('{}');
}
if ([]) {
  console.log('[]');
}
if (0) {
  console.log('0');
}
if ("") {
  console.log('""');
}
if ("false") {
  console.log('"false"');
}
```

### Solution
```
true
{}
[]
"false"
```

## References
MDN https://developer.mozilla.org/en-US/docs/Glossary/Truthy

