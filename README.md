# Introduction to Inductively Coupled Plasma Mass Spectrometry
=====
View the live deployment [here](https://elliotredhead.github.io/Introduction-to-ICP-MS/)
-----

This page explores the basic principles of inductively coupled plasma spectrometry with the objective of 
providing educational information regarding the topic.
The website features a general introduction to the technique, with deeper description of how the different 
components come together to form the analysis. The overall application and value of the analysis is covered
with examples of specific industries it is currently used in. The basics of the physical chemistry utilised 
are introduced.
 
## User Experience
 
#### The target audience for this website is: 
* A science or science-related professional that is fluent in English.
* Assumed to have a basic understanding of chemistry/science.
* Potentially researching this method as a student or someone who is beginning a career in this field.

#### This project is the best way to deliver the content because:
* The user is guided through the information in a logical manner, building upon the taught concepts.
* The page provides all of the basic information but encourages further reading by not overloading the
user with details.
* It provides a platform to open a two-way conversation with the author, encouraging questions and feedback.
* The content is easy to navigate with appropriately named sections, allowing focus on the information given.
* The colour palette chosen is representative of the scientific data supplied, reinforcing the purpose of the website to the user.

## User Stories

1. As a user with no prior knowledge of this method I want to scroll through the sections sequentially so that I can acquire a base knowledge of the procedure.
2. As a user with some prior knowledge of this method I want to select a target section of information so that I can research more of that section in particular.
3. As a returning user with extensive prior knowledge of this method I want to contact the author so that I can discuss the method further.

<!--This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.-->



## Features

### Existing Features

#### Title
The title is large and bold, assuring users that they have found the correct page for the information they are searching for, it also includes the acronym in case the user has only ever heard of the shortened version before.
#### Navigation
The navigation method provided is fully responsive to different resolutions, allowing the user easy access to any of the sections of the page and highlighting the current sections they are reading using Scrollspy.
The overview section gives a brief introduction to the instrument, its analysis and degree of sensitivity. A list was included for this section to highlight the industries that it is applicable to. This section uses a single column layout as is the standard for information websites.
#### Overview
The overview gives a brief introduction to the background of the method, showing how it is applicable in real-world practice. This section gives the reader relative comparisons to better understand the more abstract ideas and gives a brief overview of the main components of the instrument.
#### Ionisation
This section explains to the user what the role of the plasma is, an image is included to help illustrate the physical chemistry concept that occurs upon analysis.
#### Analysis
The analysis section describes the role of the remainder of the instrument in the analysis. A block diagram is included to illustrate how each each part of the instrument interacts, and allows the user to place the concepts to their positions.
#### Maintenance
The maintenance section is used to discuss the potential drawbacks and cost of ther instrument's running to give the user an idea of logistical challenges that many occur in its use.
#### Contact
The contact form allows the user to contact the author. Its presence invites questions and feedback, allowing both the user and creator to benefit from further discussion. The user simply inputs their email address and message into the required fields before clicking the send button.
#### Share
The option to share the page is given within the footer, if the user has decided that the information provided was valuable to them and would like to share it the available options are for Facebook, Twitter and LinkedIn. These sites were chosen as the most suitable target platforms for information distribution from an educational viewpoint. The user simply clicks the site icon they wish to share to and a new window is opened with the site link filled in the message box for them.

### Features Left to Implement
* Language selection option: As automatic translation services will not accurately translate the scientific language used on this page it would be beneficial to have the page manually translated to widen the potential audience.
* Functional contact form: The frontend of the contact form is in place but to make the form fully functional a backend solution is required, this will be learned further on in the Code Institute course.


## Technologies Used

1. This project is developed with primarily HTML, due to it's suitability for website page development.
2. The project style was customised further by use of CSS.
3. Javascript is used to provide additional functions, this language was not written in by the developer but incorporated in tools that the developer utilises.
4. The developer used [Visual Studio Code](https://code.visualstudio.com/) to create the website. This was chosen due to the developer having established experience within this software and for its Github integration.
5. [Bootstrap](https://getbootstrap.com) is used extensively throughout the project. The main application of this was for its integration of the CSS Flexbox Grid system used throughout the layout of this website. The Scrollspy was also sourced from Bootstrap, as were other preset components used for suitability and developer ease-of-use.
6. [Bootstrap Social Icons](https://lipis.github.io/bootstrap-social/) are used in the footer for icons to share the webpage to a few popular social media sites.
7. [FontAwesome](https://fontawesome.com/) is used within this project to provide categorical icons as found in the mobile navigation section. 
8. [GoogleFonts](https://fonts.google.com/) is used to supply the fonts for the majority of texts across this website, the fonts sourced in this way were Rubik and Roboto-Condensed. 
9. The project uses [jQuery](https://jquery.com/) to enable the Bootstrap responsive navbar.
10. The Project uses [Popper.js](https://popper.js.org/) to enable the Bootstrap responsive navbar.

## Testing

1. Navigation (Larger Resolution)
    1. Hover over any of the targets in the navigation sidebar and confirm that they glow orange upon hover.
    2. Click a chosen section and confirm that the target section is automatically scrolled to and highlighted as the current section.
    3. Repeat the above from any scrolled section of the page and confirm that the target section is scrolled to and highlighted as the current section.

2. Navigation (Smaller Resolution)
    1. Select the burger navigation icon in the top left corner of the screen, confirm that a dropdown navigation appears.
    2. Select a target section and confirm that this is highlighted as the current section.
    3. Select the burger navigation icon to close the dropdown and reveal the selected section.
    
3. Contact Form
    1. Go to the "Contact" section.
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that the form sends successfully.

4. Additional Resources
    1. Click each of the links in the additional resources section.
    2. Confirm that each leads to their respective website, in a new tab.
    
5. Share
    1. Select each of the different social websites.
    2. Confirm that each opens a share dialog in a new tab.

The website has been opened and navigated across multiple devices and platforms, including Windows (Chrome), Linux (Chromium), Apple Mac (Safari), Apple iPhone (Safari) and Android Galaxy (Samsung Internet). Across all platforms the page loaded correctly and as was designed.

The single column text layout on larger resolutions has an inline image in the plasma-ionisation section. This is merged into the single-column format on smaller resolutions. Both images used in this website are responsive to the screen size as proven by multi-platform testing.

Troubleshooting style issues was undertaken by inspecting the affected element and determining which style properties require altering to achieve the desired result.

## Deployment

This project was developed using Visual Studio Code, and was both committed to git and pushed to GitHub using the integrated source control feature.

The setup for the GitHub Pages deployment was as follows:
- Log into Github.
- Select the target repository from the list.
- Select "Settings" from the menu items.
- Scroll to the Github Pages section.
- Under "Source" click the drop-down that is set to "None" and select "Master Branch".
- The link to the website is now displayed under the "Github Pages" section.

## Run this Project Locally:

1. Open [the repository](https://github.com/ElliotRedhead/Introduction-to-ICP-MS) in GitHub
2. Select the green "Clone or download" button.
3. Copy the clone URL for this repository.
4. In your local IDE open Git Bash.
5. Navigate to where the cloned directory should reside, make this the current working directory.
6. Type "git clone", and paste the clone URL.
**i.e. "git clone https://github.com/ElliotRedhead/Introduction-to-ICP-MS.git"**
7. Press Enter.
8. The local clone is now created.

## Credits

### Media
The photos used in this site were obtained from the following sources:
1. [Diagram of Ionisiation Energy](http://chemistry-alevel.blogspot.com/2010/12/ionic-substances.html)
2. [Block Diagram of ICP-MS Instrument](https://www.researchgate.net/figure/Schematic-of-an-Inductively-Coupled-Plasma-Mass-Spectrometer-ICP-MS_fig5_44226526)

### Acknowledgements

Many thanks for support in the creation of this website to my mentor [Simen Daehlin](https://github.com/eventyret) and user centric frontend lead: [Anna Greaves](https://github.com/AJGreaves) for their guidance and advice to the Code Institute community.
