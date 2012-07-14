# Custom Input Validation Error Messages

A jQuery plugin to change the HTML5 validation error messages to whatever you wish in forms. For translation or consistency with your server-side error messages.

## Quick Start & API

Add the latest version and use `data-errormessage` and `data-errormessage-*` attributes on your `input` elements.

Any form with `input`, `textarea` or `select` element may contain:

* `data-errormessage` a generic error message

[Validity state](http://dev.w3.org/html5/spec/constraints.html#validitystate) specific error messages:

* `data-errormessage-value-missing`
* `data-errormessage-type-mismatch`
* `data-errormessage-pattern-mismatch`
* `data-errormessage-too-long`
* `data-errormessage-range-underflow`
* `data-errormessage-range-overflow`
* `data-errormessage-step-mismatch`
* `data-errormessage-custom-error`

To apply this data error messages in the HTML5 form just only have to code: `$('#form').civem();` on document ready function (for example, or whenever you want).

Show an example form in `example.html`.

## Tested on

* Chrome 20.0.1132.47
* Firefox 13.0.1
