# angular-scroll-trigger

> Set triggers for the user verticle scrolling action, in AngularJS.

## Install
1. `bower install -S angular-scroll-trigger`
2. Insert `<script src="/path/to/your/angular-scroll-trigger.js"></script>` after angular.js

## Usage
1. Add `tomNgSTrigger` as your module dependency
2. Add attributes to the elements like this:
```html
<ol st-class="{'class1': [1000, 2000], 'add-class2': 'enter', 'remove-class3': 'leave', 'add-class4': 'leave'}">
    <li>add 'class1' when you scroll into 1000~2000 (scrollTop)</li>
    <li>add 'class2' when the element scroll into viewport</li>
    <li>remove 'class3' when the element scroll out of the viewport</li>
    <li>add 'class4' when the element scroll out of the viewport</li>
</ol>
```
What it does:
> 1. add 'class1' when you scroll into 1000~2000 (scrollTop)
> 2. add 'class2' when the element scroll into viewport
> 3. remove 'class3' when the element scroll out of the viewport
> 4. add 'class4' when the element scroll out of the viewport


## License
[MIT](http://mit-license.org/)
