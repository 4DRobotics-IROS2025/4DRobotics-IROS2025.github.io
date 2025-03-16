# 4D Scene Understanding for Intelligent Robotics - IROS 2025 Workshop Website

This repository contains the website for the "Advancements for Intelligent Robotics in 4D Scenes: Localization, Reconstruction, Rendering, and Generation" workshop at IROS 2025.

## Website Overview

The website is built with simple HTML, CSS, and minimal JavaScript to ensure compatibility and easy maintenance. The main pages include:

- Overview of the workshop
- Organizers information
- Invited speakers
- Workshop schedule
- Call for papers
- Important dates

## How to Update Content

### Updating Organizer Information

1. Open `index.html`
2. Navigate to the "Organizers" section
3. Each organizer is structured as:
   ```html
   <a href="https://example.com/personal-website">
       <div class="organizer">
           <img src="images/name.png" alt="Person Name" class="profile-img">
           <h3>Person Name</h3>
           <p>Affiliation</p>
       </div>
   </a>
   ```
4. Update the `href` attribute in the outer `<a>` tag with the organizer's personal website URL
5. To add new organizers, copy an existing block and modify all relevant information

### Adding/Replacing Photos

1. Place organizer/speaker photos in the `images/` directory
2. Recommended image specs:
   - Square aspect ratio (1:1)
   - At least 300x300 pixels
   - JPG or PNG format
   - Preferably with the person's face clearly visible
3. Update the corresponding `<img>` tags in the HTML to point to the new images

### Updating Speaker Information

1. Open `index.html`
2. Navigate to the "Invited Speakers" section
3. Each speaker is structured like organizers, with additional information:
   ```html
   <a href="https://example.com/personal-website">
       <div class="speaker">
           <img src="images/name.png" alt="Speaker Name" class="profile-img">
           <h3>Speaker Name</h3>
           <p>Affiliation</p>
           <p><strong>Status: Confirmed</strong></p>
           <p><strong>Topic:</strong> Topic Title</p>
       </div>
   </a>
   ```
4. Update the `href` attribute in the outer `<a>` tag with the speaker's personal or institutional website URL
5. For confirmed speakers, ensure the status shows `<p><strong>Status: Confirmed</strong></p>`

### Updating Schedule

1. Open `index.html`
2. Navigate to the `<table class="schedule-table">` element
3. Modify the `<tr>` elements to update time slots and activities

### Updating Important Dates

1. Open `index.html` 
2. Navigate to the `<table class="dates-table">` element
3. Modify the `<tr>` elements to update dates

### Custom CSS Styling

If you want to modify the website's appearance:

1. Edit the `styles.css` file
2. The website uses CSS variables for colors (defined at the top of the CSS file)
3. Major sections are clearly commented for easy navigation

## Deployment

To deploy this website:

1. Push changes to the GitHub repository
2. The website will be automatically deployed to GitHub Pages
3. The URL will be: https://4DRobotics.github.io

## Local Testing

To test the website locally:

1. Clone this repository
2. Open `index.html` in your web browser
3. No server is required as this is a static site

## Contact

For questions or issues about the website, please contact:
- Yanyan Li: yanyan.li.camp@gmail.com
- Xin Li: xin019@e.ntu.edu.sg 