# Mini-Calender-js
# Hosted Link:-
https://github.com/Tulasidurga1/Mini-Calender-js
# explanation:-
### HTML (index.html):

The HTML file defines the structure of the webpage.
Inside the <body> element, there's a <div> with the class "calendar-container." This <div> represents the container for the mini-calendar.
Inside the "calendar-container," there are several <p> elements with specific classes. These <p> elements will display the month name, day name, day number, and year.
CSS (style.css):

- The CSS file defines the styles for the webpage.

# The <body> styling:

- Sets the margin to 0 to remove any default margins.
- Uses flexbox to center the content both horizontally and vertically within the viewport.
- Applies a cursive font and sets the background color to slateblue.
- The "calendar-container" styling:

1. Sets the background color to white, creating a white box for the calendar.
2. Defines a fixed width of 300px for the container.
3. Applies text alignment to the center.
4. Adds rounded corners with a border-radius of 10px.
5. Provides a box shadow for a subtle 3D effect.
6. Uses overflow: hidden to ensure content inside the container doesn't overflow.
- Styling for individual elements within the container:

- "month-name" styles the month name with a bold, large font and a background color of orangered.
- "day-name" styles the day name with a slightly smaller font and dark gray color.
- "day-number" styles the day number with a very large, bold font.
- "year" styles the year with a smaller font size and dark gray color.
### JavaScript (index.js):

- JavaScript code dynamically updates the content of the calendar elements based on the current date.
- It gets references to the HTML elements with specific IDs (e.g., "month-name," "day-name," etc.).
- Then, it creates a JavaScript Date object to obtain the current date and time.
- Using the toLocaleString method, it formats and sets the month name, day name, day number, and year within the corresponding HTML elements.
