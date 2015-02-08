# &lt;ist-image-map&gt;

> Simple web component to create a static image maps using [Polymer](http://www.polymer-project.org/).


## Demo

[Check it live!](http://quelicoto.es/polymer/ist-image-map/index.html)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install
```

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="elements/ist-image-map.html">
    ```

3. Start using it!

    ```html
    <ist-image-map></ist-image-map>
    ```

## Options

Attribute     | Options     | Default      | Description
---           | ---         | ---          | ---
`lat`         | *float*     | `43.53120`   | Latitude value
`lng`         | *float*     | `-5.655469`  | Longitude value
`zoom`        | *int*       | `12`         | The zoom level of the map.
`w`           | *int*       | `100%`       | 100% the parent element up to 512px (limited by google)
`h`           | *int*       | `100%`       | 100% the parent element up to 512px (limited by google)
`mapstyle`    | *string*    | `gmaps`      | type of map to show, options ['gmaps','openstreetmap']


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/Isiat/ist-image-map/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)