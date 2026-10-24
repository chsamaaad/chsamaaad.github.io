# Front-End Development - CA1 Portfolio & Exercises

**Student Name:** Abdul Samad  
**Student ID:** 77951  
**Group:** BSC20926A  
**Lecturer:** Brendan Munnelly  
**College:** Dorset College Dublin (2025-26)

## About This Repository

This repository holds my web pages and class exercises for Continuous Assessment 1 (CA1). It includes a main home page (`index.html`) that links out to the individual HTML, CSS, and TailwindCSS exercises located in the `/exercises` folder.

## Folder Structure

* `index.html` - Home page with my bio, custom favicon, developer image, and links to all exercises.
* `assets/img/` - Favicon files (`favicon-16x16.png`, `favicon-32x32.png`, `apple-touch-icon.png`, `site.webmanifest`) and home page image.
* `exercises/` - All completed tutorial web pages (`page-1.html` to `page-5.html` and the three hero block pages).
* `exercises/assets/css/` - Stylesheets for the image, typography, and hero block exercises (`style-4.css`, `style-5.css`, `hero-text.css`, `hero-image.css`, `hero-video.css`).
* `exercises/assets/img/` - Image files used in the Van Gogh, Irish Tourism, and hero image pages.
* `exercises/assets/videos/` - Background video (`hero-video.mp4`) and poster image (`hero-still.jpg`) for the video hero block.

## Completed Exercises

| File | Topic | Notes on What I Did |
| :--- | :--- | :--- |
| `index.html` | Home Page | Added semantic layout tags, TailwindCSS styling, custom favicon in `<head>`, and links to all exercise files. |
| `exercises/page-1.html` | A Tale of Two Cities | Marked up plain text with headings, paragraphs, bold/italic tags, semantic containers, and warm Tailwind colours. |
| `exercises/page-2.html` | Purple Rain | Used HTMLHint to find and fix the 5 broken/unclosed HTML tags, then added responsive padding and purple theme colours. |
| `exercises/page-3.html` | Web Page with Sections | Created 6 `<section>` blocks with Lorem Ipsum text and styled each section with different accessible Tailwind background and text classes. |
| `exercises/page-4.html` | Vincent van Gogh | Added the four painting images with drop shadows, external museum links (`target="_blank" rel="noopener"`), link hover states, and the Merriweather Google Font. |
| `exercises/page-5.html` | Irish Tourism | Added the five attraction photos with rounded corners, internal page navigation links (`#guinness`, `#top-of-page`, etc.) with smooth scrolling, and Oswald + Lato Google Fonts. |
| `exercises/hero-text.html` | Hero Block with Text | Built a full-width hero header with a blue gradient background and Animista `slide-in-top` / `slide-in-left` keyframe animations. |
| `exercises/hero-image.html` | Hero Block with Image | Added `business.jpg` as a background image with a dark overlay (`bg-overlay`), `text-shadow`, and image preloading in the `<head>`. |
| `exercises/hero-video.html` | Hero Block with Video | Replaced the static image with a muted looping background video (`hero-video.mp4`), poster image (`hero-still.jpg`), and a blue-to-rose gradient overlay. |

## Running Locally

Open `index.html` in any web browser (such as Chrome, Firefox Developer Edition, or Brave), or use the Live Server extension in VS Code to preview the pages and test the relative links.
