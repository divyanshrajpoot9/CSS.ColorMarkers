# CSS.ColorMarkers

# Hosted File Link: https://divyanshrajpoot9.github.io/CSS.ColorMarkers/

## Here are the details of the HTML tags used in the provided code:

### 1. <!DOCTYPE html>: This declaration defines the document type and version of HTML being used, which is HTML5 in this case.

### 2. `<html lang="en">`: This is the opening tag for the HTML document. The `lang` attribute specifies the language of the document, which is set to "en" for English.

### 3. `<head>`: This element contains metadata about the document, such as character encoding, viewport settings, and the document title.

  #### - `<meta charset="UTF-8">`: Specifies the character encoding for the document as UTF-8, which supports a wide range of characters and symbols.

 #### - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Defines the viewport settings for responsive web design. It ensures that the content fits the width of the device and starts with an initial scale of 1.0.

 #### - `<title>Colored Markers</title>`: Sets the title of the HTML document, which is displayed in the browser's title bar or tab.

 ####  - `<link rel="stylesheet" href="style.css">`: Links an external CSS stylesheet (`style.css`) to the HTML document, allowing you to apply styles to the content.

### 4. `<body>`: This element contains the visible content of the web page.

 ####   - `<h1>`: Defines a top-level heading with the text "CSS Color Markers."

  ####  - `<div class="container">`: Creates a container element to group and style the marker elements.

  ####    - `<div class="marker red">`: Defines a marker element with the class "red."

   ####      - `<div class="cap">`: Represents the cap or top part of the red marker.

 ####       - `<div class="sleeve">`: Represents the main body or sleeve of the red marker.

 ####     - `<div class="marker green">`: Similar to the red marker, but with the class "green."

  ####      - `<div class="cap">`: Represents the cap or top part of the green marker.

 ####       - `<div class="sleeve">`: Represents the main body or sleeve of the green marker.

 ####     - `<div class="marker blue">`: Similar to the previous markers, but with the class "blue."

 ####       - `<div class="cap">`: Represents the cap or top part of the blue marker.

  ####      - `<div class="sleeve">`: Represents the main body or sleeve of the blue marker.

## Here's a description of the CSS attributes used in the provided CSS code for the HTML page:

  ###  1. `*` (Universal Selector):
   - `margin: 0px;`: Sets the margin for all elements to 0 pixels, effectively removing any default margins.
   - `padding: 0px;`: Sets the padding for all elements to 0 pixels, removing default padding.
   - `box-sizing: border-box;`: Specifies the box-sizing model as "border-box," which includes padding and border within the element's total width and height.

  ###  2. `h1` (Selector for `<h1>` element):
   - `text-align: center;`: Centers the text within `<h1>` elements horizontally.

  ###  3. `.container` (Selector for elements with class "container"):
   - `background-color: rgb(255, 255, 255);`: Sets the background color of elements with the class "container" to white (RGB color).
   - `padding: 10px 0;`: Adds 10 pixels of padding to the top and bottom of elements with the class "container" and no padding to the left and right.

  ###  4. `.marker` (Selector for elements with class "marker"):
   - `width: 200px;`: Sets the width of elements with the class "marker" to 200 pixels.
   - `height: 25px;`: Sets the height of elements with the class "marker" to 25 pixels.
   - `margin: 10px auto;`: Adds a 10-pixel margin to the top and bottom and automatically centers the element horizontally.

  ### 5. `.cap` (Selector for elements with class "cap"):
   - `width: 60px;`: Sets the width of elements with the class "cap" to 60 pixels.
   - `height: 25px;`: Sets the height of elements with the class "cap" to 25 pixels.

  ### 6. `.sleeve` (Selector for elements with class "sleeve"):
   - `width: 110px;`: Sets the width of elements with the class "sleeve" to 110 pixels.
   - `height: 25px;`: Sets the height of elements with the class "sleeve" to 25 pixels.
   - `background-color: rgba(255, 255, 255, 0.5);`: Sets the background color of elements with the class "sleeve" to a semi-transparent white (RGBA color).
   - `border-left: 10px double rgba(0, 0, 0, 0.75);`: Adds a double border of 10 pixels to the left side of elements with the class "sleeve," using a semi-transparent black border color.

  ### 7. `.cap, .sleeve` (Selectors for elements with classes "cap" and "sleeve"):
   - `display: inline-block;`: Sets the display property of elements with classes "cap" and "sleeve" to inline-block, allowing them to appear next to each other horizontally.

  ### 8. `.red` (Selector for elements with class "red"):
   - `background: linear-gradient(rgb(122, 74, 14), rgb(245, 62, 113), rgb(162, 27, 27));`: Sets a linear gradient background for elements with the class "red," transitioning from brown to pink to dark red.
   - `box-shadow: 0 0 20px 0 rgba(83, 14, 14, 0.8);`: Adds a box shadow with a red tint to elements with the class "red."

  ### 9. `.green` (Selector for elements with class "green"):
   - `background: linear-gradient(#55680D, #71F53E, #116C31);`: Sets a linear gradient background for elements with the class "green," transitioning from dark green to light green to dark green.
   - `box-shadow: 0 0 20px 0 #3B7E20CC;`: Adds a box shadow to elements with the class "green," with a green tint.

  ### 10. `.blue` (Selector for elements with class "blue"):
    - `background: linear-gradient(hsl(186, 76%, 16%), hsl(223, 90%, 60%), hsl(240, 56%, 42%));`: Sets a linear gradient background for elements with the class "blue," transitioning between different shades of blue using HSL values.
    - `box-shadow: 0 0 20px 0 hsla(223, 59%, 31%, 0.8);`: Adds a box shadow to elements with the class "blue" using HSLA values, which includes alpha (opacity) information.

![Screenshot 2023-09-06 155154](https://github.com/divyanshrajpoot9/CSS.ColorMarkers/assets/114856467/9c73adfc-c4bd-4b1c-93ff-96ef40fd8256)
![Screenshot 2023-09-06 155207](https://github.com/divyanshrajpoot9/CSS.ColorMarkers/assets/114856467/66d121ef-1f17-4825-af6a-57482bdbabc6)
![Screenshot 2023-09-06 155224](https://github.com/divyanshrajpoot9/CSS.ColorMarkers/assets/114856467/0fda2a53-ff8c-4f6a-979c-cf49106f3b04)
