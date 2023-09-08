# Follow Me Toggle Button

This is a simple HTML and CSS code example that demonstrates how to create a toggle button with a "Follow Me" feature. When the user clicks on the button, it toggles between two states: "Follow me" and "Eh? Alright." The button design is visually appealing, featuring a circular shape and a sliding knob.

## Table of Contents

- [Getting Started](#getting-started)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)
- [Preview](#preview)
  
---

## Getting Started

To use this toggle button in your HTML project, follow these simple steps:

1. Clone this repository or download the necessary files:

   ```
   git clone https://github.com/Aarzoo75/Follow-me-toggle-button.git
   ```

2. Include the `style.css` file in your HTML document:

   ```html
   <link rel="stylesheet" href="style.css">
   ```

3. Add the HTML structure for the toggle button to your HTML file:

   ```html
   <!DOCTYPE html>
   <html lang="en">
   <head>
       <meta charset="UTF-8">
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <link rel="stylesheet" href="style.css">
       <title>Follow Me Toggle Button</title>
   </head>
   <body>
       <input type="checkbox" id="lol-checkbox">
       <label id="button" for="lol-checkbox">
           <div id="knob"></div>
           <div id="subscribe">Follow me</div>
           <div id="alright">eh? alright</div>
       </label>
   </body>
   </html>
   ```

## Usage

Once you've added the HTML structure and included the `style.css` file, the toggle button should be fully functional. When a user clicks on the button, it will toggle between the "Follow me" and "Eh? Alright" states.

## Customization

You can customize the appearance and behavior of the toggle button by modifying the CSS code in the `style.css` file. Here are some customization options:

- Change the button's size: Adjust the `width` and `height` properties in the `#button` selector.
- Customize the button colors: Modify the `background-color` property in the `#button` selector.
- Change the knob's appearance: Replace the `background-image` URL and adjust the `background-size` property in the `#knob` selector.
- Adjust the text content and styles: Modify the `#subscribe` and `#alright` selectors to change the text, font size, colors, and positioning.

Feel free to experiment and make the toggle button fit your project's design requirements.

## Contributing

If you'd like to contribute to this project, please fork the repository, make your changes, and submit a pull request. We welcome contributions from the community.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use and modify this code for your own purposes.

## Demo

<img width="952" alt="Screenshot 2023-09-08 165613" src="https://github.com/Aarzoo75/Follow-me-toggle-button/assets/59678435/96b62d89-bcc4-42a5-afba-f10b05841c10">
