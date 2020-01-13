# Milestone Fitness Club

#### Stream One Project: User-Centric Frontend Development - Code Institute

Milestone Fitness Club is a fictional gym website. It provides details about the location of the gym, it's opening hours, facilities, classes and membership costs. It serves as both a marketing platform to encourage new sign-ups and as platform for existing customers looking for key information.

## Demo

A live demo can be found [here](index.html)

![Responsive Demo](assets/images/man-carrying-barbel-791763.jpg)

## UX

### Strategy
The overall aim is to attract new sign-ups and acheive the satisfaction and retention of existing members.
The website will enable users to find practical information about the gym to maximize their enjoyment of what is on offer (Appropriate classes, Awareness of opening times, Participation in events and challenges, access to support).
The target audience may be from different demographics. They are apirational individuals and may be looking to make a lifestyle change. The gym serves to help them commit to their goals and the project outcome should be positive, energetic and optimistic.

### Scope 
- The gym location, contact details, opening hours and membership costs are all vital pieces of information that should be available. 
- The facilities and class schedule are key to providing information about the value of joining Milestone Fitness Club.
- A downloadalbe downloadable timetable should be available to all users to be used as a reference tool.

Although it would be nice to have a feature that provides details of daily or weekly challenges, this would require skills beyond my scope, and should be left for a future feature.

### Structure
The Facilities section will provide photos and short descriptions of the facilities at the gym
A small map will appear in the general information section, but only on larger screen sizes.


### Skeleton
The Navigation menu is collapsed into a burger icon on mobile deives. The icon sits within a header at the top of the page and clicking on it triggers the navigation pane to slide in from off screen on the right. 

On larger devices, the navigation menu appears to have expanded. This is a separate header, not displayed on smaller devices. It is displayed over the background 'hero' image as opposed to appearing before it. 
#### Wireframes

### Surface
I chose to use Cyan and Magenta in my color scheme as I wanted the page to feel vibrant and energetic. The 'Orbitron' typeface from google fonts was chosen for the Milestone logo for it's modern and geometric form, as it helped to portray both robustness and refinement. I paired it with the Raleway font for use in the body text, as it was equally modern and appropriately legilble.

### User Stories
- As a customer looking to join a gym, I want to know what this gym has to offer and whether it will provide value for money
- As a customer looking to join a gym, I want find out where the gym is located and what time it opens
- As an existing gym member, I want to access the class schedule to see when my prefered class is available

## Features

### Existing Features
1.  ### Facilities
    Showcases what the gym can offer its mambers to serve their personal fitness journey. For example, a swimming pool, 2 studios, a fully quipled gym and a snack bar

1. ### Timetable: 
    A downloadable schedule to provide members with timings for the available classes.

1. ### Membership: 
    Provides 3 different membership options and the cost of each.

1. ### General information
    Provides other key information such as the location, contact details and opening hours.
 

### Features Left to Implement
- In the future I would like to provide details of daily or weekly challenges. This would help keep members engaged and motivated.
- Create a Members Section so that the login feature fully functions in taking the user to their own account page.



## Technologies Used

- **HTML** 
    Used for the general structure and flow of the page
- **CSS** 
    Used for overall styling and to add animations to the Navigation elemements
- **Bootstrap 4.4.1** 
    Used for providing repetitive styling to elements such as *text-uppercase* and also helped to create responsive layout in the 
- The project uses **Javascript** is used to provide the response to onclick functions- toggling a navigation menu to slide in 


## Testing

The employer and recruiter user story achieved the intended outcome of providing them with a showcase of myself and my work. In the about me section, they can read a bit about my background, and if they're viewing on a desktop, the background of this section is a photo of me. They are able to see my showcased projects via the project cards in the "Work" section. They can view both the live version and the GitHub repository by clicking on the Font Awesome icons. They are also able to view my social media profiles via clicking on the icons in the footer. They are also able to download my CV by either clicking on CV in the navbar dropdown, or by clicking on the document icon in the footer.

If you try to submit the contact form with an invalid email address, there will be an error noting the invalid email address. Furthermore, the 'required' attribute is added to the 'name,' 'email,' and 'message' fields, so if those fields are not filled in, the form will not submit. If all field are valid, the page will reload. If an employer or recruiter is interested in contacting me, they will have to fill out all fields in order for the form to go through.

All links will open in a new tab using 'target="_blank"' and the CV will download to your default folder for downloads on click using the 'download' attribute. All links have been manually tested to ensure that they are pointing to the correct destination.

By clicking on the links in the navbar, the scrollSpy effect will work regardless of whether or not you're viewing the sections in the same order they are listed in the dropdown navbar.

This site was tested across multiple browsers (Chrome, Safari, Internet Explorer, FireFox) and on multiple mobile devices (iPhone 4, 5, 7: Chrome and Safari, iPad, Samsung Galaxy) to ensure compatibility and responsiveness. During the testing phase, I realized that background-attachment: fixed was not compatible with iOS browsers. On Chrome and Safari in iOS, the background photos appeared zoomed-in and blurry. To fix this, the background-attachment: scroll property value was added in a media query

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named index.html.

To run locally, you can clone this repository directly into the editor of your choice by pasting git clone https://github.com/fran2488/milestone-fitness.git into your terminal. To cut ties with this GitHub repository, type git remote rm origin into the terminal.


## Credits

### Content


### Media
- The photos used in this site were obtained from Pexels.com, courtesy of Tim Savage and Victor Freitas

### Acknowledgements

