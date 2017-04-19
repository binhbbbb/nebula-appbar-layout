# \<nebula-appbar-layout\>

A flexbox layout with header, content and footer slots.

## Import

```html
<link rel="import" href="/bower_components/nebula-appbar-layout/nebula-appbar-layout.html"> 
```

## Usage

The element will automatically fill its parent container element.

The element provides slots for header, footer and/or content areas. The header and footer slots will fit their content, while the content slot is fluid and scrollable.

```html
<nebula-appbar-layout>
  <div slot="header"></div>
  <div slot="content"></div>
  <div slot="footer"></div>
</nebula-appbar-layout>
```

## Style

The element can be styled using standard CSS properties. To style slotted content, using the slot attribute and name to target styles.

```css
[slot=header] {
  background-color: darkred;
  color: white;
  padding: 8px;
}
```
