# gg-comp-challenge-1

### Overview  
The original layout included 7 small square boxes, a header, and a large picture.  As the screen size gets scaled down the boxes become too distorted and so does the image proportions.  This approach used 3 media queries to continuously re-organize the layout in order to maintain an aesthetically pleasing page.

### Media Query 1 @ 980px
A larger, previously disabled header and footer appear to replace the header, and box#7 in order to prevent an issue with widows since there are an odd number of boxes compared to columns for the boxes.

### Media Query 2 @ 780px  
The image joins the row the header is in, and is aligned with one of the boxes which each take up 1/3rd of the page.  The footer button now spans the entire bottom of the page.

### Media Query 3 @ 480px  
The image now becomes a small square that resides next to the h1.  The boxes now fit in a 2 column format.  This is meant to scale down to 320px.


### COMPARISON:
[Original Page](https://github.com/Ggoering/gg-comp-challenge-1/tree/master/photos/origincompSS.png)
[Custom Page with reactivity] (https://ggoering.github.io/gg-comp-challenge-1/)
