# image-thumbnail

A Polymer Element showing a stylized image thumbnail with on-click behavior.

### Example
```html
<image-thumbnail
  source="http://source"
  style-class="style-class"
  click-listener="[[listener]]">
</image-thumbnail>
```

### Styling

`<image-thumbnail>` provides the following custom properties and mixins for styling:

Custom property           | Description                                    | Default
--------------------------|------------------------------------------------|--------
`--image-highlight-color` | The background color of the highlighted image. | none
`--image-highlight-style` | The style of the highlighted image.            | none

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve

