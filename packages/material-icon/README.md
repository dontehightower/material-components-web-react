# React Material Icon

A React wrapper for [Material Icons](http://material.io/tools/icons).

## Installation

```
npm install @material/react-material-icon
```

## Usage

### Styles

with Sass:
```js
import '@material/react-material-icon/index.scss';
```

with CSS:
```js
import '@material/react-material-icon/dist/material-icon.css';
```

### Javascript Instantiation

```js
import MaterialIcon from '@material/react-material-icon';

const MyComponent = () => {
  return (
    <MaterialIcon icon='menu' />
  );
}
```

## Props

Prop Name | Type | Description
--- | --- | ---
icon | string | Type of icon to be displayed.
className | string | Classes to pass on to the root `<i>` element.
hasRipple | n/a | If present on element, it will enable the ripple on the icon.
