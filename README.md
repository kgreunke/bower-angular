# AngularJS (Stable)

[Bower](https://github.com/twitter/bower) package for [AngularJS](http://angularjs.org/).

## Usage

To avoid conflicts with the official AngularJS bowser package, this package will remain unregistered. To use it, add the following to your Bower dependencies.

```json
{
  "dependencies" : {
    "angular" : "git@github.com:PatternConsulting/bower-angular.git#1.0.6"
  }
}
```

**Note that _1.0.6_ refers to the tag, which corresponds to the AngularJS release. Visit the [_tags_](https://github.com/PatternConsulting/bower-angular/tags)
list to see available versions.

## Branches

The `master` branch does not contain any AngularJS distribution. Our [`stable`](https://github.com/PatternConsulting/bower-angular/tree/stable) and [`unstable`](https://github.com/PatternConsulting/bower-angular/tree/unstable) branches track with the respective AngularJS branches.

## Rationale

This is package is duplicative to [bower-angular](https://github.com/angular/bower-angular), but strives to maintain packages for both the stable and unstable AngularJS branches.
