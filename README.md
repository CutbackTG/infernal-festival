Project One: Infernal Festival Website
======================================
**Author:** *Tyler Worth*

<img src= assets\images\readme-images\infernal-festival-responsive-screens.png alt ="Infernal Festival Responsive Screens" width= 800>

# Project Description

Infernal Festival is a dynamic and interactive website designed to simulate the experience of an exciting design and experience of visiting and interacting with information in the promotional buildup for a hypothetical live festival event.
The Infernal Festival website hosts an engaging interface and vibrant design inspired by the metal music genre and industry trends featured by companies such as Metal Hammer Magazine and Download Festival.

# Website Purpose

The purpose of the Infernal Festival website for visitors is to share information for the (hypothetical) Infernal Festival event, view upcoming lineups of performing artists, receive purchasing and contact information and view visual collections of photography from previous events in addition to answering some user story generated frequently asked questions about the event and its proceedings for participation.

For the Infernal Festival clients themselves, the website features strong call to actions toward ticket sales and customer information to repeatedly direct them back to the ticket purchasing page, in addition to advertising the event itself and answering customers' frequently asked questions that may help them decide to attend the festival and purchase a ticket.

# Links

- Website Deployment: https://cutbacktg.github.io/infernal-festival/index.html
- Github Repository: https://github.com/CutbackTG/infernal-festival

# Features

Interactive UI: An engaging user interface with smooth scrolling and easy navigation.
Responsive Design: The website design is optimised for mobile, tablet, and desktop devices.
Ticket contact Form: Ahead of a ticket purchasing system, the website features a contact form for details on ticket purchasing and camping information as its minimum viable product (see MVP section)

# Technologies Used

- HTML5: For the structure and content of the website.
- CSS3: For styling the site with custom layouts and designs.
- Git: Version control to manage project files.
- GitHub Pages: Hosting the live version of the project.
- RealVisXL v5 Lightning: AI Generation of copyright-free images of simulated events and photography. Engine hosted by https://creator.nightcafe.studio/explore 

# Website Walkthrough

**Landing Page**

The Landing page features a large hero image of the festival main stage mid-performance, with the festical logo situated in the top left and a functional navigation bar linking to all four website pages with hover-over highlighting effects and an underline selction identifier for the current page displaying to the user.

Below the hero image are two bold call to action buttons linking to the performer "Line-up" page and another to navigate to the ticket information/ purchasing page.<br>

<img src= assets\images\readme-images\landing-page-upper.png alt ="Infernal Festival Landing Page Upper" width= 800>

<br>The lower section of the landing page features another large image of the location at The Scorrier Estate, Cornwall with a brief about section for the event.
Below this is a section promoting our event sponsors with functional links on the logo images once clicked and a social links footer below the sponsors which navigate to our selected social media sites.<br>

<img src= assets\images\readme-images\landing-page-lower.png alt ="Infernal Festival Landing Page Lower" width= 800>

**Line-Up Page**

The line-up page features a large looping video of a previous performance on the main stage at the festival with user controls for the media player visible on hover-over.

Overlaying this video is a list of the headline acts for the festival and their relevant stages on a reduced opacity background.

<img src= assets\images\readme-images\lineup-page-upper.png alt ="Infernal Festival Line-up Page Upper" width= 800>

The lower section of the line-up page has a designed background with a simple overlay displaying supporting acts and upcoming acts to be announced for the users.
This lower section mirrors the lower of the Landing Page, once again featuring our linked sponsors logos and our social media navigation footer.<br>

<img src= assets\images\readme-images\lineup-page-lower.png alt ="Infernal Festival Line-up Page Lower" width= 800>

**Tickets Page**

The tickets page features a simple sign-up form for further information about tickets as a precursing element before the launch of a functional ecommerce page to purchase tickets.
The form itself features placeholder entries for Full Name and Email Address and validations checks on each for correct data entry formats including regex alphabetical, spaces and mark symbols in names, allowing international letters in names and hyphenated surnames etc. and correct email formats.

A clear submit button actions the validation checks and if passed, displays a pop-up modal that notifies the user that they have been added to the mailing list for Infernal Festival.

The footer of the page once again features our social media navigation footer for more information.<br>

<img src= assets\images\readme-images\tickets-page.png alt ="Infernal Festival Tickets Page" width= 800>

