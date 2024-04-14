# Portfolio
This porfolio was created for T1A2 of Coder Academy's Web Development Course.

[Link to GitHub repository](https://github.com/JZ2803/portfolio)

## Table of Contents
* [Purpose and Target Audience](#purpose-and-target-audience)
* [Technologies Used](#technologies-used)
* [Functionality and Features](#functionality-and-features)
    * [Sitemap](#sitemap)
        * [Home page](#home-page)
        * [Experience page](#experience-page)
        * [Portfolio page](#portfolio-page)
        * [Project post](#project-post)
        * [Blog page](#blog-page)
        * [Blog post](#blog-post)
        * [Contact page](#contact-page)
    * [Noteworthy/Reusable Components](#noteworthyreusable-components)
    * [Aesthetic and Colour Scheme](#aesthetic-and-colour-scheme)
    * [Accessibility](#accessibility)
* [Wireframes](#wireframes)
    * [Media Query Breakpoints](#media-query-breakpoints)
    * [Mobile Wireframes](#mobile-wireframes)
    * [Tablet Wireframes](#tablet-wireframes)
    * [Desktop Wireframes](#desktop-wireframes)
* [Screenshots](#screenshots)
* [Acknowledgements](#acknowledgements)

## Purpose and Target Audience
The purpose of this portfolio website is to present information about myself as a developer and IT professional in a clear, easy-to-navigate and visually appealing way to prospective employers.

Key information items include: overview of skills and professional experience, resume, project portfolio, blog posts and contact details.

## Technologies Used
This portfolio website leverages concepts and technologies learned in the first two weeks of the course. Languages utilised in developing the portfolio website are HTML and CSS. Flexbox is utilised quite heavily throughout the website for layout.

## Functionality, Features and Design
When designing the website layout, some key themes I kept in mind were: clear structure, accessibility, clean aesthetic and website responsiveness. To maintain clarity and structure, I divided the website into five main pages, each serving a distinct purpose, which can be easily accessed via the navigation bar.

### Sitemap
![sitemap](/docs/sitemap.png)

#### Home page
I wanted the home page to serve as a clear, high-level overview of the structure and content of my portfolio website, containing snapshots of each main page of the website. The home page can be categorised into two main sections/components:
* **Profile summary section:** which includes my photo, a short description about myself and email/social media buttons for easy access.
* **Overview of main pages of website:** the skills & experience section includes a summarised overview of my technical skills as well as links to access the experience page and my resume. The portfolio and blog sections show previews of my two latests posts which users can click to view the full individual post, and there are also links to the full portfolio and blog pages.

#### Experience page
The purpose of this page is to present all the information a propsective employer would want to know regarding my technical skills and professional experience, in a clear and concise way. As such, there are two main items on this page:
* **Summary of skills & experience:** essentially a short version of a cover letter which prospective employers can easily access and read to quickly gain an understanding of my background, skills and professional experience.
* **Button to view resume:** following on from the summary above, I wanted to ensure that if the employer is interested in learning more, a full PDF version of my resume can beeasily and readily viewed/downloaded. As such, a button is included (call to action component) for this purpose.

#### Portfolio page
This page lists all the projects in my portfolio. Each project is shown in a tile containing the project name, a brief description and an image. Clicking on the project name or image will take the user to the project post (child page), where full details of the project can be viewed. 

To ensure the page layout remains balanced on all screen sizes, on smaller screens such as mobile and tablet the project tiles are displayed in single column whilst on larger screens they are displayed in two columns.

#### Project post
Project post pages are child pages of the Portfolio page, contain the details of an individual project, and feature the following:
* **Button to GitHub repo:** call to action component, for easy access.
* **Post text:** writeup of the project details.
* **Images:** visual documentation along with the text.

#### Blog page
Similar to the purpose of the portfolio page, the blog page lists out blog posts I have published. Blog posts are shown in tiles similar to the project tiles in the Portfolio page but with some minor differences to accomodate the different content type. One difference is that the blog post tiles include a publish date, this way the user is informed at a glance of how recent the blog posts are without clicking into the post itself. With this addition, I also modified the tile layout to display the image on the right to ensure the blog title, description and publish date all fit cleanly in the tile.

As with the Portfolio page, the tiles are displayed in single column on smaller screens and two columns on larger screens.

#### Blog post
Blog post pages are child pages of the Blog page, contain an individual blog post, and feature the following:
* **Published date:** to inform user of date of publish and relevancy.
* **Post text:** blog post writeup.
* **Images:** visual documentation along with the text.

#### Contact Page
This page presents all the ways which users can contact me. It has two components:
* **Social media buttons:** links to my profile on various social media platforms.
* **Contact form:** where users can input their name and email address and submit a message. This serves as an alternative if the user does not wish to use social media contact.

### Noteworthy/Reusable Components
1. **Navigation bar:** to ensure users have a way to easily navigate between pages of the website, I included a horizontal navigation bar at the top of all pages of the website. The bar is fixed in position, meaning that it will remain at the top of the user's screen regardless of what location on the page the user is at. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![screenshot-navbar](/docs/screenshot-navbar.png)

2. **Social media buttons:** minimal, dark grey buttons with rounded edges were designed with the overall clean and professional theme of the website in mind. A basic hover effect was incorporated, to make the page more interactive and engage the user. Upon hovering, the buttons text and borders change to a shade of blue consistent with the theme of the website and provide some aesthetic elements. These set of buttons appear in both the home page and the Contact pages.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![screenshot-socialmediabuttons](/docs/screenshot-socialmediabuttons.png)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![screenshot-socialmediabuttons](/docs/screenshot-socialmediabuttonshover.png)

3. **Copyright footer:** included at the bottom of every page on the website. Interestingly, I found that the best way to achieve the positioning of the footer at bottom of the page (even on shorter pages) was to utilise Flexbox.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![screenshot-footer](/docs/screenshot-footer.png)

4. **Project list:** as detailed in the [Portfolio page](#portfolio-page) section, a snapshot of each project is shown on its own tile which includes information such as the project name, brief description and an image and the full project writeup can be accessed through clicking the project title or image. Collectively, these tiles (i.e. list of projects) can be considered a component.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[See 'Portfolio page' in Screenshots section](#screenshots)

5. **Project post:** as detailed in the [Project post](#project-post) section, these pages are child pages to the Portfolio page and contain a button to access the project repo on GitHub, project writeup and supporting image documentation. This page (component) is reused for every project post.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[See 'Project post' in Screenshots section](#screenshots)

6. **Blog list:** as detailed in the [Blog page](#blog-page) section, a snapshot of each blog is shown on its own tile which includes information such as the blog post name, brief description, publish date and image. The full blog post can be accessed through clicking the blog post title or image. Collectively, these tiles (i.e. list of blog posts) can be considered a component.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[See 'Blog page' in Screenshots section](#screenshots)

7. **Blog post:** as detailed in the [Blog post](#blog-post) section, these pages are child pages to the Portfolio page and contain publish date, blog post text and supporting images. This page (component) is reused for every blog post.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[See 'Blog post' in Screenshots section](#screenshots)

### Aesthetic and Colour Scheme
With the aim of creating a website with a clean and professional feel whilst not appearing too bland or generic, I decided on a black/grey/white colour theme with muted blue accents. This colour scheme stands out and is visually appealing yet does not take away from the content it is presenting, and is consistently implemented throuhgout all the pages and subpages on the website.

### Accessibility
With user accessibility in mind, semantic elements were used throughout the HTML document where possible.

## Wireframes
As aforementioned, clear structure and responsiveness were key considations when creating the layout of the website. As such, the functionality, features and design of the website were developed using the mobile-first approach.

### Media Query Breakpoints
I started developing my website on a screen width of 360px (based on my research, this tends to be the lower end of the spectrum of mobile screen sizes). From there, I increased the screen width incrementally until the page layout started to look unbalanced, and would set a media query breakpoint there and modify elements where necessary. Then, I would rinse and repeat, until I reached the upper threshold of screen sizes (I stopped at 1920px).

In performing this process, I found that given the use of Flexbox for layout throughout my website, the pages were already quite responsive.

Utlimately, I decided that setting four media query breakpoints (400px, 550px, 700px, 950px) worked best for the layout of my website. 950px was the last breakpoint I set, as by that point I had set a max-width for the pages and any further increase to the screen size would not change the layout.

See wireframes below for layout on different screen sizes:

### Mobile Wireframes
![wireframe-mobile](/docs/wireframe-mobile.png)
### Tablet Wireframes
![wireframe-tablet](/docs/wireframe-tablet.png)
### Desktop Wireframes
![wireframe-desktop](/docs/wireframe-desktop.png)

*Note: Footer is not shown in the wireframes as I decided to add it to the website layout after designing the wireframes.*

## Screenshots

### Home page
![screenshot-home1](/docs/screenshot-home1.png)
![screenshot-home1](/docs/screenshot-home2.png)

### Experience page
![screenshot-experience](/docs/screenshot-experience.png)

### Portfolio page
![screenshot-portfolio](/docs/screenshot-portfolio.png)

### Project post
![screenshot-project](/docs/screenshot-project.png)

### Blog page
![screenshot-blog](/docs/screenshot-blog.png)

### Blog post
![screenshot-blogpost](/docs/screenshot-blogpost.png)

### Contact page
![screenshot-contact](/docs/screenshot-contact.png)

## Acknowledgements
- [Font Awesome](https://fontawesome.com/) for icons
- [draw.io](https://app.diagrams.net/) for wireframes
- [Lucidchart](https://www.lucidchart.com/) for sitemap