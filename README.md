# Gira Sol Music Website

Website for Gira Sol, a bossa nova, jazz & pop music trio featuring Tobias, Helena, and Elias.

## Setup

### Prerequisites
- Hugo (extended version recommended)

### Running Locally

```bash
hugo server
```

Visit `http://localhost:1313` in your browser.

## Content Structure

- `content/`: Page content (home, booking, gallery, setlist, upcoming events)
- `layouts/`: HTML templates
- `static/`: Images and stylesheets
- `i18n/`: Translations (German, English, Portuguese)

## TODO for Gira Sol

- [ ] Add trio photo to `static/img/trio.jpg` (currently using placeholder)
- [ ] Add gallery photos to `static/img/gallery/` (currently empty)
- [ ] Add setlist items to `content/setlist/` (currently empty)
- [ ] Add upcoming events to `content/upcoming-events/` (currently empty)
- [ ] Set up domain and GitHub Pages deployment
- [ ] Update CNAME file with actual domain

## Site Features

- Multilingual support (German, English, Portuguese)
- Responsive design
- Image gallery with lightbox
- Event carousel
- Booking form
- Mobile-friendly navigation

## Building for Production

```bash
hugo build
```

Output will be in the `public/` directory.

## Contact

- Email: girasolmusic.band@gmail.com
- Instagram: @music.girasol
- Phone: +41 76 322 73 28 
