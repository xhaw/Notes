# Readings in the order according to Angular docs

### [ES6 In Depth: Modules](https://hacks.mozilla.org/2015/08/es6-in-depth-modules/)

- An ES6 module is a file containing JS code
- export: any top-level function, class, var, let, or const
- `import {detectCats, Kittydar} from "kittydar.js";`
- export list: `export {i1, i2}`
- renaming: `{xx as XX}`
- default
	- import without {}: equivalent of `var x = require("X");`
	- `export default ...`
- module object: `import * as cows from "cows";`, then `cows.moo()`
- aggregating modules(main module): `export ... from ...;`, doesn't add re-exported bindings to your scope
- bundle all your modules into a single file to ship them: webpack etc.
- ES6 module syntax is very static, can work alongside a rich dynamic, programmatic loader API.
- need a compiler
 
### [JavaScript Modules vs. NgModules](https://angular.io/guide/ngmodule-vs-jsmodule#javascript-modules-vs-ngmodules)

- use declarable class only 
- list member classes in @NgModule.declarations
- only export declarable classes


### [Bootstrapping](https://angular.io/guide/bootstrapping)

- declarations

```typescript
declarations: [
  YourComponent,
  YourPipe,
  YourDirective
],
```

### [Frequently Used Modules](https://angular.io/guide/frequent-ngmodules)



### [Feature Modules](https://angular.io/guide/feature-modules)

### [Types of Feature Modules](https://angular.io/guide/module-types)

### [Routing & Navigation](https://angular.io/guide/router)

### [Lazy Loading Feature Modules](https://angular.io/guide/lazy-loading-ngmodules)
	
