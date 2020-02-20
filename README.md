# Olympus Fitness - Responsive site for a gym business. 
#### _Author_ - *Blazej Werbanowski*

Link to the site https://badziobw.github.io/bw-ci-milestone1/ 

For my project in the User Centered Frontend Design module I have chosen to do a website for a fake gym business. As a gym enthusiast myself, I had a fair idea of what content such site needs which made a project easier. I have focused on making a user friendly website that tells potential client all the information he may need and also makes a new customer excited to visit the gym and see it for himself. 
My personal goal when designing this website was to heavily alter and edit existing bootstrap  components. I wanted use this project as a learning tool predominantly to improve my little knowledge of bootstrap and semantic HTML.

## UX  - User Experience Design

### User stories

#### User Goals
Owner's - To attract new customers by giving them enough information about what does the business offer and what makes it different than others as well as provide quick information to existing customers such as opening times and offers.
New Customer - To find out what is on offer at Olympus Fitness. Have a look at how does the gym look, where is it located and its opening hours. I would also like to be able to contact the gym online.
Existing Customer - I want to be able to check the opening times of the gym and contact staff with any queries I have.

#### Solution

These goals are accomplished by designing a website that will be easy to navigate and rich in information. The information has to well presented to not confuse the customer. This is done by creating sections on the website that aim to give information about the gym, it's membership options, its contact information and opening times. Additional features are the gallery and social links that aim to help the owner interact with the customers. An easy to use, simple form that allows user to ask a question in a matter of minutes is also designed and placed conveniently in the contact page.



## Features

The site consists of a main page and 4 subpages ( Our offer, About, Gallery, Contact).
Each section of the home page aims to provide short, relevant information with more detailed version on the corresponding subpage.

### Existing features

* Navigation menu at the top and bottom of each subpage that allows user to go to any subpage.
* Sticky footer and header with most sought for information and links
* Background images specifically chosen to make the customer more interested in the gym.
* Gallery of the gym in a form of carousel that is kept "in the back" and does not distract the user
* Simple font (roboto) throughout, with exception for brand name which makes it stand out and complement the logo
* Mobile Home page's  'More Info' button transfer user directly to a bigger variery of information about the membership options.
* Contact page contains a simple form that allows user to ask question without forcing to provide a lot of information to do so, only email is required as a contact option, telephone is only optional.
* On submit of form a Modal Popup appears thanking the user for submitting a question.
* On the Gallery subpage when image is clicked it scales while maintaining its quality.
 

#### Features Left to Implement

* Form that will fully validate
* Add a section with a foreword from personal trainers (testimonials)

## Technologies Used
* HTML 5 - used for the semantic markup of the website
* CSS3 - used for customized styling of all the components on the site
* Bootstrap 4.4 
* Google Fonts - I have used two fonts Roboto as main text throughout the site and Bangers for the logo brand text
* jQuery - used in the burger menu via bootstrap
* Visual Studio Code -  as a main editor
* Javascript - used for Bootstrap modals and custom onClick action in offer.html
* Fontawesome -  for icons that aim to improve the look of the website
* Markdown - used for readMe files
* Git - used as a version control to commit the code to Github.com
* http://ami.responsivedesign.is/ - this website was used to display the site's responsiveness at the same time

When choosing color pallete for the project I have used a [Color Hunt pallete](https://colorhunt.co/palette/161696), and added complimentary colors that I found matching this pallete.




## Testing
When validating the code for errors I have used the following:
* [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator/#validate-by-input)
* [HTML](https://validator.w3.org/)

The site has been manually tested using various devices.
For the reponsiveness test, most of the possible options in Chrome Developer tools such as iPad, iPhone emulators as well as actual Huawei P8 and Samsung S8 mobile phones both in portrait and landscape modes were tested.
Additionally I have tested if the site displays correctly in the following browsers:
* Google Chrome mobile
* Google Chrome desktop
* Mozilla Desktop
* Safari Desktop
* Microsoft Edge
* Opera mobile 

Overall I was happy with the testing, the fonts seemed to be sized appropriately as well as other elements, the images did not loose the quality on larger device. 

### Bugs / errors
* Upon validation of the code I noticed few errors with the choice of html tags, I have chosen wrong child elements for the element span in many cases, which showed up error. This is something that I will need to look into and re build that portion of the code to make sure it validates correctly.

## Deployment
The site's index.html README.md and sub pages are in the main directory, stylesheets are kept in css folder and additional components are located in the assets folder.
Finished project has been deployed as a website using Github Pages. It is synchronised with master branch, any further commits to the master branch will be updated live on the deployed site.
It can be viewed under https://badziobw.github.io/bw-ci-milestone1/
To deploy the repository on a local machine, git clone the repository https://github.com/badziobw/bw-ci-milestone1 to your machine.

## Credits

#### Images

All the images used in the project apart from the Logo image were taken from https://www.pexels.com . Those images are free to use and edit.
The image used for the logo was taken from [this site] (https://pixabay.com/illustrations/gym-weight-loss-muscle-exercise-1048852/) and edited by me to suit the color scheme of the website.
#### Code
[Stack Overflow](https://www.stackoverflow.com), [w3schools](https://www.w3schools.com/), [Mozilla Developer Network](https://developer.mozilla.org/en-US/), [Bootstrap 4.4 Documentation](https://getbootstrap.com/docs/4.4/getting-started/introduction/) were used extensively in aid to solve code issues along the way.

When browsing the website on mobile the offer.html page contains "More Info" buttons that display the content onClick. This was created using custom JavaScript. I have used [this](https://stackoverflow.com/questions/32153720/how-to-make-button-show-content-onclick) stack overflow question to get an idea how to accomplish this task and edited the code to suit my needs to the best of my ability.

#### Inspiration

I have been partly inspired by the website of [Goldstone Fitness Gym](https://www.goldstonefitness.ie)

_This project is for educational purposes only_
