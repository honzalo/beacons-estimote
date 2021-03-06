# Estimote Beacons

A custom element wrapper for the [Estimotes Javascript SDK (Cordova plugin)](https://github.com/evothings/phonegap-estimotebeacons).
A custom element to identify nearby Beacons. The element retrevies an array of all
beacons returned in the specified region. Default region is {} which will be search
for every beacon out there. The auto property starts the search automatically, or it
can be triggered by executing the proper methods.

For more information please check the [Component Page](http://honzalo.github.io/beacons-estimote/).

For Demo create a Cordova project or use Evothing Studio.

# Usage

beacons-estimote is a web component for ranging Esitmote beacons. Range for all beacons automatically or look for a particular region.

### Install the component

Using Bower:

```sh
bower install honzalo/beacons-estimote
```

### Import the component

Make sure to include the Web components polyfill library and to import the element:

```html
<script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
<link rel="import" href="bower_components/beacons-estimote/beacons-estimote.html">
```

### Use the component

In any part of your application inlcude:

```html
<beacons-estimote beacons="{{beacons}}" auto></beacons-estimote>
```


# Demo

The component only works with the [Cordova plugin for Estimotes](https://github.com/evothings/phonegap-estimotebeacons). Create a Cordova application, add the plugin and use the component.

You can use [Evothing Studio](https://evothings.com/download/) for a quick demo:

<p align="center"><img src="demo/beacons.gif" width="200" /> </p>

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

[MIT License](http://opensource.org/licenses/MIT)
