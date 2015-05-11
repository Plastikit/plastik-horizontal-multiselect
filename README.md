core-horizontal-multiselect
============

**This element is only compatible with Polymer 0.5.x. At the moment, there is no equivalent for Polymer 0.8.x.**

core-horizontal-multiselect is a horizontal, multi-selectable listbox with support for reset items. It was inspired by the [filter
controls](http://i.imgur.com/kWMxW0X.png) in the new Google Maps Android app.

Demos and documentation are available on the [component page](https://vsimonian.github.io/polymer-elements/components/core-horizontal-multiselect/).

Pull requests are always welcome. If you encounter any bugs, please feel free to [submit an issue](https://github.com/vsimonian/core-horizontal-multiselect/issues/new/).

## Installation

```sh
bower install vsimonian/core-horizontal-multiselect --save
```
## Basic usage

 > _See [component page](https://vsimonian.github.io/polymer-elements/components/core-horizontal-multiselect/) for more details_
 
 ```html
<core-horizontal-multiselect>
    <core-item reset>Any</core-item>
    <core-item value="0">Free</core-item>
    <core-item value="1-100">$1 - $100</core-item>
    <core-item value="101-500">$101 - $500</core-item>
    <core-item value="501+">$501+</core-item>
</core-horizontal-multiselect>
 ```
