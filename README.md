Project One: Infernal Festival Website
======================================
**Author:** *Tyler Worth*

![Infernal Festival Responsive Screens]({3A7B46AE-86C7-424A-8A14-F6ACE1AE46D2}.png)

# Project Description

Festival is a dynamic and interactive website designed to simulate the experience of an exciting design and experience of visiting and interacting with informaton in the promotional buildup for a hypothetical live festival event.
The Infernal Festival website hosts an engaging interface and vibrant design inspired by the metal music genre and industry trends featured by companies such as Metal Hammer Magazine and Download Festival.

# Website Purpose

The purpose of the Infernal Festival website for visitors is to share information for the (hypothetical) Infernal Festival event, view upcoming lineups of performing artists, receive purchasing and contact information and view visual collections of photography from previous events in addition to answering some user story generated frequently asked questions about the event and its proceedings for participation.

For the Infernal Festival clients themselves the website features strong call to actions toward ticket sales and customer information to repeatedly direct them back to the tickets purchasing page in addition to advertising the event itself and answering customer's frequently asked questions that may help them decide to attend the festival and purchase a ticket.

# Features

Interactive UI: An engaging user interface with smooth scrolling and easy navigation.
Responsive Design: The website design is optimised for mobile, tablet and desktop devices.
Ticket contact Form: Ahead of a ticket purchasing system, the website features a contact form for details on ticket purchasing and camping information as its minimum viable product (see MVP section)

# Technologies Used

- HTML5: For the structure and content of the website.
- CSS3: For styling the site with custom layouts and designs.
- Git: Version control to manage project files.
- GitHub Pages: Hosting the live version of the project.
- RealVisXL v5 Lightning: AI Generation of copyright free images of simulated events and photography. Engline hosted by https://creator.nightcafe.studio/explore 

# Links

- Website Deployment: https://cutbacktg.github.io/infernal-festival/index.html
- Github Repository: https://github.com/CutbackTG/infernal-festival

# Design

**Wireframes**

# UX

**User Stories**

1. First-Time Visitor 1:

*As a First-Time Visitor, I want to be able to easily navigate the site to find information about tour dates, ticket prices, and the festival line-up, so I don’t have to spend time searching for the details I need to decide to purchase tickets. I expect clear menus, sections, and call-to-action buttons that lead me to key pages like "Buy Tickets" and "Line-up."*

**Acceptance Criteria**
- There is a clear, intuitive main navigation menu visible at the top of every page.
- The navigation menu includes direct links to "Buy Tickets," "Line-up," and "About."
- Key pages like "Buy Tickets" and "Line-up" are reachable within one click from the homepage.
- Prominent call-to-action (CTA) buttons for "Buy Tickets" and "View Line-up" are placed on the homepage.
- Ticket sales page and the festival line-up are each clearly laid out on their own dedicated pages.
- The navigation adapts responsively for mobile (e.g., collapses into a hamburger menu).
- Site structure follows logical paths — no dead ends or hidden links.
- The homepage and other key pages include in-page links or banners pointing to "Buy Tickets" and "Line-up."
- Accessibility is considered (e.g., clear button labels, focus states, screen reader support).
- Users report finding tickets and line-up info quickly during usability testing (target: under 20 seconds).

**Tasks**

**Content Planning**
- Create content for "Tour Dates," "Ticket Prices," and "Festival Line-up" pages.
- Write strong CTA button text (e.g., "Get Your Tickets," "See the Full Line-up").

**Design**
- Design a clear navigation bar with prominent links to all key sections.
- Create homepage CTA sections (banner, feature blocks, or sticky buttons) linking directly to "Buy Tickets" and "Line-up."
- Design mobile navigation (hamburger menu) for smaller screens.

**Development**
- Build a consistent, site-wide header with a navigation menu.
Develop dedicated pages for:
- Ticket Prices (clear breakdown of pricing tiers, early bird discounts, etc.).
- Festival Line-up (artist names, times, stages if available).
- Implement anchor links and CTAs on the homepage to key pages.
- Set up a sticky header (optional) to keep navigation accessible while scrolling.

**Accessibility**
- Ensure navigation is keyboard navigable and screen reader friendly.
- Add clear focus indicators for clickable elements.
- Make CTA buttons descriptive (avoid "Click Here" — be specific like "Buy Festival Tickets").

**Testing**
- Perform usability testing with first-time visitors — measure how long it takes them to find tour dates, ticket info, and line-up.
- Test navigation functionality across browsers and devices (desktop, mobile, tablet).
- Conduct accessibility audits using tools like axe or Lighthouse.

**Performance**
- Minimize any JavaScript or CSS that could slow down menu interactions.
- Optimise images/icons used in navigation.

# Accessibility

# Testing

**Lighthouse Rating**

![index.html About Page rating]({3D617FBF-22A3-463E-B99C-25E0D76F3B95}.png)
- This rating demonstrates good accessibility, best practices and SEO, however the images in .png or .jpg format take too long to load and need to be saved as .webp files for optimisation.

After some recommended optimisation of all images to .webp files with a size of under 100kb and reducing Googlr fonts to just two weighted classes we have now achieved a slightly higher performance rating for the index.html page.

![improved About Page rating](image-3.png)

