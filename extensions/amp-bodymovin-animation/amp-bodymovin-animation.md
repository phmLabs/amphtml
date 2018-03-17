<!---
Copyright 2018 The AMP HTML Authors. All Rights Reserved.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

      http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS-IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
-->

# <a name="amp-bodymovin-animation"></a> `amp-bodymovin-animation`

<table>
  <tr>
    <td width="40%"><strong>Description</strong></td>
    <td>An <code>amp-bodymovin-animation</code> displays the <a href="http://airbnb.io/lottie/ ">AirBnB Bodymovin animation player</a> used to render the JSON generated by Adobe Effects.
  </tr>
  <tr>
    <td width="40%"><strong>Required Script</strong></td>
    <td><code>&lt;script async custom-element="amp-bodymovin-animation" src="https://cdn.ampproject.org/v0/amp-bodymovin-animation-0.1.js">&lt;/script></code></td>
  </tr>
  <tr>
    <td class="col-fourty"><strong><a href="https://www.ampproject.org/docs/guides/responsive/control_layout.html">Supported Layouts</a></strong></td>
    <td>fill, fixed, fixed-height, flex-item, nodisplay, responsive</td>
  </tr>
</table>

[TOC]

## Example

The `width` and `height` attributes determine the aspect ratio of the animation embedded in responsive layouts.

Examples:

```html
  <amp-bodymovin-animation
    layout="fixed"
    width="200" height="200"
    src="https://nainar.github.io/loader.json"
    loop="5">
  </amp-bodymovin-animation>
```

## Attributes

##### src

The path to the exported Bodymovin animation object

##### loop (optional)

Whether the animation should be looping or not. `true` by default. Values can be: `true`|`false`|`number`

##### common attributes

This element includes [common attributes](https://www.ampproject.org/docs/reference/common_attributes) extended to AMP components.

## Validation

See [amp-bodymovin-animation rules](https://github.com/ampproject/amphtml/blob/master/extensions/amp-bodymovin-animation/validator-amp-bodymovin-animation.protoascii) in the AMP validator specification.