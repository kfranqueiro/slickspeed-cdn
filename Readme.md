# SlickSpeed

## Speed / Validity tests for dom queries in JavaScript web frameworks.

### Instructions

* Edit config.ini and fill in your framework list.  Each ini section maps to one framework entry, with the following properties:
    * **lib:** name of the library to load from Google CDN
    * **version:** version of the library to load
    * **file:** filename (possibly including path) to load under the directory for the specified version
    * **function:** function (in the global context) to invoke the library's query engine
* Edit selectors.list and fill in your preferred selectors list.
* Edit style.css, header.html and footer.html, if you wish.
* Edit template.html if you want to change the selectors html file. It DOES NOT accept the full document, just elements.

### License

MIT-Style License.