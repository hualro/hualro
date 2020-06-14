# hualro
The project is a simple web site that includes common pages, I will list below the requirements text and I will give pointers as to where to find the answers or solutions.
## Requirements
A) Your website must contain at least four different .html pages, and it should be possible to get from any page on your website to any other page by following one or more hyperlinks.
```
index.html
about.html
blog.html
contact.html
```
B) Your website must include at least one list (ordered or unordered), at least one table, and at least one image.
```
<ul> found in all pages, the menu is an <ul> element. There is another <ul> in about.html
<table> found in about.html
<img> found in about.html
```
C) Your website must have at least one stylesheet file.
```
style.css
```
D) Your stylesheet(s) must use at least five different CSS properties, and at least five different types of CSS selectors. You must use the #id selector at least once, and the .class selector at least once.
```
the file style.css contains all of the above, there is a class selector named 'space' and ID selector named 'profile' and 'mobile-screen'
```
E) Your stylesheet(s) must include at least one mobile-responsive @media query, such that something about the styling changes for smaller screens.
```
There is a media query that shows a message on the index.html file if the screen is small but it is not shown on wider screens.
the component is a bootstrap alert.
```
F) You must use Bootstrap 4 on your website, taking advantage of at least one Bootstrap component, and using at least two Bootstrap columns for layout purposes using Bootstrap’s grid model.
```
The index.html shows an alert component if the screen is small.
The blog.html contains a button that is part of bootstrap's components.
The contact.html page has more bootstrap columns, one is fixed and the other will flow down if the screen gets smaller. There's also fake links to social media that are columns showing the grid system.
```
G) Your stylesheets must use at least one SCSS variable, at least one example of SCSS nesting, and at least one use of SCSS inheritance.
```
In the style.scss there is one <table> element that shows a color variable, it has nesting and inheritance all demonstrated for the same table.
```

## Other Info
The text in the blog has a selector that when the text is highlighted/selected it will show it in a different color.
The print button will open up the print dialog and I demonstrate the media query usage because the menu and button are not shown for printing.
