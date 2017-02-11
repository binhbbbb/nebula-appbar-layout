[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/arsnebula/nebula-appbar-layout)

[![Build Status](https://saucelabs.com/browser-matrix/arsnebula.svg)](https://saucelabs.com/beta/builds/551af902d3674868b74f7c4402142fe6)

# \<nebula-appbar-layout\>

A web component to display an application bar layout.

* Provides header, content and/or footer slots
* Header and footer slots will fit content
* Content slot is fluid and scrollable

## Installation

```
$ bower install -S arsnebula/nebula-appbar-layout
```

## Usage

Import the element:

```
<link rel="import" href="/bower_components/nebula-appbar-layout/nebula-appbar-layout.html"> 
```

Add the element markup and provide containers for one or more of the available slots:

```html
<nebula-appbar-layout>
  <div slot="header"></div>
  <div slot="content"></div>
  <div slot="footer"></div>
</nebula-appbar-layout>
```

Add additional styles targeting each slot using the slot attribute:

```css
[slot=header] {
  background-color: darkred;
  color: white;
  padding: 8px;
}
```

*For more information on element properties and methods see the element API documentation.*

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Change Log

See [CHANGELOG](/CHANGELOG.md)

## License

See [LICENSE](/LICENSE.md)