<h1>Building a document scanner in OpenCV</h1><br>
<h2>All you have to do is:</h2><br>
1. Detect edges.
2. Use the edges in the image to find the contour (outline) representing the piece of paper being scanned.
3. Apply a perspective transform to obtain the top-down view of the document.