# baasic-markdowneditor

> [Baasic](http://www.baasic.com) markdown editor Web Component.

## Demo

[Check it live!](http://demo.baasic.com/polymer/)

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install baasic-markdowneditor --save

## Playing With Your Element

If you wish to work on your element in isolation, we recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polyserve

And you can run it via:

    polyserve

Once running, you can preview your element at
`http://localhost:8080/components/baasic-markdowneditor/`, where `baasic-markdowneditor` is the name of the directory containing it.

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents-lite.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/baasic-markdowneditor/baasic-markdowneditor.html">
    ```

3. Start using it!

    ```html
    <baasic-markdowneditor id="editor"></baasic-markdowneditor>
    ```
    
## Testing Your Element

Simply navigate to the `/test` directory of your element to run its tests. If
you are using Polyserve: `http://localhost:8080/components/baasic-markdowneditor/test/`

### web-component-tester

The tests are compatible with [web-component-tester](https://github.com/Polymer/web-component-tester).
Install it via:

    npm install -g web-component-tester

Then, you can run your tests on _all_ of your local browsers via:

    wct

#### WCT Tips

`wct -l chrome` will only run tests in chrome.

`wct -p` will keep the browsers alive after test runs (refresh to re-run).

`wct test/some-file.html` will test only the files you specify.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/baasic/baasic-sdk-polymer-core-markdowneditor/releases).