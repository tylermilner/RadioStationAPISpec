# RadioStationAPISpec
A RAML specification for a generic internet radio station API. The API is being developed in Swift Vapor [here](https://github.com/tylermilner/RadioStationAPI).

**🚧 This is a work in progress. 🚧**
* The general structure of the API has been defined, but is not final.
* View the API structure by opening the included `.raml` files in your favorite text editor.
* You can also view the API in a more human-readble form in `raml2html/index.html`.
* The docs are also hosted [online](https://radiostationapi-dev.vapor.cloud/docs/index.html).

### Generating the HTML Documentation

The `index.html` is generated from the RAML spec using [raml2html](https://github.com/raml2html/raml2html) using the [raml2html-plain-theme](https://www.npmjs.com/package/raml2html-plain-theme)].
**Install raml2html**
`npm i -g raml2html`
**Install the theme**
`npm i -g raml2html-plain-theme`
**Use raml2html to generate the HTML**
 `raml2html --theme raml2html-plain-theme api.raml > raml2html/index.html`

## Disclaimer

My knowledge and experience in RAML is limited and I know there are many features I'm not taking full advantage of. Don't look at this too hard for best practices, but it may help you get started on your API spec if you need something to get some ideas from. 😄
