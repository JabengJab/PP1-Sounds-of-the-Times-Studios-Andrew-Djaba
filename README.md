# Sounds of the Times Studios Website

![Sounds of the Times Studios Logo](assets/images/logo.PNG)

A responsive, accessible website for Sounds of the Times Studios in Leipzig, featuring Home (About Us), Media, and Contact sections.

Visit the deployed site: [Sounds of the Times Studios](https://jabengjab.github.io/PP1-Sounds-of-the-Times-Studios-Andrew-Djaba/)

## CONTENTS

- [Features](#features)
  - [Three Main Pages](#three-main-pages)
  - [Responsive Design](#responsive-design)
  - [Accessibility Compliant](#accessibility-compliant)
  - [Social Media Integration](#social-media-integration)
  - [Modern UI](#modern-ui)
- [Technologies Used](#technologies-used)
- [File Structure](#file-structure)
- [Accessibility Features](#accessibility-features)
- [Responsive Design](#responsive-design)
- [UX Principles](#ux-principles)
- [Maintainability](#maintainability)
- [Performance](#performance)
- [Installation](#installation)
- [Customization](#customization)
  - [Images](#images)
  - [Colors](#colors)
- [Social Media Links](#social-media-links)
- [Browser Support](#browser-support)
- [Testing](#testing)
- [Credits](#credits)

  - [Media](#media)

  ## Features

- **Three Main Pages**:

  - Home/About Us
  - Media Gallery
  - Contact Page

  ## Design

  - Home
    ![Home](assets/images/balsamiq_homepage.PNG)
    Link to wireframes for Home on : [balsamiq](https://balsamiq.cloud/sl2q3sz/pveikvd/r2278)

  - Media
    ![Media](assets/images/balsamiq_media.PNG)
    Link to wireframes Media on : [balsamiq](https://balsamiq.cloud/sl2q3sz/pveikvd/rBB0E)

  - Contact
    ![Contact](assets/images/balsamiq_contact.PNG)
    Link to wireframes Contact on : [balsamiq](https://balsamiq.cloud/sl2q3sz/pveikvd/r682F)

- **Responsive Design**: Works on all device sizes
- **Accessibility Compliant**:
  - WCAG 2.1 AA standards
  - Keyboard navigation
  - Screen reader friendly
- **Social Media Integration**: Links to Facebook, Instagram, X (Twitter), and YouTube
- **Modern UI**:
  - Clean, professional design
  - Interactive elements
  - Optimized media display

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**:
  - Flexbox/Grid layouts
  - CSS variables
  - Responsive design
  - Modern CSS Reset by [Andy Bell](https://gist.github.com/Asjas/4b0736108d56197fce0ec9068145b421)
- **Font Awesome**: For icons

## File Structure

sounds-of-the-times/

├── index.html # Homepage (About Us)

├── media.html # Media Gallery

├── contact.html # Contact Page

└── assets/

    ├── css/

       ├── reset.css # CSS reset/normalization

       ├── styles.css # Main styles


    ├── favicon/ All favicons

    ├── images/  All website images

    ├── audio/   Audio samples

├── Readme.md/ Readme document

## Accessibility Features

- Semantic HTML5 structure
- ARIA attributes for interactive elements
- Skip to content link
- Proper heading hierarchy
- High contrast color scheme
- Alt text for all images
- Keyboard navigable interface

## Responsive Design:

- Mobile-first approach

- Flexible grid layouts

- Responsive typography

- Mobile navigation toggle

- Adapts to all screen sizes

## UX Principles:

- Clear information hierarchy

- Consistent navigation

- Visual feedback for interactions

- Readable typography

- Logical content organization

## Maintainability:

- Well-organized file structure

- CSS variables for easy theming

- Modular component-based design

- Comprehensive comments

- Consistent naming conventions

## Performance:

- Optimized assets

- Efficient CSS with minimal redundancy

- Responsive images

- Lazy loading for iframes

This implementation provides a complete, professional website for Sounds

## Installation

No installation required - this is a static website. Simply open `index.html` in any modern web browser.

## Customization

To customize the website:

1. **Images**:

   - The band-recording image was taken from - https://www.vecteezy.com/photo/33879669-interior-of-a-music-studio-with-guitar-piano-and-chair-indoor-recording-studio-with-guitars-amps-and-pianos-ai-generated

   - The hero image was taken from - https://www.vecteezy.com/photo/36053483-ai-generated-a-professional-music-studio-with-a-large-mixing-console-computer-monitors-and-studio-monitors

   - The logo was created with Looka - https://looka.com/editor/222956077

   - The mastering image was taken from - https://www.vecteezy.com/photo/36053483-ai-generated-a-professional-music-studio-with-a-large-mixing-console-computer-monitors-and-studio-monitors

   - The analog-mixing image was taken from - https://www.vecteezy.com/photo/24711148-hand-adjusting-sound-mixer-knob-in-recording-studio-generated-by-ai

   - The playback image was taken from - https://www.vecteezy.com/photo/34430800-audio-recording-studio-with-professional-audio-equipment-close-up-view-shot-of-a-modern-music-record-studio-control-desk-with-computer-screen-show-user-interface-of-daw-software-ai-generated

   - The sound-design image was taken from - https://www.vecteezy.com/photo/53789631-energy-and-sound-collide-as-speaker-unleashes-powerful-vibration-effect-on-surface

   - The studio image was taken from - https://www.vecteezy.com/photo/36053483-ai-generated-a-professional-music-studio-with-a-large-mixing-console-computer-monitors-and-studio-monitors

   - The vocals image was taken from - https://www.vecteezy.com/photo/29633346-skillful-male-singer-with-eyes-closed-in-casual-clothes-with-headphones-and-music-recorded-on-laptop-in-modern-lighting-studio-with-professional-microphone

2. **Colors**:
   - Modify CSS variables in `styles.css`:
   ```css
   :root {
     --primary-color: #2a2d43;
     --secondary-color: #4a6fa5;
     --accent-color: #ff7e5f;
     /* ... */
   }
   ```

## Social Media Links:

- Update in all footers :
  <a href="https://youtube.com/yourpage">facebook</a> , <a href="https://facebook.com/yourpage">YouTube</a>, <a href="https://twitter.com/yourpage">twitter</a>, <a href="https://instagram.com/yourpage">Instagram</a>

## Browser Support

- Chrome (latest)

- Firefox (latest)

- Safari (latest)

- Edge (latest)

- Mobile Safari/Chrome

# Testing

![Sounds of the Times Studios site shown on multiple screen sizes](assets/images/bytes.PNG)

---

## CONTENTS

- [AUTOMATED TESTING](#AUTOMATED-TESTING)
  - [W3C Validator](#W3C-Validator)
  - [Lighthouse](#Lighthouse)
- [FULL TESTING](#FULL-TESTING)

---

## AUTOMATED TESTING

### W3C Validator

[W3C](https://validator.w3.org/) was used to validate the HTML on all pages of the website. It was also used to validate the CSS.

- [Index Page W3C HTML Validation](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjabengjab.github.io%2FPP1-Sounds-of-the-Times-Studios-Andrew-Djaba%2Findex.html) - Pass

- [Media Page W3C HTML Validation](https://validator.w3.org/nu/?showsource=yes&doc=https%3A%2F%2Fjabengjab.github.io%2FPP1-Sounds-of-the-Times-Studios-Andrew-Djaba%2Fmedia.html) - Pass

- [Contact Page W3C HTML Validation](https://validator.w3.org/nu/?showsource=yes&doc=https%3A%2F%2Fjabengjab.github.io%2FPP1-Sounds-of-the-Times-Studios-Andrew-Djaba%2Fcontact.html) - Pass

- Style.css Validation - Pass
  ![style.css CSS Validation](assets/images/style_css_wc3.PNG)

### Lighthouse

I used Lighthouse within the Chrome Developer Tools to test the performance, accessibility, best practices and SEO of the website.

- Index Page
  ![Index Page lighthouse testing desktop](assets/images/lighthouse_index.PNG)

- Index Page
  ![Index Page lighthouse testing desktop](assets/images/lighthouse_media.PNG)

- Index Page
  ![Index Page lighthouse testing desktop](assets/images/lighthouse_contact.PNG)

## Full Testing

Full testing was performed on the following devices:

- Laptop:
  - Lenovo Legion 17 inch screen
- Mobile Devices:
  - iPhone 12 pro.
  - iPhone 11 pro.
  - Samsung Galaxy S7.

## Credits

### Media

- All images used were taken from [Vecteezy](https://www.vecteezy.com/)
- Logo was created by me at [Looka](https://looka.com/)
- Font Awesome for icons
- Modern CSS reset by [Andy Bell](https://gist.github.com/Asjas/4b0736108d56197fce0ec9068145b421)
- Wireframes [Balsamiq](https://balsamiq.com/)
