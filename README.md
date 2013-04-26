# AngularJS

[Bower](https://github.com/bower/bower) package for [AngularJS](http://angularjs.org/). This project _makes makes no modifications_ to the stock AngularJS build.

## Usage

To avoid conflicts with the official AngularJS bowser package, this package will remain unregistered. To use it, add the following to your Bower dependencies.

```json
{
  "dependencies" : {
    "angular" : "git@github.com:PatternConsulting/bower-angular.git"
  }
}
```

**Note that implies the `latest`**, which corresponds to the newest, unstable AngularJS release. Visit the [_tags_](https://github.com/PatternConsulting/bower-angular/tags) list to see available versions, and [usage notes on Bower dependencies](https://github.com/bower/bower#usage) for details.

## Branches

The `master` branch does not contain any AngularJS distribution. Our [`stable`](https://github.com/PatternConsulting/bower-angular/tree/stable) and [`unstable`](https://github.com/PatternConsulting/bower-angular/tree/unstable) branches track with the respective AngularJS branches.

## Rationale

This is package is slightly duplicative with [bower-angular](https://github.com/angular/bower-angular), but intends to maintain packages for both the stable and unstable AngularJS branches.
