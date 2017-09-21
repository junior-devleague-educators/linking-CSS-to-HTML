# linking-CSS-to-HTML
[Beginner] HTML, CSS - Visuals Linking CSS File to HTML File

## What is CSS?
CSS stands for Cascading Style Sheets. It's a language that helps change the style of our HTML page.<br>
![alt text](https://i.imgur.com/pcyc05I.png "HTML without CSS and HTML and CSS")

The image on the left shows a website with no CSS, while the image on the right shows a website that has styling with CSS.<br> 

## HTML & CSS
In order to apply styles to the HTML file, we need to place the `<link>` element within the `<head>` element to link both the HTML & CSS files together. <br>

Add this `<link>` directly below our `<title>`:<br>

![alt text](https://i.imgur.com/cJFMxkN.png "adding link element in header")

As you can see we have 3 important *attributes* to include within this self closing element. The first *attribute* , `type` tells the browser what type of content we are linking. We will use `text/css` file.<br>

The second attribute `rel` tells the browser what the relationship is between the HTML and the linked document. In this case, the CSS document is a `stylesheet`.<br>

Finally, we have `href` which tells the browser where to find our CSS file in our computer directory.<br> 

If everything is linked correctly, your styles will show on the page when you refresh it.<br> 

![alt text](https://i.imgur.com/7IXMNtA.png "Linked and Unlinked HTML & CSS")

## Resources
https://www.w3schools.com/tags/tag_link.asp<br>
