# UI Portfolio Website

This project is a portfolio website designed to showcase the skills, services, and projects of a web developer and UI designer. Below is a detailed explanation of the structure and functionality of the code.

---

## Table of Contents
1. [Overview](#overview)
2. [File Structure](#file-structure)
3. [Code Explanation](#code-explanation)
   - [HTML Structure](#html-structure)
   - [CSS Styling](#css-styling)
   - [Media Queries](#media-queries)
   - [Sections](#sections)
4. [How to Use](#how-to-use)

---

## Overview

The website is a responsive portfolio that includes:
- A hero section introducing the developer.
- A biography section.
- A services section.
- A skills section.
- A portfolio section showcasing projects.
- A footer with contact details and social media links.

---

## File Structure

---

## Code Explanation

### HTML Structure

The main file is [`vki.html`](c:/Users/LENOVO/Documents/web_dev_project/projectweb/vki.html), which contains the following sections:

1. **Head Section**:
   - Includes metadata for the website.
   - Links to the Bootstrap CSS framework for styling.
   - Contains custom CSS styles defined in a `<style>` tag.

2. **Hero Section**:
   - Introduces the developer with a title, description, and call-to-action buttons.
   - Includes a fixed header with navigation links and a logo.

3. **Biography Section**:
   - Displays the developer's biography, including name, email, location, and phone number.
   - Includes social media links for easy connection.

4. **Services Section**:
   - Highlights the services offered, such as web development, app development, and photography.
   - Each service is represented with an image, title, and description.

5. **Skills Section**:
   - Showcases the developer's skills with progress bars indicating proficiency levels.
   - Includes images and descriptions for branding and strategy.

6. **Portfolio Section**:
   - Displays a featured project and additional portfolio images.

7. **Footer**:
   - Contains contact information and social media links.
   - Includes copyright information.

---

### CSS Styling

Custom styles are defined within the `<style>` tag in the `<head>` section:
- **Global Styles**:
  - Sets the font family and removes default margins.
- **Hero Section**:
  - Uses a dark background with white text.
  - Adds padding for spacing.
- **Service Boxes**:
  - Styled with a light background, padding, and rounded corners.
- **Footer**:
  - Styled with a dark background and centered text.

---

### Media Queries

The website is responsive, with media queries defined for:
- **Screens smaller than 768px**:
  - Adjusts the header layout to stack vertically.
  - Reduces padding in the hero section.
- **Screens smaller than 576px**:
  - Reduces font sizes and button padding for better readability.

---

### Sections

1. **Fixed Sidebar**:
   - Contains quick action buttons for navigation (Back, Forward, Download, Buy).
   - Positioned on the right side of the screen.

2. **Hero Section**:
   - Displays the developer's name, title, and a call-to-action button linking to [`inex.html`](c:/Users/LENOVO/Documents/web_dev_project/projectweb/inex.html).

3. **Biography Section**:
   - Includes an image and a detailed description of the developer's background.

4. **Services Section**:
   - Highlights three main services with images and descriptions.

5. **Skills Section**:
   - Displays skill levels using progress bars.

6. **Portfolio Section**:
   - Features a project image and additional portfolio work.

7. **Footer**:
   - Provides contact details and social media links.

---
## WhatsApp Integration (`inex.html`)

The `inex.html` file includes a direct link to WhatsApp for communication. When users click the "Hire Me" button in the hero section or biography section, they are redirected to `inex.html`, which contains a WhatsApp link formatted as:

```html
<a href="https://wa.me/<phone_number>?text=Hello%20John%20Watson,%20I%20am%20interested%20in%20your%20services.">
  Chat on WhatsApp
</a>

## How to Use

1. Open the `vki.html` file in a browser to view the portfolio website.
2. Navigate through the sections using the header links or scroll down.
3. Use the "Hire Me" button to navigate to the contact form in [`inex.html`](c:/Users/LENOVO/Documents/web_dev_project/projectweb/inex.html).
4. Explore the portfolio and services offered.

---

## Notes

- Ensure all images are placed in the correct directory (`images/`) for proper rendering.
- The website uses Bootstrap for responsive design and custom CSS for additional styling.
- Modify the contact details and social media links in the footer to personalize the website.

---

## Author

This portfolio was created by John Watson, a web developer and UI designer based in the UK.