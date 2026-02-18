# bbno$ Fan Site

A personal fan site built for my Web Development course (CIT 484) at CSUN. The site is about the Canadian rapper bbno$ and covers his discography, biography, tour dates, and a photo gallery.

## About the Project

This project was built using only HTML and CSS, no frameworks or libraries. The goal was to practice writing clean, well-structured HTML and CSS from scratch while building something around a topic I actually care about.

The site has 4 pages and 1 shared stylesheet:

- index.html - Home page with a brief intro and highlights
- discography.html - Studio albums and notable singles with tracklists
- about.html - Bio and quick facts about the artist
- tour.html - Tour dates displayed in a table
- gallery.html - Photo gallery with captions and expandable info
- style.css - Shared stylesheet used across all pages

## MDN Elements and Attributes

As part of the assignment I had to find 3 HTML elements and 3 attributes from MDN that were not covered in lecture and use them in a practical way.

**Elements:**

1. `<dl>`, `<dt>`, `<dd>` - Definition list used on the About page to display artist facts in a structured key/value format. Source: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dl

2. `<figure>` and `<figcaption>` - Used in the Gallery page to wrap each photo with a semantic caption linked to the image. Source: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/figure

3. `<details>` and `<summary>` - Used in the Gallery page as a native toggle to show and hide extra photo info without any JavaScript. Source: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/details

**Attributes:**

1. `scope="col"` on `<th>` - Used in the Tour page table to explicitly associate header cells with their columns, which improves accessibility for screen readers. Source: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/th#scope

2. `caption-side` CSS property - Used on the Tour page to position the table caption above the table. Source: https://developer.mozilla.org/en-US/docs/Web/CSS/caption-side

3. `loading="lazy"` on `<img>` - Used on Gallery page images to defer loading until the user scrolls near them, which improves page performance. Source: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img#loading

## Course Info

- Course: COMP 484/L - Web Engineering I 
- School: California State University, Northridge  
- Semester: Spring 2026
