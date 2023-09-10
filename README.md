# Flex-box Photo Gallery Ass-6 CSS

## Hosted Link: [View Project](https://saifulislam05.github.io/flex-box-photo-gallery/)
## Project Description
The "Photo Gallery" project is a responsive web page that showcases a collection of images in a grid layout using CSS flexbox. It features a header section with a title and a gallery section displaying multiple images.

## HTML Structure
- `<header class="header">`: Represents the header section of the web page.
  - `<h1>`: Represents the title of the gallery.

- `<div class="gallery">`: Contains a collection of images displayed in a flexbox grid.
  - `<img>`: Displays individual images within the gallery.

## CSS Styles

### Global Styles
- `*`: Sets the box-sizing property to border-box for all elements.
- `body`: Defines the background color and font for the entire page.

### `.header` Selector:
- `text-align: center;`: Centers text content horizontally within the header.
- `text-transform: uppercase;`: Converts text to uppercase for styling.
- `padding: 32px;`: Adds padding to the header.
- `background-color: #0a0a23;`: Sets the background color of the header.
- `color: #fff;`: Defines the text color in the header.
- `border-bottom: 4px solid #fdb347;`: Adds a colored border at the bottom of the header.

### `.gallery` Selector:
- `display: flex;`: Utilizes flex layout for content alignment.
- `flex-direction: row;`: Arranges items horizontally.
- `flex-wrap: wrap;`: Allows items to wrap to the next row when there's not enough space.
- `justify-content: center;`: Centers content horizontally.
- `align-items: center;`: Centers content vertically.
- `gap: 16px;`: Adds spacing between gallery items.
- `max-width: 1400px;`: Sets the maximum width for the gallery.
- `margin: 0 auto;`: Centers the gallery horizontally.
- `padding: 20px 10px;`: Adds padding around the gallery.

### `.gallery img` Selector:
- `width: 100%;`: Ensures images take up the full width within their containers.
- `max-width: 350px;`: Sets the maximum width for individual images.
- `height: 300px;`: Specifies a fixed height for images.
- `object-fit: cover;`: Ensures images maintain aspect ratio while covering the entire container.
- `border-radius: 10px;`: Adds rounded corners to images.
