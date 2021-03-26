![CBC logo](https://canadianbusinesscollege.com/wp-content/uploads/2020/09/CBC-New-Logo-Website.png)
![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# User Centric Front End Development Milestone Project
---

Welcome to my first Milestone project for the Full Stack Software Program at the Canadian Business School, in collaboration with Code Institute.

This project is a web developer portfolio built for showing of my skills in order to attract the attention of potential recruiters or any body interested in working with me. 

👍[Quick Preview👈](https://kmadjei.github.io/MilestoneProject-UserCentricFrontEndDevelopment/)
 
## UX
---

### Strategy 

- **Project Goals**
    - Design a Full Stack Software Developer portfolio website that allows for recruiters / future employers to contact me with potential job opportunity.

- **User Objectives**
    - The portfolio will provide recruiters background information about the Developer.
    - After evaluating the portfolio, the recruiters will be able to decide whether to proceed with contacting the candidate for a potential position at company " X ". 

### Scope

- Provide informative content for users to evaluate developers skills
- Show variety of deployed projects to determine that the developer has the skills to adapt to changing work flow
- Structure the portfolio content in a way that drives user's curiosity while reducing information overload
- Add animations to enhance the liveliness of website

### Wireframes

- [Mobile View](https://github.com/kmadjei/MilestoneProject-UserCentricFrontEndDevelopment/tree/main/assets/wireframes/mobile-view)
- [Desktop and Tablet Views](https://github.com/kmadjei/MilestoneProject-UserCentricFrontEndDevelopment/tree/main/assets/wireframes/Desktop-and-Tablet)

## Features
---
 
### Existing Features
- Fixed Navigation Bar - allows users to quickly go to any section of the web page without worrying about scrolling all the way back to the beginning.
- Home page - Landing page with CTA for users inviting them to engage with the contents of the website
- About page - Provides opportunity to learn about the developer
- Skills page - gives users to analyze what they user knows and can accomplish
- Coding Challenge page - Shows the developers growth and enthusiasm for programming
- Projects page - provides users with the chance of viewing the user's skills live in action. This further enhances users trust in the abilities of the developer
- Footer section -  gives the users better experience of remembering and engaging with key information presented on the web site.

### Features to implement in the Future

- Making individual landing pages for each project with slides of project mockups, incase recruiters were not interested in deploying the whole project
- Add  a contact page with an email contact form

## Technologies Used
---

- [HTML](https://www.w3schools.com/html/default.asp) 
    - In the project **HTML** was used for creating the basic information structure of th site

- [CSS](https://www.w3schools.com/css/default.asp)
    - The project uses **CSS** to simplify further enhance content and structure of the site.

- [Bootstrap 4.6](https://getbootstrap.com/docs/4.5/getting-started/introduction/)
    - The project uses **Bootstrap 4.6** to create responsive elements and styling for the contents.

- [Font Awesome](https://fontawesome.com/icons?d=gallery&p=1)
    - **Font Awesome** was used for creating the social icons and the collapsible menu on small screen devices


## Testing
---

1. [W3C CSS Validation](https://jigsaw.w3.org/css-validator/#validate_by_input)
    1. Directly injected style.css code using the **W3C CSS Validator** - resulting in meeting the requirements CSS3
    <img style="border:0;width:88px;height:31px"
            src="http://jigsaw.w3.org/css-validator/images/vcss"
            alt="Valid CSS!" />

2. [W3C HTML Validation](https://validator.w3.org/#validate_by_input)
    1. By directly injecting HTML code into the **W3C HTML Validator** you can verify it passes HTML5 markup requirements
        - Results shows no errors or warnings found 

3. **Device Responsiveness**
    1. Once project is deployed, using chrome or any browser of your choice , right click on the page and select inspect or push **F12** on your keyboard
    2. On chrome - I utilized breakpoints to view my website for different screen devices 
    3. I proceeded to write the media queries:
        1. The about section was changed to a 1 column view on mobile devices
        2. The footer section containing **_container_** class was adjusted to one column view using the grid display for mobile view
        3. The header utilized bootstrap classes so no query was required for it
        4. A responsive text using `vw` was utilized for the Home page text for views less than 475px

4. **Broken Link Test**
    - While the project was deployed live, I proceeded to click through the navigation links, social, links, Project Links, and the coding challenge links to make sure they operated how they should
        - Navigation links directed user to desired page
        - All other links open new window tab when clicked 

### User Stories Testing

1. As a new user I want to be able to clearly navigate the page 
    1. Any user is able to navigate the page without getting lost due to fixed navigation bar and the responsive nature of the webpage

2. As a recruiter I would want to know if the developer pays attention to details
    1. Website prototype was sent out to friends for feedback on user experiences
    2. The Results:
        - Bootstrap Navigation bar corrected with font Awesome Hamburger Icon and cdn was changed from 4.5 to version 4.6
        - Grammar mistakes in the throughout the page was spotted and corrected


## Deployment
---

The easiest way to view the project is with github pages. And since the files have already been uploaded just click on the link below for access:

[🚀LAUNCH🚀](https://kmadjei.github.io/MilestoneProject-UserCentricFrontEndDevelopment/)
 
 - **Deploying to Github**
    1. The project was built using the light weight IDE, [VS Code](https://code.visualstudio.com/).
    2. Upon completion, [Gitbash](https://git-scm.com/downloads) was downloaded for windows 10
    3. Gitbash was then utilized to upload the project on to Github via it's CMD. Note that a github account was created to host the project.
        1. After download, right click on project root folder and click *Gitbash Here*
        2. When open enter `git init` to initialize the folder 
        3. On github, a repository was created for the project.
        4. After creating the repository, the instructions for  deployment via the CMD was followed
        5. In the instructions, `git add .` was used to add all files and then the `git commit` was entered after typing it in the command line
        6. All files were then pushed online using `git push` after confirming login validations.
    4. In the settings of the Git hub repository for the project, the Git hub pages section shows a drop down from which the where the main branch folder is selected. 
    5. The main branch houses the index file which can deploy the static page of the project.
    6. After saving your changes, a hosting site is generated for the project 

- **Deploy Locally**
    1. Click this [download](https://github.com/kmadjei/MilestoneProject-UserCentricFrontEndDevelopment/archive/refs/heads/main.zip) link of the project from github repository. 
    2. Once downloaded, unzip the file or go into the zip folder and copy the files to your preferred location.
    3. Double click on the index file to view the project on your local desktop once the download process is completed


## Credits
---

###

- W3C school code examples for creating cards served as a basis for creating the cards for the skill, coding challenge, and project sections
    - CSS animation examples for cards were also utilized such as:
        - Box-shadow
        - 3D card 180* rotation
        - Image overlay

- Code from the Bootstrap resume project, presented by the Code Institute Learning platform, was utilized for the footer social icons of the webpage 

- Utilized bootstrap template for Navbar

### Content

- The text for all the sections of the website are  my original work

### Media

- The photos used in the skill section were obtained from google images
    - [Front End Logos](https://www.pngitem.com/pimgs/m/520-5208614_curso-programacin-front-end-completo-transparent-html-css.png) 
    - [Bootstrap logo](https://www.pinclipart.com/picdir/middle/35-353932_bootstrap-bootstrap-4-logo-png-clipart.png)
    - [PHP and MySQL logo](https://cdn.app.compendium.com/uploads/user/e7c690e8-6ff9-102a-ac6d-e4aebca50425/8a997691-8bf1-4258-9b29-795bf5ddd085/Image/7e869e0f81db34c1a99a7906a2fe8cae/php_mysql.png)
    - [Wordpress](https://www.google.com/url?sa=i&url=https%3A%2F%2Fthemeskills.com%2Fchange-login-wordpress-logo-url-no-plugin%2F&psig=AOvVaw2kyAvoemK5eqo1Y7pgTNNS&ust=1615696052991000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCIjMpIC3rO8CFQAAAAAdAAAAABAD)

- The background hero image was obtained from Pexels.com (created by [Markus Spiske](https://www.pexels.com/photo/matrix-background-1089438/))

- The logos for the project and coding challenge card were created using [Free Logo Design](https://editor.freelogodesign.org/?lang=en&logo=ec4667e0-7afa-4580-bab4-d973522c34d9) and 3d paint App for windows 10.


### Acknowledgements

- In order to design and build this project, I sought for  advice from fellow developers on YouTube and modeled my portfolio project after them:
    - [Bedimcode](https://www.youtube.com/watch?v=6cidbUHNZRQ&t=1061s) 
    - [Career Foundry](https://www.youtube.com/watch?v=5j7orGKJslg&t=716s&ab_channel=CoderFoundry)

- The [Mini-Bootstrap Project](https://github.com/Code-Institute-Solutions/resume-miniproject-bootstrap4/tree/master/18-resume-for-download) walk-through also expanded my knowledge in using bootstrap for my front end design along with design ideas for the footer of the website

