# Responsive Coffee Shop Website Design

A single-page coffee shop site. It includes a home hero, an about section, a menu, customer reviews, a table booking form, and a footer with branches, links, and contact details.

This design is inspired by the work of [Mr. Web Designer](https://www.youtube.com/@MrWebDesignerAnas). Click [here](https://youtu.be/52sKmRsk7xU) to watch the video.

![preview img](/preview.png)

## How to view

Open `index.html` in a browser. There is no install step and no build step.

Swiper, Font Awesome, and the Poppins font load from CDNs, so an internet connection is needed for icons, the review carousel, and typography.

## Features

- **Navigation.** Links jump to Home, About, Menu, Reviews, and Book. On screens 768px and narrower, a menu button toggles the navigation.
- **Home image switcher.** Clicking a thumbnail in the home slider replaces the main image.
- **Reviews carousel.** Swiper shows one slide on small screens and two from 768px up, with pagination, looping, and autoplay.
- **Booking form.** Name, email, number, and message fields. The form is front-end only and does not send data.
- **Responsive layout.** Type and spacing adjust at 991px, 768px, and 450px in `css/style.css`.

## Project structure

```
index.html          Page markup and section content
css/style.css       Layout, theme, and media queries
js/script.js        Mobile menu, image switcher, and Swiper setup
image/              Photos used by the page
preview.png         Screenshot shown above
```

Images referenced from the page:

- `image/home-img-1.png`, `image/home-img-2.png`, `image/home-img-3.png`
- `image/about-img.png`, `image/about-icon-1.png`, `image/about-icon-2.png`, `image/about-icon-3.png`
- `image/menu-1.png` through `image/menu-6.png`
- `image/pic-1.png` through `image/pic-4.png`
