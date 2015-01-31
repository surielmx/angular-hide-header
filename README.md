Angular Hide Header
==================

Angular directive to hide or show header when user scroll down or up.
Could use on infinite scroll pages

Demo
-------
Check out [the live demo](http://embed.plnkr.co/nqZGAzOXbtVtxDq3JHNP/preview).

Installation
-------

#### via bower:

```
$ bower install angular-hide-header --save
```

Usage
---

1. Include **angularHideHeader** as a dependency for your app

  ```js
  angular.module('myApp', ['angularHideHeader'])
  ```
  
2. Easy, add the directive to header element you want to hide or show.

  ```html
  <header hide-header>
    ...
  </header>
    ```
    > This is the most basic example.
  
Configuration
--- 
  Add **hide-offset** to specify from which pixels from the top header will hide. Default value is 60.

    hide-offset="80"
  
  ```html
  <header hide-header hide-offset="80">
    ...
  </header>
    ```

Next step:
=======
* Hide header when select menu item! 