**Gallery Page**

The gallery serves as a visual guide to the aesthetics and "feel" of the event as requested in the user stories, with images of previous performances, the venue site itself and the different stages with alternate text for each image included.

Our social media footer again features on this page continuing the familiarisation for the entire website.<br>

<img src= assets\images\readme-images\gallery-page.png alt ="Infernal Festival Gallery Page" width= 800>


# User Experience (UX)

# User Stories

**1. First-Time Visitor 1:**

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

**2. First-Time Visitor 2:**

*As a First-Time Visitor, I want to easily understand the main purpose of the site and learn more about the festival, so I can quickly determine if this is the kind of event I would enjoy attending. I want to see a visually striking homepage that showcases the festival’s vibe, past events, and overall atmosphere through videos, images, and key details.*

**Acceptance Criteria**
- The homepage clearly states the festival’s name, theme, and dates at first glance.
- A short, engaging headline and sub-headline explain what the festival is about.
- There is a prominent "About the Festival" section or call-to-action (CTA) leading to more information.
- High-quality videos and/or image galleries showcase past events and the overall vibe.
- The visual design feels exciting, modern, and aligned with the festival's identity.
- The site loads quickly despite media-rich content.
- The layout is responsive and mobile-friendly.
- Accessibility standards are met (e.g., alt text for images, video captions).
- First-time visitors should be able to answer "What is this event?" and "Does it interest me?" within 30 seconds of landing.

**3. First-time Visitor 3**

*As a First-Time Visitor, I want to locate social media links to check out the festival’s community and engagement, so I can see how popular and reputable the event is. I expect links to be easy to find and to lead me directly to platforms like Instagram, TikTok, and Facebook, where I can view festival highlights, band interactions, and community excitement.*

**Acceptance Criteria**
- Social media icons/links are prominently placed on the homepage (e.g., header, footer, or a sticky sidebar).
- Links lead directly to the festival’s official accounts on Instagram, TikTok, and Facebook (open in a new tab).
- The icons are easily recognizable, using standard, official platform logos.
- Social media links are also present on key pages like "Line-up," "About," and "Buy Tickets."
- Hover states or tooltips clarify the destination of each link (e.g., "Follow us on Instagram").
- Links are accessible (e.g., labelled properly for screen readers).
- Users can easily find and access the festival's social media presence within 10 seconds of landing on the site during testing.

Please visit section [Testing User stories from User Experience (UX)] for targeted testing to match these user defined requirements. 

# Design

Minimalist colour palette design of Black, #1a1a1a & #e50000 for high contrast and elegant style.

<img src= assets\images\readme-images\minimalist-colour-pallette.png alt ="Minimalist colour pallette" width= 600>

Contemporary inspirations from the Netflix logo and website design for customer familiarisation.

<img src= assets\images\readme-images\netflix-logo.png alt= "Netflix logo" width= 400>

<img src= assets\images\readme-images\netflix-landing-page.png alt= "Netflix website landing page" width= 600>
Available at https://www.netflix.com/gb/<br>
<br>
In addition to the minimalistic branding and styling of Marshall amplifiers.

<img src= assets\images\readme-images\marshall-amps.png alt= "Marshall Amps homepage" width= 600>
Available at https://www.marshall.com/gb/en 

Typography
The main font used throughout is the Lato font, a sans-serif font chosen for its modern design, readability and clean aesthetics with a fallback font of sans-serif if the user's browser fails to load Lato for any reason.

**Wireframes**

Home Page Design Concept - Mobile first<br>
<br>Mobile first design:<br>
<br>
<img src= assets/wireframes/home-page-mobiledevice.png alt= "Home page mobile first design" width= 600>
<br>Desktop Monitor design:<br>
<br>
<img src= assets/wireframes/home-page-pcdevice.png alt= "Pc Monitor Home page design" width= 600>

<br>Lineup Page Design Concept<br>

Mobile first design:<br>
<br>
<img src= assets/wireframes/lineup-page-mobiledevice.png alt= "Line up Page mobile design" width= 600>
<br>Desktop Monitor design:<br>
<br>
<img src= assets/wireframes/lineup-page-pcdevice.png alt= "Line up Page pc design" width= 600>

# Testing & Accessibility