![Lineup Page rating](image-4.png)
- a slightly slower load time due to the .mp4 file but overall good scores.

![Ticket Page ratings](image-2.png)
- As expected from this relatively simple form page, excellent Lighthouse ratings across the board.

![Gallery page rating](image-5.png)
- This performance rating is to be expected with multiple images to load initially on page load.

**Bugs discovered**

![Error handling Response found](image.png)

![Page Titles not unique](image-6.png)

**Solved Bugs:**

![Unneccesary ALT tag](image-7.png)

![Duplicate autoplay attributes](image-8.png)

![Title situated outside of Head parameters](image-9.png)

![End tag required for </section> element](image-10.png)

![Video height defined incorrectly](image-11.png)

# Deployment

**Installation**
If you’d like to clone the project and work locally, follow these steps:

**Clone the repository:**

- Copy
`git clone https://github.com/cutbacktg/infernal-festival.git`
Navigate to the project directory:

- Copy
`cd infernal-festival`
Open index.html in a web browser to view the site.

**Deployment**

This section guides you through the process of deploying your web application to Github Pages from your project repository.

**Pre-requisites:**
- A github account.
- A github repository or clone of with your web project already pushed to it.

**Step 1: Prepare Your Repository**
Check that your project is in a GitHub repository. If you haven't already created one, follow these steps:

1. Create a new repository on GitHub:
- Go to GitHub and log in.
- Click the + icon at the top-right of the page and select New repository.
- Name your repository (e.g., infernal-festival).
- Make sure to initialize the repository with a README file (optional).
- After creating the repository, you will see instructions to push an existing project.

2. Push your local project to Github (if you haven't already done so):
If you have an existing project:
- Open your terminal or command line and navigate to the project folder.

Use the following commands to push your project to Github:

- `git init`  # If your project isn't already a Git repository
- `git add .` # Add all files to the staging area
- `git commit -m "Initial commit"`  # Commit the changes
- `git branch -M main`  # Rename your default branch to 'main'
- `git remote add origin https://github.com/yourusername/infernal-festival.git`  # Replace with your repository URL
- `git push -u origin main`  # Push to GitHub

**Step 2: Enable Github Pages**

1. Navigate to the settings on your repository page on Github.
- Open the repository on Github.
- Click on the ***settings*** tab located in the top menu of your repository.

2. Find the Github Pages section:
- Scroll down until you find the ***Github Pages*** section under the ***Code and automation*** category.

3. Choose a source branch for deployment:
- In the ***Source*** dropdown, select the branch you want to deploy (usually ***main*** or ***master***)
- After selcting your branch, Github Pages will automatically start building and deploying the website

4. Select the root folder (if necessary):
- Usually the root folder will be enough. However, if you have your site in a specific folder (like ***/docs*** etc), choose that folder instead.
- If your website's ***index.html*** file is in the root of your repository, no folder selection is necessary.

5. Save the changes:
 - After selecting the branch and folder (if applicable), Github will begin deploying your site. This may take several minutes depending upon the size of your site.

 **Step 3: Access your live website**

 Once Github Pages has finished building your site, you can access it via a URL.

 1. Find your Github Pages URL:
 - In the ***Github Pages*** section under ***settings***, you will see a URL that will look like:
 https://yourusername.githuib.io/infernal-festival/ 
 - This URL is your live website (as stated previously this may take a minute or two to appear, simply refresh the page periodically until it appears on the page)
 - Click the link to open your deployed website in your browser.

 **Step 4: Updating your website**

 Any time you make updates or changes to your project (e.g., editing HTML, CSS, or JavaScript), follow these steps to update your live website:

 1. Make changes to your project locally
 - Edit your files as needed in your local project directory as normal.

 2. Commit your changes in your Terminal or command line.
 - `git add .` (adds all changed files)
 - `git commit -m "Update website content"` (Commits your changes)

 3. Push the changes to Github:
 - `git push origin main` (Push to Github main branch)

 4. Wait for Github Pages to rebuild the site:
 - After pushing your changes, Github Pages will automatically rebuild your site with your new content.
 - Refresh the live URL to view your changes.

**Step 5: Troubleshooting**

Site not showing up after deployment?

- Double-check that your index.html file is in the root directory of your repository. GitHub Pages needs this file to display your website.
- Check for typos in your file names or references to other resources (like CSS or JS files).
- Make sure you've committed and pushed all your files to the repository.

Assets (images, CSS, etc.) not loading correctly?

- Ensure the file paths for your assets are correct. GitHub Pages is case-sensitive, so make sure file names are properly capitalized.

**Usage**

Once the site is open in your browser, users can:

Browse the site: View the event site, see the band line-up, contact for information on tickets and camping for the event and view the gallery of previous event photography.

**Contributing**

If you'd like to contribute to this project, feel free to fork the repository, make changes, and submit a pull request. Contributions are welcome to improve features, fix bugs, or enhance the UI.

- Fork the repository.
- Clone your forked version.
- Make your changes and commit them.
- Push your changes back to your fork.
- Submit a pull request with a description of your changes.

# Credits

**Acknowledgements**

Guidance: Special thanks to The Code Institute for their support in helping me build and refine this first project.

Inspiration: The concept for this web application was inspired by online festivals and immersive event websites.

# Code:

# Media: