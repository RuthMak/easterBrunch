Heading:
•	Inside <h1> tag, I used a display-4 Bootstrap class on the main heading to make it responsive and large. It is responsive to screen sizes and centers the heading using text-center and text-primary for the color it has.
Styling:
•	Using mb-3 and mb-4 provides spacing between columns and rows. I used Bootstrap’s grid system to automatically adjust layout depending on device width. 
•	I added a custom style block in the <head> so that there’s consistency with the font, padding, and background.
Container and Grid:
•	Inside the div with the class container, I wrapped all content inside so that the layout is spaced consistently across devices. This makes sure the content does not stretch the full width like container-fluid but still keeps responsive.
•	The layout includes two main rows (<div class="row">). Each row contains at least two columns, using responsive column classes such as col-md-6 and col-lg-4.
Row 1:
•	This has two columns that uses col-md-6, which means they display side-by-side on medium screens (≥768px) and stack vertically on smaller screens.
Row 2:
•	This row has three columns. I used col-lg-4 col-md-6 on two columns and col-lg-4 col-md-12 on the third. This design allows for different responsive behavior:
o	On large screens (≥992px), all 3 columns stay in one row equally.
o	On medium screens (≥768px and <992px), the first two stack two per row, and the last column spans the full width.
o	On small screens, all columns stack vertically.
Images and Content:
•	I styled each column to have an image using the class meal-img. It is also responsive and has round corners.
•	Under each image is a course title and a short description of the recipe.
