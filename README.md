# Scroll Animation README

Welcome to the Scroll Animation project! This simple and effective library allows you to add smooth scrolling animations to elements on your website, enhancing user experience and making your site more engaging. Check out the live demo at: https://sonnymay.github.io/Scroll-Animation/

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Customization](#customization)
- [Browser Support](#browser-support)
- [Contributing](#contributing)
- [License](#license)

## Features

- Smooth scroll animations for website elements
- Customizable animation types and durations
- Easy to integrate and use
- Lightweight library with no dependencies

## Getting Started

1. Clone the repository or download the ZIP file:

   ```sh
   git clone https://github.com/sonnymay/Scroll-Animation.git
   ```

   Or download the ZIP file [here](https://github.com/sonnymay/Scroll-Animation/archive/refs/heads/master.zip).

2. Extract the files and include them in your project folder.

3. Add the following file to your HTML file:

   ```html
   <script src="path/to/Scroll-Animation/js/main.js"></script>
   ```

## Usage

1. Add the `data-scroll` attribute to any element you want to animate:

   ```html
   <div data-scroll>
       <!-- Your content here -->
   </div>
   ```

2. Customize the animation by adding additional `data-scroll-*` attributes:

   ```html
   <div data-scroll data-scroll-animation="fadeIn" data-scroll-duration="1s">
       <!-- Your content here -->
   </div>
   ```

   Available options include:
   - `data-scroll-animation`: The type of animation (e.g., "fadeIn", "slideUp", "zoomIn").
   - `data-scroll-duration`: The duration of the animation (e.g., "0.5s", "1s", "2s").

3. That's it! Your element will now animate when it comes into view while scrolling.

## Customization

You can customize the Scroll Animation by modifying the `main.js` file. Here are some options you might want to change:

- `animationOffset`: The distance from the bottom of the viewport at which the animation starts (default: 0.2).
- `defaultAnimation`: The default animation type if none is specified (default: "fadeIn").
- `defaultDuration`: The default animation duration if none is specified (default: "1s").

## Browser Support

The Scroll Animation library is compatible with the following browsers:

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

Please note that the Scroll Animation library may not work correctly on older browsers or those that do not support modern JavaScript features and CSS animations.

## Contributing

We welcome contributions to the Scroll Animation project. Feel free to submit issues, fork the repository, and create pull requests.

## License

The Scroll Animation library is released under the MIT License. See the [LICENSE](https://github.com/sonnymay/Scroll-Animation/blob/master/LICENSE) file for more information.
