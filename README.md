# Animated Ripple Effect Landing Page

This repository contains code for a landing page showcasing the beauty of Maldives islands, beaches and activities with an interactive slider.

## Features

- The file contains a jQuery plugin called "Ripples" (version 0.6.3) for creating water ripple effects on webpages.
- The plugin uses WebGL technology to render the ripple effects.
- It supports various configuration options such as interactivity, resolution, perturbance, drop radius, cross-origin settings, and image URL.
- The plugin automatically resizes the ripple canvas when the window size changes.
- It utilizes render targets and framebuffers to store and manipulate ripple data.
- The plugin provides a CSS class "jquery-ripples" and appends a canvas element to the target element to display the ripple effect.
- The file contains an image slider implemented using the Swiper library.

## Additional Features

The web page includes additional features such as:

- **GSAP Animations**: The GreenSock Animation Platform (GSAP) is used to create animations for the background and text elements.
- **Ripple Effect**: The ripple effect is applied to the background images in the slider using the ripples function from ripple.js.
- **Swiper Slider**: The Swiper library is used to create an interactive slider with a creative effect.
- **WebGL Configurations**: The code includes a function loadConfig that loads a configuration of GL settings which the browser supports. It checks for WebGL support, floating point textures, linear filtering for floating point textures, rendering to floating point textures, and rendering to half-floating point textures.

## Dependencies

The project uses the following external libraries:

- [Swiper](https://swiperjs.com/): A modern touch slider which is focused on modern web and mobile app development.
- [GSAP](https://greensock.com/gsap/): A JavaScript animation library that works in all major browsers.
- [Remix Icon](https://remixicon.com/): A set of open-source neutral-style system symbols for designers and developers.
- [jQuery](https://jquery.com/): A fast, small, and feature-rich JavaScript library.
- [jQuery Ripples](https://github.com/sirxemic/jquery.ripples): A jQuery plugin to create a water ripple effect on images.

## Technologies Used

- **jQuery**: The Ripples plugin is built as a jQuery plugin and requires the jQuery library to function.
- **WebGL**: The plugin utilizes WebGL technology for rendering the water ripple effect.
- **JavaScript**: The plugin is written in JavaScript to define the functionality and behavior of the ripple effect.
- **HTML**: The plugin generates and manipulates HTML elements, specifically canvas elements, to display the ripple effect.
- **CSS**: The plugin includes a CSS style definition to apply positioning and z-index to the target element and the ripple canvas

## How to Use

1. Clone the repository to your local machine.
2. Open the index.html file in your browser to view the web page.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them:

- A modern web-browser like Chrome, Firefox etc.
- A text editor to edit HTML, CSS, and JavaScript files.

### Installing

A step by step series of examples that tell you how to get a development environment running:

1. Download or clone the repository to your local machine.
2. Open the index.html file in your web browser.
3. You can now interact with the landing page.
