AnchorJS
========

<img alt="AnchorJS logo" src="data:image/png;base64,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" />

A tiny javscript utility for adding anchor links to page content.

See the [Demo](http://bryanbraun.github.io/anchorjs/).

Currently Supports: IE9+

Licensed with the [MIT License](http://opensource.org/licenses/MIT).