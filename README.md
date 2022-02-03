# &lt;slm-loop-typewriter&gt; element

This lean (332byte min+gzip) and easy-to-use vanilla js web component will add a looping typewriter effect to your texts. No additional dependencies are required.

![Magic](https://c.tenor.com/b8TEBW18djwAAAAC/amazed-magic.gif)

## Usage

To type the list of items:

`<slm-loop-typewriter items='["first", "the second", "is this the %22third%22?"]' />`

## Options

| Attribute | Description                                                                                                                                                                                                                                                      |
| --------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `items`   | This is used to get the array of items. It is **required** and **must be JSON encoded array**. You can use [encodeURIComponent](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/encodeURIComponent) to fix any character issues |

## Browser support

Browsers with native custom element support. I do not offer IE11 support, but you may be able to make it work with polyfills.

-   Chrome
-   Firefox
-   Safari
-   Microsoft Edge (Chrome based)

## Customisation

This web component only supports basic customisations. If you need to do something more advanced, you can look at how my util-typewriter repository works and make your flavour.

## License

Distributed under the MIT license. See LICENSE for details.
