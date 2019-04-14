# Lady Gaga Information Site
This is an information website about Lady Gaga. It will cover her life and achievements so that people can find out more about Lady Gaga.

## Demo
A live demo can be found [here](https://alwy-user-centric-assignment.herokuapp.com/).
## UX
My goal in the design was to make it as easy as possible to access information on the site while striving for a minimalist design. 
 - The light colour scheme was chosen to create a light-hearted and easy navigation feel. The main colours used were lavender (Lady Gaga's favourite colour) and white.
 - For the font, Helvetica (Humanist Sans-Serif) was used for Body and Didot (Modern Serif) was used for Headings and Navigation Bar to create contrast.
 - Information was classified into "Biography", "Discography", "Filmography" and "Contact" as these are the main topics that users would want to look into.
 - Links to Lady Gaga's Facebook, Instagram, Twitter and YouTube profiles were provided at the bottom of each page for the user to access official Lady Gaga resources.

 ### Existing Features
- I used a sticky button for the 'Biography' page so that regardless of where the user is on this long page, the user can easily click on the menu items to get to their intended section on the page.

### Features Left to Implement
- I would like to add smooth scrolling to the 'Biography' page's navigation menu so that the user will not jump to the section he clicks on. Instead, the page will scroll smoothly to the section after he clicks on it.

## Technologies Used
1. HTML
- For structuring the website, e.g. adding content to the website.
2. CSS
- For styling the website, e.g. font sizes and font colours.
3. [Bootstrap (Version 4)](https://getbootstrap.com/)
 - The project uses Bootstrap to create mobile-responsive web pages.


4. [JQuery](https://jquery.com)
    - The project uses **JQuery** to create the modals on the ‘Discography’ and ‘Filmography’ pages, and the button and collapsible navigation bar on the ‘Biography’ page.


## Testing
There was no JavaScript code written for this project. Any JavaScript feature, such as Modal in the ‘Discography’ and ‘Filmography’ pages, was created using the Bootstrap’s JavaScript modal plugin. Therefore, there was no need to use Jasmine, a behaviour-driven development framework, or any automation for testing JavaScript code.

The HTML, CSS and other features of this website were tested manually.

Every page of this website was tested on different browsers (Google Chrome and Microsoft Edge) and on different screen sizes on mobile devices and desktop computers. The navigation bar at the top of each page will change into a navigation bar when the screen size decreases from that of a desktop computer to that of a mobile device. The social media icons at the bottom of each page allows the user to access external websites with Lady Gaga information. The navigation bars at the top and bottom of every page allows the user to click and go to a different page on the website easily.

Page Testing:
1. Home
- Clicking a “Read More” button opens up a new tab for an external website.

2. Biography
- The sticky button on the right side of the page does not disappear even whether the user scrolls the page down or up. 
- Clicking on the sticky button on the right side of the page opens a navigation menu and the user can click on an item to go to its respective section on this page.  

3. Discography and Filmography
- Clicking a “Read More” button opens a modal with descriptive text.
- Clicking the “Close” button in a modal closes the modal.
- Clicking the ‘Play’ button in the middle of a video in the ‘Music Videos’ or ‘Trailers’ section plays the video
- Clicking an indicator bar at the bottom centre of each video allows the user to slide to the respective video in the media carousel.

4. Contact
    
    i. Go to the "Contact " page

    ii. Try to submit the empty form and verify that an error message about the required fields appears

    iii. Try to submit the form with an invalid email address and verify that a relevant error message appears

    iv. Try to submit the form with all inputs valid. Verify that all the details keyed into the fields by the user are replaced by the original placeholder texts if the form was submitted successfully.

## Deployment
This project was deployed to Heroku.
A person who wants to run this code locally can clone or download this repository from https://github.com/AlexLimWY/user-centric-assg.git and paste it into their editor terminal.

## Credits
### Content
- The text for "Latest News" was copied from the following Gaga Daily articles:
    - [Lady Gaga Celebrates Decade With V Magazine With Enigmatic Cover](https://gagadaily.com/story/news/lady-gaga-v-magazine-118/)
    - [Lady Gaga Lands First Number One Single In 8 Years](https://gagadaily.com/story/news/lady-gaga-shallow-number-one/)
    - [Lady Gaga Addresses Bradley Cooper Romance Rumors On Jimmy Kimmel](https://gagadaily.com/story/news/lady-gaga-jimmy-kimmel-oscars/)
- The text for "Accolades" was copied from the following Wikipedia article: [Achievements](https://en.wikipedia.org/wiki/Lady_Gaga#Achievements)
- The text for "Philanthropy" was copied from the following Wikipedia article: [Born This Way Foundation](https://en.wikipedia.org/wiki/Lady_Gaga#Born_This_Way_Foundation)
- The text for "Personal Life" was copied from the following IMDb article: [Lady Gaga Biography](https://www.imdb.com/name/nm3078932/bio?ref_=nm_ov_bio_sm)
- The text for "The Fame" was copied from the following Wikipedia article: [The Fame](https://en.wikipedia.org/wiki/The_Fame)
- The text for "Artpop" was copied from the following Wikipedia article: [Artpop](https://en.wikipedia.org/wiki/Artpop)
- The text for "Born This Way" was copied from the following Wikipedia article: [Born This Way (album)](https://en.wikipedia.org/wiki/Born_This_Way_(album))
- The text for "Cheek To Cheek" was copied from the following Wikipedia article: [Cheek to Cheek (album)](https://en.wikipedia.org/wiki/Cheek_to_Cheek_(album))
- The text for "Cheek To Cheek" was copied from the following Wikipedia article: [Joanne (album)](https://en.wikipedia.org/wiki/Joanne_(album))
- The text for "A Star Is Born" was copied from the following Wikipedia article: [A Star Is Born (2018 soundtrack)](https://en.wikipedia.org/wiki/A_Star_Is_Born_(2018_soundtrack))
- The text for "American Horror Story: Hotel" was copied from the following Wikipedia article: [American Horror Story: Hotel](https://en.wikipedia.org/wiki/American_Horror_Story:_Hotel)
- The text for "American Horror Story: Roanoke" was copied from the following Wikipedia article: [American Horror Story: Roanoke](https://en.wikipedia.org/wiki/American_Horror_Story:_Roanoke)
- The text for "A Star Is Born" was copied from the following Wikipedia article: [A Star Is Born (2018 film)](https://en.wikipedia.org/wiki/A_Star_Is_Born_(2018_film))

### Media
- All pictures (except the Hero image on the Home page and the Lady Gaga logo on the top left of every page) were taken from Wikipedia (www.wikipedia.org)
- The Hero image was taken from http://www.f-covers.com/ .
- The Lady Gaga logo was taken from https://shop.ladygaga.com/ .
### Acknowledgements
- I received inspiration for this project from Lady Gaga. She is a very famous and talented person who can sing, act and dance. She has won numerous singing and acting awards and I thought that it would be interesting to find out how she achieved so much in this short amount of time. I wanted to share my findings on this website so that others can learn more about her.
- The sticky button for this website was inspired by https://www.haleyschafer.com/, which also uses a sticky button on the right side of the page.

