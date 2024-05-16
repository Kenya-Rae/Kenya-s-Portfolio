<h1 allign="center" id="title"> Kenya-Rae Francis </h1>
<img src="assets/images/android-chrome-192x192.png" alt="Image of first initial logo">

[Live Project can be viewed here.](https://kenya-rae.github.io/Kenya-s-Portfolio/)

This is a website for my portfolio. It is designed to be accessible as well as responsive on a range of small to large devices. Kenya-Rae Francis is a website that aims to allure potential recruiters and other individuals who have the same interest and would like to network.

## Table of Contents

### User Experience (UX)

- Project Goals
- User Goals
- Developer Goals
- User Stories
- Design Choices
- Wireframes

### Features
### Testing
- Bugs
### Deployment
### Credits

- Content
- Media
- Code
- Acknowledgments

## User Experience (UX)

### Project Goals

The primary goal of this portfolio Project is to showcase myself to potential recruiters who are looking to hire. This project has two target audiences: Recruiters and anyone who is interested in common interests.

#### Recruiters Goals

The main audience for this site is recruiters.

#### Recruiters Goals:

- Consider hiring applicant(s).
- Look for qualified applicant(s).
- Improve the quality of hires.
- Enhancing employer brand.

#### Developers goals:
- Showcase me in the best light to recruiters.
- To get hired.
- Create a simple and effective website.

#### User Stories

As a recruiter I want:

- The ability to easily navigate the site (portfolio).
- Be able to see experience and skills demonstrated.
- Access to CV.
- Able to contact you. 

As the site owner I want:

- To get hired.
- Find others of similar interest.
- Collaborate and network with others.

## Design Choices

The overall feel of this site is to be minimalistic and professional. The design choices below were planned with this in mind.

### Languages Used 

- HTML
- CSS

### Fonts

- The primary font *Roboto* was chosen due to how concise the letters are. This font will be used within the text content of the site.
- The secondary font *Cormorant Garamond* was chosen for its simple and modern letters. Which will be used within the headers.

### Icons 

- All icons are used as they are easily recognised and understood by everyone.

### Colours

- I used a dark background to light navigation/footer, as the contrast and the feel of the page looks more formal. I chose to use light text and colourful elements to brighten pages throughout the website to ensure the website doesn't look flat all the way through.

### Images
Images of favicon can be found here:
- [Favicon.ico](/workspace/Kenya-s-Portfolio/favicon.ico)
- [Android-chrome-192x192](/workspace/Kenya-s-Portfolio/android-chrome-192x192.png)
- [Android-chrome-512x512](/workspace/Kenya-s-Portfolio/android-chrome-512x512.png)
- [Apple=touch-icon](/workspace/Kenya-s-Portfolio/apple-touch-icon.png)
- [Favicon-16x16](/workspace/Kenya-s-Portfolio/favicon-16x16.png)
- [Favicon-32x32](/workspace/Kenya-s-Portfolio/favicon-32x32.png)

Photos used within the portfolio page can be found here:
- [Raspberry Plant](assets/images/img_5367.jpg)
- [Strawberrt Plant](assets/images/img_5391.jpg)
- [Blueberry Plant](assets/images/img_5934.jpg)
- [Apple Tree](assets/images/img_5943.jpg)
- [Scotch Bonnet Plant](assets/images/img_6150.jpg)
- [Harvested Pototos](assets/images/img_6216.jpg)
- [Apple Tree Blossom](assets/images/img_7974.jpg)

### Video Files

Links to find the video files that have been added.
- [Fortnite](assets/videos/Fortnite%20Clip.mp4)
- [Warzone](assets/videos/Warzone%20clip_.mp4)

### Wireframes

- The wireframe was created using [Balsamiq](https://balsamiq.com/).
- The wireframe for the Home page can be found with this link - [Home](assets/images/Home%20Page.png)
- The wireframe for the About Me page can be found with this link - [About](assets/images/About.png)
- The wireframe for the CV page can be found with this link - [CV](assets/images/CV.png)
- The wireframe for the Portfolio page can be found with this link - [Portfolio](assets/images/Portfolio.png)
- The wireframe for the Viewport examples can be found with this link - [Media](assets/images/Media.png)

## Features

- Fully functional navigation and footer, no collapse element was used as this made some smaller devices look empty.
- Favicon was created and used to personalise the site, this is a simple icon that can be recognised.
- Responsive on all screen sizes. 
- Easy navigation, and intuitive using easily identified icons.
- Simple introduction within the home page.
- About Me, page contains brief information regarding myself (site owner). An accordion was chosen to display this information on smaller devices as this makes the site less busy and more neat. Users can interact with the accordion allowing them to read a section at a time instead of all the information showing at once. As screen size increases accordion is no longer displayed and all information is provided on the screen without any interaction features.
- The CV page provides a breakdown of my working CV and my email. Where users can gain quick information about my working history or contact me directly. A downloadable link to my CV is provided within the navbar for easy and quick access.
- The portfolio page showcases my personal hobbies gardening, gaming and web development projects. Users can interact with two videos that highlight recent edits and have the option to control them. As well as a carousel that displays photos of my gardening hobby.
- The footer is responsive and provides links to social media.

### Accessibility
- Ensuring that design/layout was not complex but was consistent and easy to navigate.
- Descriptive alt tags for each item.
- Using aria labels when needed.
- Used semantic HTML to define the meaning of the content.

## Testing
The live site has been tested on various devices and browsers and done by myself, friends and family.

The devices and browsers used to test;
- iPhone 13 Pro Max - Safari
- iPhone 13 - Safari
- iPhone 11 - Safari
- iPhone XR - Safari
- iPhone 6 - Safari
- Samsung S12 - Samsung Internet
- iPad 10th Gen - Safari
- MacBook - Chrome
- Desktop - Opera GX
- HP Pavillion Gaming Laptop 17 - Chrome

Before testing, I used Dev Tools Lighthouse. To check performance, I had to do this with the Incognito Tab as my laptop has browser extensions that may interfere with the Lighthouse testing. Within the Incognito Tab, overall accessibility and best practices come out with a 100% score, SEO with 91% and performance with 89%. Diagnostics can be found [here](assets/images/lighthouse-diagnostic.png) and performance rating can be found [here](assets/images/lighthouse-performance.png). I have managed to reduce all CSS-related things as much as possible. The other diagnostics are out of my capacity at the moment and something that could be implemented in future. 

As well as the Lighthouse, I used an HTML and CSS validator. However, when validating the code I had a couple of warnings/errors for my CV and portfolio page. [Rocketvalidator](https://rocketvalidator.com/) Was used to understand errors within validators. For example, within my video syntax, the src attribute had a space. [Link to example](https://rocketvalidator.com/html-validation/bad-value-x-for-attribute-width-on-element-video-expected-a-digit-but-saw-percent-instead). To remove this I used 20% to overcome this without changing all the file names. With this, I was able to make slight changes to my HTML to reduce any errors or warnings throughout my code. Another example of a warning was due to one of my section tags having a class attribute. This was not necessarily causing an issue, though to remove this warning, I had changed the section tag to a div that included that class attribute. Not too sure why this was a warning, maybe due to how HTML reads. However, when running the test again after the changes. There were no more warnings/errors. - I hadn't managed to take screenshots of the results as I had closed the browser off before managing to do so. Moving forward I will incorporate each result when I next make changes.

- Upon testing, it was recommended that my statement on the CV page was not visible on mobile but bigger devices displayed this. This was due to a bootstrap utility class that I have added to the personal statement paragraph. This has now been removed and posted correctly for all devices. 
- Cv PDF was not working correctly with Dev Tools. However, when tested on the live site on different devices, PDF is downloadable and works as it should.
- When viewing on MacBook, the CV page content has a bit of space on the right side of the screen if the browser is not full screen.
- It was noticed that a brightness bar displays immediately within the CV page on the Samsung S12. Two options are displayed with "Apply" and "Cancel", this also displays a bar above the CV section. When accepted, this has seemed to dim the colour of the writing or increase the boldness.
- In conclusion to the testing, the website is functional and responsive across browsers and various device resolutions. The website is intuitive and easy to navigate. Ability to access CV PDF for more information. As well as, contact information with a reasonable response time if contacted. The site also showcased and demonstrated work experience and personal interest.

## Bugs

- When viewing on a mobile device with 320 x 480 resolution, text boxes overlapped and dragged down the page. I made a change to the max height of the body made changes to each component and adjusted accordingly to resolutions.
- Fatal error when pushing my commits to my repository. Due to file sizing, I had to resize/compress my files into smaller files to fit the capacity of GitHub.
- Carousel images were taking up a lot of space within the larger screen views. As well as this, changing the size made the positioning of the photo align to the left. Leaving a big amount of space on the right. Removing .w-100 from the class element allowed me to size the images according to screen size. Using media-queries. 
- The footer wasn't staying in position and content met with the footer once placed at the bottom. I used a sticky element and some styling to position my footer correctly. I provided some elements with a margin-bottom to push up the content away from the footer.
- When viewing other resolutions in Dev Tools, I noticed that when I copy any changes to my stylesheet. In higher resolutions, the changes will not be made due to not having "!important". I used this to force the changes within the media queries.
- Uploading an image within the README.MD file will display in the preview in Gitpod, however when pushed and viewed on GitHub. The image appears to be broken. I have copied the image within my images folder under assets.

Unresolved and Questionable Bugs
- Styling for media queries that were 1440px and up, I was unable to position my divs horizontally for pages such as the CV page. I used margin-left to move and position them to where I need. However, this may not be beneficial for xxx-large screens as this may change the positioning on different screens. In the testing phase, a friend tested on MacBook. The window view was not full screen, the CV page would have a bit of a gap on the right hand of the screen next to the contents of the page. However, when the browser is in full screen the content doesn't seem to have a wide gap. I had spent some time to try and resolve this. Though with the deadline approaching im unable to problem solving any further.

## Deployments
This project was deployed to GitHub Pages using the steps below;
### How to Deploy to GitHub Pages.
1. Open the browser, search GitHub and log in. If you do not have an account, sign up [here](https://github.com/login).
2. Locate and select the [repository that you want to deploy](https://github.com/Kenya-Rae/Kenya-s-Portfolio).
3. Once the repository is open, select settings.
4. Select 'Pages', which is found on the left-hand side under the Code and Automation category.
5. Underneath build and deployment, there are two sub-heading 'Source' and 'Branch'. Select the 'None' dropdown below the branch sub-heading.
6. Change the 'None' option to 'Main', then press save
7. Wait a few moments whilst the pages refresh. (This could take up to 5 minutes.)
8. You may need to refresh the page, to see the saved changes. You should have seen that the site and the link to the live site. An orange icon will display which will indicate that the save changes are still loading.
9. You can also check your deployment by selecting 'Code'. On the right-hand side, you should see 'Deployments'. Select 'Deployments' to view the status of your deployments.

### How to run this project locally.
To clone this project to Gitpod use the following steps;

1. Open the browser, search GitHub and log in. If you do not have an account, sign up [here](https://github.com/login).
2. Open a new tab, search Gitpod and log in. If you don't have an account, you can sign in with GitHub.
3. Open a new workspace.
4. Go back to the GitHub tab and locate [Project GitHub Repository](https://github.com/Kenya-Rae/Kenya-s-Portfolio).
5. Click the green "<> Code" button.
6. Under the HTTPS tab, copy the URL for the repository.
7. Go back to your Gitpod Workspace and open the terminal.
8. Change the location of your current working directory to where you want the cloned directory.
9. Type "git clone", then paste the URL that you had copied earlier from GitHub.
10. Press Enter to create your local clone.

## Credits

### Frameworks, Libraries and Programs Used
- To create wireframes [Balsamiq](https://balsamiq.com/).
- Local IDE that was used to write code and to push files and repository to GitHub [Gitpod](https://www.gitpod.io/).
- To store files and respository [Github](https://github.com/).
- For that structure and components such as accordion, and carousel.[https://getbootstrap.com/docs/4.1/getting-started/introduction/](https://getbootstrap.com/docs/4.1/getting-started/introduction/),
- Google Dev Tools. Functionality that is built in with the Chrome browser. This was used to test designs and troubleshoot as I went along creating the website.
- Icons from [Font Awesome](https://fontawesome.com/).
- Font sourced from [Google Fonts](https://fonts.google.com/).
- Accordion template from [Bootstrap](https://getbootstrap.com/docs/4.1/components/collapse/).
- Coolors were used to select colours for elements and some text within the About, CV and Portfolio pages.[Coolors](https://coolors.co/).
- Favicon was used to create an icon [Favicon](https://favicon.io/favicon-generator/).
- To ensure I was adding the Favicon correctly [W3schools] (https://www.w3schools.com/html/html_favicon.asp).
- To compress video files [Veed](https://www.veed.io/tools/video-compressor).
- To compress images [Imageresizer](https://imageresizer.com/).
- To optimize images for the web [Tinypng](https://tinypng.com/).
- Validation of CSS was done by [Jigsaw](https://jigsaw.w3.org/css-validator/).
- Validation of HTML was done by [Validator](https://validator.w3.org/).
- CSS Minimiser [Toptal](https://www.toptal.com/developers/cssminifier).
### Media

All media sourced and provided were uploaded from my device, using the media I have captured and created.

### Code
- Code for the footer positioning sourced from [nehalahmadkhan](https://dev.to/nehalahmadkhan/how-to-make-footer-stick-to-bottom-of-web-page-3i14).
- Basic code for fade-in transition and modified to what I wanted.[hubspot](https://blog.hubspot.com/website/css-fade-in#text-transition).
- Accordion template code [Bootstrap](https://getbootstrap.com/docs/4.1/components/collapse/).
- Carousel template code [Bootstrap](https://getbootstrap.com/docs/4.1/components/carousel/).

### Acknowledgments
Thank you to everyone for all the suggestions and advice provided.

- [Code Institute](https://codeinstitute.net/) providing me the chance to learn and put what I have learnt into practice.
- [Martina Terlevic](https://github.com/SephTheOverwitch) For the reassurance and advice through the making of this project.
- Family and friends who tested my live site and provided feedback. As well as supporting me emotionally whilst building my first project!
- [Ant2210 Raw README.md](https://raw.githubusercontent.com/Ant2210/project1/main/README.md) used to prompt ideas and thoughts for my own README.md.
- [Developer.Mozilla](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries) was used when researching about making media query.
- [Display Bootstrap](https://getbootstrap.com/docs/5.3/utilities/display/) was used to research how to hide properties used from Bootstrap.
- [.w3schools](https://www.w3schools.com/css/css3_box-sizing.asp#:~:text=With%20the%20CSS%20box%2Dsizing,Hooray!) was used to get an understand of what the box-sizing property does.
- [Kevin Powell](https://www.youtube.com/watch?v=6Nv0weHy7t0) helped me find ways to tackle the overflow of text and great to refresh my mind on things I have previously learnt.
- [IoanZahria] (https://code-institute-room.slack.com/archives/CP07TN38Q/p1715337626643139?thread_ts=1715335321.886689&cid=CP07TN38Q). Helping me resolve the issue with my file sizes as this was causing a git push error.
- [Bootstrapstudio](https://forum.bootstrapstudio.io/t/how-do-you-decrease-carousel-size/5109/2) A forum post that related to a similar issue I was having. A response from Saj pointed me in the right direction on how to override the carousel image size on the desktop.
- [Joshwcomeau](https://www.joshwcomeau.com/css/center-a-div/). Explained centre a div using margin auto. This showed me a new property called margin-inline.
- [Rocketvalidator](https://rocketvalidator.com/) Was used to understand errors within validators. In particular [Page I read](https://rocketvalidator.com/html-validation/bad-value-x-for-attribute-width-on-element-video-expected-a-digit-but-saw-percent-instead) and [Another page I read](https://rocketvalidator.com/html-validation/bad-value-x-for-attribute-src-on-element-img-illegal-character-in-path-segment-space-is-not-allowed).

[Back to top](#title)