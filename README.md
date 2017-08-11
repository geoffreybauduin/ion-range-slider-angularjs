# ion-range-slider-angularjs
Ion Range Slider for AngularJS https://github.com/IonDen/ion.rangeSlider

## How to use this module

```
angular.module("app", ["ion.rangeslider"]);

angular.module("app").controller("Controller", function ($scope) {
    $scope.model = {
        age: {
            min: 18,
            max: 99
        }
    }
});
```

```
<div ng-controller="Controller">
    <input ion-range-slider min="18" max="60" from="model.age.min" to="model.age.max" />
</div>
```

## License

The MIT License (MIT)

Copyright (c) 2017 Geoffrey Bauduin

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
