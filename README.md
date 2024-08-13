# TinyLightbox

TinyLightbox is a lightweight JavaScript class for creating a simple and customizable image lightbox. It enables users to click on images to view them in a larger format, with an easy-to-use interface that includes a close button and automatic closing when clicking outside the image.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Dependencies](#dependencies)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Introduction

TinyLightbox is a simple and efficient tool for displaying images in a modal-like view. It's designed to be easy to integrate into any web project, requiring minimal setup and offering straightforward functionality. The lightbox is fully responsive and works well on both desktop and mobile devices.

## Features

- Lightweight and easy to integrate
- Simple interface with minimal HTML and CSS
- Customizable with basic CSS classes
- Responsive design
- Close lightbox by clicking outside the image or on the close button

## Installation

You can install TinyLightbox by including the script in your project.

```html
<script type="module" src="path/to/TinyLightbox.js"></script>
```

Alternatively, you can import it as a module if using a build system like Webpack or Rollup.

```javascript
import { TinyLightbox } from './TinyLightbox.js';
```

## Usage

- 1 Initialize the TinyLightbox:

Create an instance of the TinyLightbox class:
```javascript
const lightbox = new TinyLightbox();
```

- 2 Initialize the TinyLightbox:
Use the attach method to bind the lightbox to a set of images:
```javascript 
lightbox.attach('.your-image-selector');
```

Replace '.your-image-selector' with a valid CSS selector that matches the images you want to be clickable.



## Customization

TinyLightbox can be easily customized using CSS. The following classes are used in the default setup:

    tlb-lightbox: The main lightbox container.
    tlb-lightbox__img-container: The container for the image and the close button.
    tlb-lightbox__close: The close button. This contains the SVG icon by default.
    tlb-lightbox__big-img: The large image displayed in the lightbox.
    tlb-is-active: A class added to the lightbox when it is open.

You can modify the styles of these classes in your CSS to suit your design requirements.

## Dependencies

TinyLightbox does not have any external dependencies. It is a pure JavaScript implementation.

## Examples
Here is a basic example of how to use TinyLightbox:

https://alflow.github.io/light-box/


## Contributing

If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License


This README should provide users with the necessary information to understand, install, use, and customize the `TinyLightbox` class. If there are any additional details or specific customizations you'd like to include, feel free to ask!
