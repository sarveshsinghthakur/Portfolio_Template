# Editable Portfolio Studio
A single-file editable portfolio website built with HTML, CSS, and JavaScript.
This project lets you update your portfolio directly in the browser without editing code every time. You can change text, upload images, add or remove sections, save your work in the browser, and download a clean HTML version of your portfolio.
## Features
- Edit text directly on the page using `contenteditable`
- Upload profile, project, and social images
- Add and remove:
  - Education cards
  - Project cards
  - Blog cards
  - Social cards
- Save changes in browser using `localStorage`
- Download a clean HTML portfolio file without editor controls
- Smooth reveal animations
- Custom cursor trail effect
- Responsive layout for desktop and mobile
## Sections Included
- Hero section
- About section
- Skills section
- Education section
- Projects section
- Writing / Blog section
- Social links section
- Contact section
- Footer
## How It Works
### Edit Content
Click on editable text and type your own content.
### Upload Images
Use the upload buttons to add:
- Profile image
- Project images
- Social icons
### Add New Cards
Use the top editor bar to add new:
- Education entries
- Projects
- Blogs
- Social links
### Save Changes
Click `Save Changes` to:
1. Save the current portfolio state in your browser
2. Download a clean HTML file of the portfolio
### Reset
Click `Reset` to clear saved browser data and reload the original version.
## Exported File
When you save and download the portfolio:
- editor buttons are removed
- upload controls are removed
- remove buttons are removed
- `contenteditable` is removed
- inline editing behavior is removed
The downloaded file is a clean public portfolio version.
## Technologies Used
- HTML5
- CSS3
- JavaScript
- `localStorage`
- `FileReader API`
- `IntersectionObserver`
## Notes
- Saved changes are stored only in the same browser using `localStorage`
- If uploaded images are very large, browser storage may fill up
- For best results, use optimized/compressed images
## Customization
You can easily customize:
- colors in `:root`
- fonts
- section text
- links
- contact details
- project cards
- social platforms
## File Structure
This project is designed as a **single HTML file**, so all code is inside one file:
- HTML markup
- CSS styling
- JavaScript functionality
## Best Use Case
This project is useful for:
- students
- freshers
- developers
- designers
- freelancers
- personal portfolio websites
## Future Improvements
Possible upgrades:
- dark/light theme toggle
- image compression before save
- separate `Save` and `Download` buttons
- project filtering
- contact form backend integration
- animations with GSAP or Framer Motion style behavior
