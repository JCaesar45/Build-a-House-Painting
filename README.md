```marked
# House Painting Project

## Description

This project involves building a simple HTML and CSS-based representation of a house. The house includes elements such as a roof, chimney, windows, and a door, each styled using CSS with absolute positioning inside a relative-positioned container. The project is intended to practice basic HTML structure, CSS positioning, and styling.

## User Stories Fulfilled

* The `#house` div has a relative position and specific dimensions (500px width and 400px height).
* The `#house` div has a background color and a border.
* Five div elements within the `#house` div: `#chimney`, `#roof`, `#window-1`, `#window-2`, and `#door`.
* All the immediate children of the `#house` div are positioned absolutely.
* The `#chimney`, `#roof`, `#window-1`, `#window-2`, and `#door` divs have width, height, background colors, and borders.
* The `#roof` is positioned at the top of the house (`top: 0`).
* The `#door` is positioned at the bottom of the house.
* The `#window-1` and `#window-2` are placed below the `#roof`, above one-third of the `#door` height, and positioned inside the house borders.
* The `#chimney` is placed at the top of the house and has a `z-index` to position it behind the house.

## Technologies Used

* **HTML**: Structure of the house.
* **CSS**: Styling and positioning elements inside the house.

## Setup

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/house-painting-project.git
   ```
```
2. Navigate into the project directory:

   ```bash
   cd house-painting-project
   ```
```
3. Open `index.html` in your web browser to view the project:

   ```bash
   open index.html
   ```
```
## File Structure

```
/house-painting-project
    ├── index.html
    ├── styles.css
    └── README.md
```

### index.html

This file contains the HTML structure for the house and links to the CSS stylesheet.

### styles.css

This file contains the CSS for positioning and styling the house elements, including the roof, windows, door, and chimney.

## How It Works

* **House Container**: The `#house` div is the main container with a `position: relative` to allow its children to be positioned absolutely inside it.
* **Chimney**: Positioned at the top with a `top: 0` value, and placed behind the house using `z-index: -1`.
* **Roof**: Positioned at the top of the house, spanning the width of the container.
* **Windows**: Positioned below the roof, with one window on the left and the other on the right, keeping them inside the house borders.
* **Door**: Positioned at the bottom of the house, centered horizontally.

## Tests

This project includes a series of tests to ensure the structure and styling are correct, including checks for proper positioning and the required elements:

1. The house container has the correct size, position, and background color.
2. The chimney, roof, windows, and door are properly positioned.
3. The chimney is placed at the top of the house and behind the other elements.

## Conclusion

This project is a simple demonstration of using HTML and CSS for creating a styled container with absolute positioning. It is an excellent exercise for learning layout techniques and CSS properties like `position`, `z-index`, and `background-color`.
