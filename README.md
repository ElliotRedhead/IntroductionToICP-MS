# Introduction-to-ICP-MS
-------------------------
This is my first milestone project, an introduction to inductively coupled plasma mass spectrometry. Designed to be an educational tool, it covers the basic principle of the technique, the instrumentation, its application and its limitations.
-------------------------
Colour palette specified - https://coolors.co/dce3e3-acd9ce-b8bfb8-55a3af-3b5b66
https://coolors.co/bbdef0-ff8811-247ba0-1b98e0-F8FBFB
-------------------------
Resource: https://pdfs.semanticscholar.org/f57f/d4b1e5343eaf35d21afc599eddafeb437a5c.pdf
-------------------------
# Introduction to Inductively Coupled Plasma Mass Spectrometry

<div align="center">
View the live deployment here: [GitHub Page](https://elliotredhead.github.io/Introduction-to-ICP-MS/)
</div>

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

This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.

- Include links to mock and revised wireframes.

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

## Technologies Used

This project is developed with primarily HTML and CSS languages. These were chosen in order to fulfil the project requirements and are the languages that the developer has most experience in due to their suitability to website development.
The developer used [Visual Studio Code](https://code.visualstudio.com/) to create the website. This was chosen due to the developer having established experience within this software and for its Github integration.
[Bootstrap 4](https://getbootstrap.com) is used extensively throughout the project. The main application of this was for its integration of the CSS Flexbox Grid system used throughout the layout of this website. The Scrollspy was also sourced from Bootstrap, as were other preset components used for suitability and developer ease-of-use. 
[FontAwesome](https://fontawesome.com/) is used within this project to provide categorical icons as found in the mobile navigation section. 
[GoogleFonts](https://fonts.google.com/) is used to supply the fonts for the majority of texts across this website, the fonts sourced in this way were Rubik and Roboto-Condensed. 
The project uses [jQuery](https://jquery.com/) and [Popper.js](https://popper.js.org/) to enable the Bootstrap responsive navbar.


## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

This project was developed using Visual Studio Code, and was both committed to git and pushed to GitHub using the integrated source control feature.

The setup for the GitHub Pages deployment was as follows:
- Log into Github.
- Select the target repository from the list.
- Select "Settings" from the menu items.
- Scroll to the Github Pages section.
- Under "Source" click the drop-down that is set to "None" and select "Master Branch".
- The link to the website is now displayed under the "Github Pages" section.

## Clone the Project from GitHub:

Open [the repository](https://github.com/ElliotRedhead/Introduction-to-ICP-MS) in GitHub
Select the green "Clone or download" button.
Copy the clone URL for this repository.
In your local IDE open Git Bash.
Navigate to where the cloned directory should reside, make this the current working directory.
Type "git clone", and paste the clone URL.
i.e. "git clone https://github.com/ElliotRedhead/Introduction-to-ICP-MS.git"
Press Enter.
The local clone is now created.

## Credits

### Content
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
- The photos used in this site were obtained from ...

### Acknowledgements

Support for this project from Simen Daehlin
