# Wicklow Motorcycle Tourers
Wicklow Motorcycle Tourers is the website for a motorcycle touring group based in Wicklow, Ireland. The intention of this [site](https://cmikedev.github.io/wicklow-motorcycle-tourers/) is to provide an overview of the meeting location and ride times for riders who wish to tour Wicklow with other like-minded riders and make use of a roadside bike shed.

The purpose of the site was to ultimately get users to sign up with the group. Given the nature of the group's activities (i.e. being dependant on weather conditions), only the bare minimum details of the weekly meet ups would be posted to the site with the intention that a user would sign up and receive detailed emails on each upcoming weekly meet.
____


![image](https://raw.githubusercontent.com/cmikedev/wicklow-motorcycle-tourers/main/assets/readme-images/am-i-responsive-screenshot.png)


## Deployed Website
[Wicklow Motorcycle Tourers](https://cmikedev.github.io/wicklow-motorcycle-tourers/)


## Repository
https://github.com/cmikedev/wicklow-motorcycle-tourers



## Structure

* The site is divided into four pages sharing common features (as detailed below):
    * Home
    * Rides
    * Bike Shed
    * Sign Up<br />
    <br />
* There is an additional 'Thank You' page which is only accessed once the sign up form is completed and submitted by the user.

## Styling

The colour palette is very subdued with only white, black and shades of grey being utilised. This was to frame the navigation, text and footer in a clear, clean way whilst maximising the sense of flow and engagement provided by the video.

Of the fonts available on Google Fonts I chose 'Lobster'. The stylised, italic nature of this font is one that is common to many motorcycle-centered websites, tshirts and other visuals and so might elicit a sense of familiarity to motorcycle riders.

## Features

* ### Navigation Bar
    * The navigation bar is featured on all pages where there is click-access. It is not featured on the 'Thank You' page which is only accessed via completion of the sign up form.

    * This allows the user to navigate across the website without having to use their browser's back button. The page name in the navigation bar is underlined when the user hovers over that page and is permanently underlined when a user is on that page allowing them to easily see where they are.

    &nbsp;
    ![image](https://raw.githubusercontent.com/cmikedev/wicklow-motorcycle-tourers/main/assets/readme-images/navbar-screenshot.png)
    &nbsp;


* ### Page Videos

    * Each page contains a video which was chosen to create a sense of motion through the site and elicit a sense of companionship and belonging and a desire in the user to get onto their bikes, thus going to the sign up page.<br />
    <br />
    
    #### Home page video
    &nbsp;
    ![image](https://raw.githubusercontent.com/cmikedev/wicklow-motorcycle-tourers/main/assets/readme-images/front-page-video-screenshot.png)
    &nbsp;

    #### Rides page video
    &nbsp;
    ![image](https://raw.githubusercontent.com/cmikedev/wicklow-motorcycle-tourers/main/assets/readme-images/rides-page-video-screenshot.png)
    &nbsp;

    #### Bike Shed page video
    &nbsp;
    ![image](https://raw.githubusercontent.com/cmikedev/wicklow-motorcycle-tourers/main/assets/readme-images/bike-shed-page-video.png)
    &nbsp;

    #### Sign up page video
    &nbsp;
    ![image](https://raw.githubusercontent.com/cmikedev/wicklow-motorcycle-tourers/main/assets/readme-images/sign-up-page-video-screenshot.png)
    &nbsp;


* ### Main Text
    * Overlaying each video is a text box providing an introductory welcome to the section as well as a link to the next page facilitating the users journey to the sign up form. The text boxes overlaying the videos are relatively opaqe and off-set so as to be obvious, legible but not interfere with the sense of motion created by the video.

    &nbsp;
    ![image](https://raw.githubusercontent.com/cmikedev/wicklow-motorcycle-tourers/main/assets/readme-images/front-page-text-box-screenshot.png)
    &nbsp;
    * The 'Sign Up' page differs in that the text box which contains the sign up form is centred rather than off-set and is not opaque. This is because the user will have reached our intended destination and so the sign up form is styled to stand out over the video in order to capture and hold their attention.

    &nbsp;
    ![image](https://raw.githubusercontent.com/cmikedev/wicklow-motorcycle-tourers/main/assets/readme-images/sign-up-page-text-box-screenshot.png)
    &nbsp;

* ### Information Section
    * Below the video and main text on the 'Home' and 'Rides' pages is a section providing some more information about the Wicklow Motorcycle Tourers and in the case of the 'Rides' page, ride times and an Embedded Google Map showing the meeting location.<br />
    <br />

    #### Home page
    &nbsp;
    ![image](https://raw.githubusercontent.com/cmikedev/wicklow-motorcycle-tourers/main/assets/readme-images/front-page-information-screenshot.png)
    &nbsp;

    #### Rides page
    &nbsp;
    ![image](https://raw.githubusercontent.com/cmikedev/wicklow-motorcycle-tourers/main/assets/readme-images/rides-page-information-screenshot.png)
    &nbsp;


* ### The Footer
    * The footer section contains social media links encouraging the user to connect and engage via social media.
    * The social media links open in a new tab allowing easy navigation for the user.

    &nbsp;
    ![image](https://raw.githubusercontent.com/cmikedev/wicklow-motorcycle-tourers/main/assets/readme-images/footer-screenshot.png)
    &nbsp;


* ### The Sign Up Form
    * The sign up form is located on the [Sign Up](https://cmikedev.github.io/wicklow-motorcycle-tourers/sign-up.html) page.
    * It allows the user to get signed up and be kept abreast of all ride information.
    * The form requires the user to input their first name, last name and their email before submitting.<br />
    <br />

* ### The Thank You Page
    * The 'Thank You' page is accessed once a user has filled out all required fields in the sign up form and submitted.
    * The page opens in a new window thereby not disrupting the users access to the main site.
    * The 'Thank You' page has purposely been designed to be minimalistic with many elements such as the header and footer being removed. 
    * A central image is added in place of a video to retain the minimalism but also the sense of motion.
    * The aim of this page is to: 
        * acknowledge the user providing their details
        * confirm that they have been received
        * direct them back to the main site via a link which opens in a new browser
    
    &nbsp;
    ![image](https://raw.githubusercontent.com/cmikedev/wicklow-motorcycle-tourers/main/assets/readme-images/thank-you-page-screenshot.png)
    &nbsp;



## Testing

### Responsiveness Testing

* The responsiveness tests were carried out manually using Google Chrome's [Inspect Function](https://developer.chrome.com/docs/devtools/open/). Some of the devices tested included (but not limited to):
    * Nest Hub Max
    * iPad Mini
    * Samsung Galaxy S8+
    * iPhone SE <br />
    <br />

* Testing on a real device (Samsung Galaxy S8) revealed that the footer social media links no longer lined up at that screen resolution:
    
    &nbsp;
    ![image](https://raw.githubusercontent.com/cmikedev/wicklow-motorcycle-tourers/main/assets/readme-images/samsung-galaxy-s8-links-overflow-screenshot.jpg)
    &nbsp;

* This was corrected and the footer social media links appear correctly in a row on the Samsung Galaxy S8:
    
    &nbsp;
    ![image](https://raw.githubusercontent.com/cmikedev/wicklow-motorcycle-tourers/main/assets/readme-images/samsung-galaxy-s8-links-corrected-screenshot.jpg)
    &nbsp;

### Validator Testing

* #### W3C
    * HTML
        * There were no errors or warnings within the HTML when checked through The [W3C HTML Validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcmikedev.github.io%2Fwicklow-motorcycle-tourers%2F)
    * CSS
        * There were no errors or warnings within the HTML when checked through The [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)<br />
        <br />

* #### Lighthouse (web.dev)
    * Lighthouse through [web.dev](https://web.dev/) was used to test the site for: 
        * Performance
        * Accessibility
        * Best Practice
        * SEO<br />
        <br />
    None of the results were below 90%<br />
    <br />
    ![image](https://raw.githubusercontent.com/cmikedev/wicklow-motorcycle-tourers/main/assets/readme-images/lighthouse-results-screenshot.png)<br />
    <br />
    * The full test results can be found [here](https://web.dev/measure/?url=https%3A%2F%2Fcmikedev.github.io%2Fwicklow-motorcycle-tourers%2F)<br />
    <br />


## Deployment

### Deploying the repository via GitHub
* The website was deployed using GitHub pages via the following steps:
    * In the Respository section, select the [wicklow-motorcycle-tourers](https://github.com/cmikedev/wicklow-motorcycle-tourers) repository
    * From the horizontal menu above the repository contents select __Settings__
    * From the left-hand vertical menu, go to the __code and automation__ section and select __pages__
    * From the __Source__ selection drop-down, select __Branch__ > __main__
    * The page will then automatically refresh displaying a ribbon indicating deployment status<br />
    <br />
    The deployed website can be found here - https://cmikedev.github.io/wicklow-motorcycle-tourers/<br />
    <br />

### Forking the repository
* The GitHub repository can be forked to make a copy of the original. This copy can then be viewed or changed without affecting the original repository via the following steps:
    * In the Respository section, select the [wicklow-motorcycle-tourers](https://github.com/cmikedev/wicklow-motorcycle-tourers) repository
    * At the top right of the page select __fork__ from the menu below your profile
    * A copy of the repository will now be created in your account

### Creating a local clone
* To create a local clone via GitHub:
    * In the Respository section, select the [wicklow-motorcycle-tourers](https://github.com/cmikedev/wicklow-motorcycle-tourers) repository
    * From the horizontal menu above the repository contents select __Code__
    * __Copy__ the link that that is shown
    * Within __Gitpod__ change the directory to where you would like the location of the cloned directory to be
    * Type __git clone__ and paste the link that you copied
    * Press __Enter__ and the local clone will be created<br />
    <br />



## Credits

### Content
* The favicon in the tile (page tab) was taken from [flaticon](https://www.flaticon.com/)
* The icons in the footer were taken from [font awesome](https://fontawesome.com/)
* The fonts were taken from [Google Fonts](https://fonts.google.com/)
* Code from the [Love Running](https://github.com/Code-Institute-Solutions/Love-Running-Solutions) project was utilised in the navigation, footer sections and social media links

### Media
* The background videos and background image were taken from [pexels](https://www.pexels.com/)
* The map was taken from [Google Maps](https://www.google.com/maps)

### Research and Guidance
* [Stackoverflow](https://stackoverflow.com/questions/20818881/use-video-as-background-for-div) was referenced for guidance on using a background video within a div container

----

## Acknowledgements
I would like to thank my course mentor Harry Dhillon for providing guidance on this project as well as Daisy Gunn and Tasha Johnson for providing styling inspiration for the README.