<br>W3C CSS validator results<br>
<br>
<img src= assets\images\readme-images\w3c-css-results.png alt= "W3C CSS Validator Results" width= 600>

<br>HTML Page validator results run from W3C on source code.
Index Html<br>
<br>
<img src= assets\images\readme-images\index-html-check.png alt= "Index html source code validation check" width= 600>

<br>Lineup HTML W3C validation checker shows two expected issues.<br>
<br>
<img src= assets\images\readme-images\lineup-html-check.png alt= "Lineup Html W3c results" width= 600>

The first error here is the unexpected value of a percentage rather than a whole number, however to keep this element adaptable and display perfectly on our various media queries a static number fails to work. I did experiment with using a CSS order for 
`line-up-video {
  width: 100%
}`

however this also did not return the desired results over the initial code which works.

The second error here refers to a lower section that I coded in for future releases of information and content for the lineup page and so looks at the following lines which feature a commented heading which is in place for development.<br>

`<section id="lineup-lower-section">
      <h3><!-- lower section for additional lineup content in future--></h3>
      <div id="lineup-lower">
        <p></p>
      </div>
    </section>`

<br>Gallery HTML validation Check Results<br>
<br>
<img src= assets\images\readme-images\gallery-html-check.png alt= "gallery page html results" width= 600>

<br>Tickets HTML validation Check Results<br>
<br>
<img src= assets\images\readme-images\tickets-html-validation.png alt= "tickets page html results" width= 600>

**Accessibility - Lighthouse Rating**

<br>
<img src= assets\images\readme-images\index-lighthouse-score.png alt= "index.html About Page rating" width= 600>

- This rating demonstrates good accessibility, best practices, and SEO, however, the images in .png or .jpg format take too long to load and need to be saved as .webp files for optimisation.

After some recommended optimisation of all images to .webp files with a size of under 100kb and reducing Google fonts to just two weighted classes, we have now achieved a slightly higher performance rating for the index.html page.

The contrast does however come up as a failure as the red in the logo and the dark grey background provide an insufficient contrast for accessibility best practice (see image below)<br>
<br>
<img src= assets\images\readme-images\contrast-failure.png alt= "lighthouse contrast failure report" width= 600>

<br>To amend this I have changed the background colour from  #313131 to #1a1a1a that we have used elsewhere on the design, which smartens up the design of the site and addresses the contrast issue to suit best practices for accessible website design and raising the accessibility score to 100<br>
<br>
<img src= assets\images\readme-images\contrast-issue-fixed.png alt= "lighthouse score update" width= 600>

<br>Lighthouse rating for Lineup page:<br>
<br>
<img src= assets\images\readme-images\lineup-lighthouse-score.png alt= "Lineup Page rating" width= 600>
<br>

<br>Lighthouse rating for Ticket page:<br>
<img src= assets\images\readme-images\ticket-lighthouse-score.png alt= "Ticket Page ratings" width= 600>
<br>- As expected from this relatively simple form page, excellent Lighthouse ratings across the board.<br>

<br>Lighthouse rating for Gallery page:<br>
<img src= assets\images\readme-images\gallery-lighthouse-score.png alt= "Gallery page rating" width= 600>
<br>- This performance rating is better than I expected with multiple images to load initially on page load.<br>

**Testing User Stories from User Experience (UX)**

How the specified user story requirements have been implemented on the Infernal Festival site:

*Content Planning*
Tour Dates, Ticket Prices, Festival Line-up: The website includes dedicated sections for "Line-Up" and "Tickets." The homepage prominently displays the festival dates (1st - 3rd August) and location (The Great Estate, Cornwall).

Strong CTA Button Text: Clear call-to-action buttons such as "Buy Tickets" and "See Line-Up" are present, guiding users effectively.

*Design*
Navigation Bar: A clear navigation bar with links to "About," "Line-Up," "Tickets," and "Gallery" is present at the top of the page.

Homepage CTA Sections: The homepage features prominent CTA buttons like "Buy Tickets" and "See Line-Up," facilitating easy access to key sections.

Mobile Navigation: The website employs a responsive design, adapting to various screen sizes. On smaller screens, the navigation menu collapses into a hamburger menu, enhancing usability on mobile devices.

