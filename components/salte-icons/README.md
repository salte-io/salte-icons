[![Slack Status][slack-image]][slack-url]
[![Travis][travis-ci-image]][travis-ci-url]

_[Demo and API docs][salte-icon-docs]_

## &lt;salte-icons&gt;

`salte-icons` is a utility import that includes the definition for the `iron-icon` element, `iron-iconset-svg` element, as well as an import for the default icon set.

The `salte-icons` directory also includes imports for additional icon sets that can be loaded into your project.

Example loading icon set:

```html
<link rel="import" href="../salte-icons/salte-icons.html">
```

To use an icon from one of these sets, first prefix your `iron-icon` with the icon set name, followed by a colon, ":", and then the icon id.

Example using the logo icon from the salte icon set:

```html
<iron-icon icon="salte:logo"></iron-icon>
```

[slack-image]: https://salte-slack.herokuapp.com/badge.svg
[slack-url]: https://salte-slack.herokuapp.com/

[travis-ci-image]: https://travis-ci.org/salte-io/salte-icons.svg?branch=master
[travis-ci-url]: https://travis-ci.org/salte-io/salte-icons

[salte-icon-docs]: https://salte-io.github.io/salte-icons
