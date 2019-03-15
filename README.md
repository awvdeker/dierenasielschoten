# dierenasielschoten

My client wants me to improve his website: www.dierenasielschoten.be

The website is about the animal shelter in Schoten. The lay-out of the site is bad. There is an ugly background. Pictures and links are spread all over the place. An h1 in italics and with different font-sizes. Unmatching font-colors. The navbar is constructed by using the outdated 'frameset' and 'frame' elements: the navbar is a new html-page loaded at the left side of the homepage.

The client wants his site to be something different, something more modern. 

I suggested a simple design with one big background image of a dog and to keep the navbar at the left side of the screen so the visitor still recognizes the layout of the site. The homepage should have a centered heading and below the links for adoption of cats and dogs and the e-mail inks. At the bottom left the ad of Zooplus. The contactpage as well as the sponsorshippage should stay more or less the same but nicely styled and the content corrected.  

The client agreed on my suggestions and he liked the mockup I made. Then I started working on the code.

I constructed a navbar without a frame, with bootstrap. In HTML: an unordered list with class "nav" and a listed item with class "nav-item" and a link with class "nav-link". I made 3 pages: homepage, contact-page and sponsorship-page and they are linked to eachother by the navbar. Each page corresponds to one file: index.html, contact.html and petermeter.html. 

In each page there is a link to a corresponding .css file: style.css, stylecontact.css and stylepetermeter.css. The 3 pages have the same background, a big picture of a dog. The background-pictures takes the whole viewport. All the text is in white as a contrast. In the CSS: with position relative I create the heading "DIERENASIEL SCHOTEN". The navbar, the links for adoption and the email links are placed around the heading with positon absolute. At the homepage only I put the Zooplus add on the left bottom corner. I included a favicon.ico file in the root folder of the site.

The site is not fully responsive but it is still readable on mobile screens.

I worked 5 days on it or around 40 hours.

The site is published at:

https://awvdeker.github.io/dierenasielschoten/