*Development*
Site-wide Header with Navigation Menu: A consistent header with navigation links is present across all pages, ensuring easy access to different sections.

*Dedicated Pages*
Ticket Prices: The "Tickets" page provides information on ticket purchasing, though specific pricing tiers or early bird discounts are not detailed yet.

Festival Line-up: The "Line-Up" section lists performing artists, offering users insight into the event's musical offerings.

Anchor Links and CTAs: The homepage includes anchor links and CTA buttons directing users to key pages like "Tickets" and "Line-Up."

Sticky Header: The header remains fixed at the top of the page as users scroll, maintaining constant access to navigation options.

*Accessibility*
Keyboard Navigable and Screen Reader Friendly Navigation: The website's navigation is accessible via keyboard inputs, and semantic HTML elements are used, aiding screen reader compatibility.

Focus Indicators: Interactive elements like links and buttons display visible focus indicators when navigated via keyboard, enhancing accessibility.

Descriptive CTA Buttons: Buttons use specific, descriptive text such as "Buy Tickets" and "See Line-Up," avoiding vague phrases like "Click Here."

*Testing*
Usability Testing: The intuitive layout and clear navigation present a user-friendly design that facilitates quick access to tour dates, ticket information, and the festival line-up.

Cross-Browser and Device Testing: The responsive design demonstrates that the site has been tested for functionality across various devices and screen sizes.

Accessibility Audits: The implementation of accessibility features like keyboard navigation and focus indicators shows consideration of accessibility standards, achieving high Lighthouse accessibility rankings across all pages.

*Performance*
Optimized JavaScript and CSS: The website loads efficiently, indicating that scripts and stylesheets are optimized to prevent slowdowns, particularly in menu interactions.

Optimized Images/Icons: Images and icons are appropriately sized and compressed, contributing to fast load times and overall performance.

First-Time Visitor Experience
Clear Festival Information: The homepage immediately presents the festival's name, dates, and location, providing essential information at a glance.

Engaging Headline and Sub-headline: The "About Infernal Festival" section offers a concise and engaging description of the event's theme and atmosphere.

"About the Festival" Section: An "About" section is accessible via the navigation bar, offering more detailed information about the festival.

Visual Media: A "Gallery" section is available, showcasing images from past events to convey the festival's vibe and atmosphere.

Responsive and Mobile-Friendly Layout: The site's design adjusts seamlessly to different screen sizes, ensuring usability on both desktop and mobile devices.

Accessibility Standards: The use of alt text for images and appropriate color contrasts indicates adherence to accessibility guidelines.

*Social Media Integration*
Prominent Social Media Links: Social media icons linking to platforms like Instagram, TikTok, and Facebook are present, allowing users to explore the festival's online community.

Standard Platform Logos: Recognizable icons are used for each social media platform, maintaining consistency and user familiarity.

Accessible Links: Social media links are keyboard-navigable and include descriptive aria-labels, enhancing accessibility.

*Returning/Frequent User Features*
Sign-Up for Updates: The website includes a sign-up form for users to receive updates, collecting necessary information like name and email address.

Attractive Sign-Up Section: The sign-up form is designed to be visually appealing and is placed prominently to encourage user engagement.

**Bugs discovered**

The "prettier" code formatter seemed to add some unneccessary tail slashes on source code that register in Chrome devtools as required fixes and need to be deleted before bug testing can continue, see the following example of where prettier has added the tail slashes that have been removed from the source code.<br>
<br>
<img src= assets\images\readme-images\prettier-bug.png alt= "Prettier adding syntax" width= 600>
<br>

<br>Ticket Form generated a 404 error page on submit after adding validation checks opening up a new url<br>
<br>
<img src= assets\images\readme-images\submit-error.png alt= "ticket form 404 error" width= 600>
<br>This was solved after some quick research via google where a # was required before the value ettributed to the form action to open the modal on the same page instead of going to a new url and generating teh 404 error.<br>
<br>
<img src= assets\images\readme-images\submit-fix.png alt= "ticket form fix" width= 600>

<br>After some further reading into validating alphanumeric fields using Regex I found that my first validation set for the ticket form which utilised an expected entry pattern of `pattern="^[A-Za-z\s]{2,}$"` that looked just for alphabetical entries and spaces actually wouldn't accept international symbols such as the Germanic umlaut and so would not be suitable for a potential international audience.

