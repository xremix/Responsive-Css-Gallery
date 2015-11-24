# responsive-css-gallery
Samples for a Web Gallery based on different approaches (Flexbox, CSS3 Column, Bootstrap, etc.)

##Status
`WIP`

- [ ] Basic HTML
- [ ] CSS3 Flexbox
- [x] CSS3 Column
- [x] Bootstrap Basic
- [ ] *Bootstrap Advanced*

##Goal
I strugled with most available Masorny Galleries I could find beacuse I wanted a **lightweight**, **responsive**, **CSS-only** gallery that I can customize from it's styling.
The gallery should work on **comon browsers**, have a meaningful **order** as this could be important for some and just **look high-value** and **clean** without having any unnecessary animations or gaps between the images.
I decided for showing the images in columns - rows would also be better but this seems to be impossible with plane CSS but that also could make portrait images look small and nonrelevant.
Also I took a look at other web galleries out and how they display the single images. My personal favorite yet is Flickr as it is exactly what I am searching for.


Click [here](https://raw.githubusercontent.com/xremix/Responsive-Css-Gallery/master/Ascii%20Demonstration) to see an example what my goal is


##Results

###Basic HTML
`WIP`

Pros
- Browser support
- Correct order
- Small overhead

Downs
- Ugly as hell

###CSS3 Flexbox
`WIP`

Pros
- Correct order on Desktop

Downs
- Gaps everywhere
- **Currently** no breakpoints - Always 3 fluid columns
- *Many Vendor prefixes*

[Browser Support](http://caniuse.com/#search=flexbox)

###CSS3 Column
`WIP`

Pros
- Responsive
- No Gaps
- Allows fluid and responsive layouts

Cons
- Order of images is correct on mobile but not correct on desktop

[Browser Support](http://caniuse.com/#feat=multicolumn)

###Bootstrap Basic
`WIP`

Pros
- Responsive and fluid possible
- No Gaps

Cons
- Huge overhead if Bootstrap is not required for the site
- Wrong order on mobile
- Loops (backend or js) needed to put the images in the 3 rows

###Bootstrap Advanced
`WIP`

##Conclusion
`WIP`

##JS Competitors

###Justified Gallery
This looks pretty much what I was looking for, even a row style, but of course has a lot of JS and CSS on top.