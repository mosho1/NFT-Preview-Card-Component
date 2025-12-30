## Frontend Mentor - NFT Preview Card Component
Design preview for the NFT preview card component coding challenge
Welcome! 👋
Thanks for checking out this front-end coding challenge.
Frontend Mentor challenges help you improve your coding skills by building realistic projects.
## The Challenge
The challenge is to build an NFT preview card component that closely matches the provided design. The component showcases an NFT item ("Equilibrium #3429") with details like price, time remaining, and creator information, featuring hover effects for interactivity.
Users should be able to:
View the optimal layout for their device's screen size (desktop or mobile).
See hover states for interactive elements, such as the NFT title, creator name, and image overlay with an eye icon.
## Where to Find Everything
The project includes designs in the /design folder, with both mobile and desktop versions in JPG format. Use your best judgment for styles like font-size, padding, and margin based on these designs.
All required assets (e.g., NFT image, icons, favicon, avatar) are in the /images folder and are optimized for use. The style-guide.md file contains the color palette and font details:
Fonts: Outfit (weights: 300, 400, 600)
Colors:
Primary:
Soft Blue: hsl(215, 51%, 70%)
Cyan: hsl(178, 100%, 50%)
Neutral:
Main Background: hsl(217, 54%, 11%)
Card Background: hsl(216, 50%, 16%)
Line: hsl(215, 32%, 27%)
White: hsl(0, 0%, 100%)
## Building the Project
 # My Process
I followed a mobile-first workflow, structuring the content with semantic HTML before applying styles. The process included:
Setting up a public repository on GitHub.
Writing clean, semantic HTML to structure the NFT card, including the image, title, description, price, date, creator, and attribution.
Using CSS Flexbox for alignment and layout consistency.
Implementing hover effects, such as the cyan overlay with an eye icon on the NFT image and color changes for the title and creator name.
Using CSS custom properties (:root) for consistent color management.
Testing the layout across different screen sizes to ensure responsiveness.
Built With
Semantic HTML5 markup
CSS custom properties
Flexbox (for alignment and layout)
Mobile-first workflow
Outfit - For all text (weights: 300, 400, 600)
## What I Learned
This project deepened my understanding of:
Hover Effects: Created an interactive image overlay using absolute positioning and opacity transitions, as shown below.
CSS Custom Properties: Used :root variables to manage colors consistently across the project.
Flexbox: Applied Flexbox to align the price and date sections evenly with justify-content: space-between.
Font Styling: Leveraged the Outfit font with multiple weights for hierarchy and readability.
CSS snippet I’m proud of:
css
.overlay2 {
  position: absolute;
  top: 0;
  margin-top: 45px;
  background-color: hsl(178, 100%, 50%, 50%);
  width: 15.45em;
  height: 15.45em;
  z-index: 999;
  opacity: 0;
  transition: opacity 0.3s ease-in-out;
  border-radius: 7px;
}

.overlay2:hover {
  cursor: pointer;
  opacity: 1;
}
This code creates a smooth cyan overlay with an eye icon that appears when hovering over the NFT image, enhancing interactivity.
## Continued Development
In future projects, I plan to:
Add CSS animations for card entry or hover transitions to improve user experience.
Enhance accessibility with ARIA attributes and keyboard navigation for interactive elements.
Optimize image loading with techniques like srcset or lazy-loading.
Explore CSS Grid for more complex layouts in similar projects.
## Useful Resources
MDN Web Docs - CSS Positioning - Helped with absolute positioning for the image overlay.
Google Fonts - For selecting and implementing the Outfit font.
CSS Tricks - Flexbox - A great reference for Flexbox alignment.
Frontend Mentor Slack - For community support and feedback.
## Deploying the Project
The project was hosted using:
GitHub Pages
Links
Solution URL: Add your solution URL here
Live Site URL: Add your live site URL here
Author
Name - Moshood
Frontend Mentor - mosho1
Twitter - @EMPERORMOSH
Acknowledgments
Thank you to Frontend Mentor for providing this challenge and the design assets. The clear structure of their challenges helped me focus on both design fidelity and technical implementation. I also appreciate the community for offering inspiration and feedback.