An article by Sanders.T (Sanders, 2021) addresses precisely this issue and suggests instead the use of unicode characters in your Regex entries and so presented me with a much more internationally friendly expected pattern of `pattern="^[\p{Letter}\p{Mark}\s-]+/gu"` that allows the use of letter-mark combinations and hyphens for hyphenated surnames.<br>
<br>

**Solved Bugs:**

On first run of checking my html code for Index.html I was presented with the following error (see image below) which addressed that I had failed to give each of my page titles a unique value and so I jumped back into my header code and changed values to Infernal Festival, Infernal Festival Lineup, " " Gallery .etc<br>
<br>
<img src= assets\images\readme-images\page-titles-not-unique.png alt= "Page Titles not unique" width= 600>
<br>

Unneccessary Alt tag entered on my video media resulted in an error, which was subsequently removed.
<br>
<img src= assets\images\readme-images\unnecessary-alt-tag.png alt= "Unneccesary ALT tag" width= 600>
<br>

I accidentally entered multiple attribes for autoplay on my video element.
<br>
<img src= assets\images\readme-images\duplicate-autoplay-attributes.png alt= "Duplicate autoplay attributes" width= 600>
<br>

Head element required a title entered to correct this error.
<br>
<img src= assets\images\readme-images\title-outside-of-head.png alt= "Title situated outside of Head parameters" width= 600>
<br>

I forgot to enter an end tag for this section element here, which was subsequently corrected.
<br>
<img src= assets\images\readme-images\end-tag-required.png alt= "End tag required for </section> element" width= 600>
<br>

Incorrect parameters defined for video element - this was corrected to the following entry:
`<video
          src="assets/Videos/line-up-video/lineup-video.mp4"
          width = 100%
          autoplay
          loop
          controls
          muted
          playsinline
        ></video>`
<br>
<img src= assets\images\readme-images\video-height-incorrect.png alt= "Video height defined incorrectly" width= 600>
<br>

Video defined height incorrect and unneccessary this was corrected to only define a video width = 100% for all devices.
<br>
<img src= assets\images\readme-images\css-validation-fix.png alt= "CSS Validation fix" width= 600>
<br>

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
- A github repository or clone of your web project already pushed to it.

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
 - This URL is your live website (as stated previously, this may take a minute or two to appear, simply refresh the page periodically until it appears on the page)
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

Glowing text tutorial code sourced from LambdaTest and then adapted to suit my project in line 94 of the #style.css file.

`.glow:hover {
  text-shadow: 0 0 10px #e50000, 0 0 20px #e50000, 0 0 30px #e50000, 0 0 40px #e50000, 0 0 50px #e50000
}`

And classified in from line 32 in the #index.html, Gallery, Lineup and Tickets source code.

`<nav>
    <ul id="menu">
      <li><a href="index.html" class="glow active">About</a></li>
      <li><a href="line-up.html" class="glow">Line-Up</a></li>
      <li><a href="tickets.html" class="glow">Tickets</a></li>
      <li><a href="gallery.html"class="glow">Gallery</a></li>
    </ul>
  </nav>
</header>`

Code resourced to centre Modal to the centre of the screen by user Vlad Udod on the Stackoverflow website

`.center {
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
}`

And adapted on line 320 of my #style.css file

`.modal {
  display: none;
  position: fixed;
  z-index: 1000;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.6);
}`

# Media:

All images and videos have been generated using Nightcafe's RealVisXL v5 Lightning: AI Generation of copyright-free images of simulated events and photography. Engine hosted by https://creator.nightcafe.studio/explore 

# References

https://www.linkedin.com/in/clinton-joy-538804244 (2025). Introducing The All New LT Browser 2.0!🖥️ | LambdaTest. [online] LambdaTest. Available at: https://www.lambdatest.com/blog/glowing-effects-in-css/ [Accessed 6 May 2025].

Sanders, T. (2021). Let’s stop using [a-zA-Z]+. [online] DEV Community. Available at: https://dev.to/tillsanders/let-s-stop-using-a-za-z-4a0m [Accessed 3 Jun. 2025].

Stack Overflow (2024). Stack Overflow - Where Developers Learn, Share, & Build Careers. [online] Stack Overflow. Available at: https://stackoverflow.com/.
