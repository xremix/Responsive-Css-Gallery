# responsive-css-gallery
Samples for a Web Gallery based on different approaches

##Status
`WIP`

- [x] Basic HTML
- [x] CSS3 Flexbox
- [x] CSS3 Column
- [x] Bootstrap
- [x] JS Gallery

##Goal
I strugled with most available Masorny Galleries I could find beacuse I wanted a **lightweight**, **responsive**, **CSS-only** gallery that I can customize from it's styling.
The gallery should work on **comon browsers**, have a meaningful **order** and just **look high-value** and **clean** without having any unnecessary animations or gaps between the images.

There is always the design decition between showing the images in columns or rows. Columns show portait images big, rows show them small but panoramas big. Beautiful rows seem to be impossible with blank CSS.

Also I took a look at other web galleries out and how they display the images. My personal favorite yet is Flickr as it is exactly what I am searching for.


Click [here](https://github.com/xremix/Responsive-Css-Gallery/blob/master/Ascii%20Demonstration.txt) to see an example what my goal is


##Results

###Basic HTML
[Demo](https://rawgit.com/xremix/Responsive-Css-Gallery/master/Basic%20HTML.html)


| Pros | Cons |
| ------------- | ----------- |
| Browser support|Ugly as hell|
| Correct order|       |
| Small overhead|       |


###CSS3 Flexbox
[Demo](https://rawgit.com/xremix/Responsive-Css-Gallery/master/CSS3%20Flexbox.html)


| Pros | Cons |
| ------------- | ----------- |
| Correct oder on Desktop|Gaps everywhere|
| | *Currenty* no breakpoints - always 3 fluid columns|
|  | *Many Vendor prefixes* |

[Browser Support](http://caniuse.com/#search=flexbox)

###CSS3 Column
[Demo](https://rawgit.com/xremix/Responsive-Css-Gallery/master/CSS3%20Column.html)

| Pros | Cons |
| ------------- | ----------- |
| Responsive|Order of images is correct on mobile but wrong on desktop|
| No Gaps|       |
| Allows fluid and responsive layouts|       |



[Browser Support](http://caniuse.com/#feat=multicolumn)

###Bootstrap
[Demo](https://rawgit.com/xremix/Responsive-Css-Gallery/master/Bootstrap%20Basic.html)

| Pros | Cons |
| ------------- | ----------- |
| Responsive and fluid possible|Huge overhead if Bootstrap is not required for the site|
| No gaps | wrong order on mobile|
|  | Images need to be split in 3 different rows |


##JavaScript

###JS Gallery
[Demo](https://rawgit.com/xremix/Responsive-Css-Gallery/master/JS%20Gallery.html)
I wanted to have try a JS Gallery on my own, so I just started with development.

| Pros | Cons |
| ------------- | ----------- |
| Perfect design on every device | JS required |
| Overhead is adquate | jQuery, Underscore is **currently** required |
|  | A lot of work for me :) |

##Conclusion
`WIP`