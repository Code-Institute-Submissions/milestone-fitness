# Milestone Fitness

#### Stream One Project: User-Centric Frontend Development - Code Institute

Milestone Fitness Club is a fictional gym website. It provides details about the location of the gym, it's opening hours, facilities, classes and membership costs. It serves as both a marketing platform to encourage new sign-ups and as platform for existing customers looking for key information.

## Demo

A live demo can be found [here](index.html)

![Responsive Demo](assets/images/man-carrying-barbel-791763.jpg)

## UX

### Strategy
The overall aim is to attract new sign-ups  and acheive the satisfaction and retention of existing members.
The website will enable users to find practical information about the gym, to maximize their enjoyment of what is on offer (Appropriate classes, Awareness of opening times, Participation in events and challenges, access to support).
The target audience may be from different demographics. They are apirational individuals and may be looking to make a lifestyle change. The gym serves to help them commit to their goals and the project outcome should be positive, energetic and optimistic.

### Scope 


### Structure

### Skeleton
#### Wireframes

### Surface

I chose to use Cyan and Magenta in my color scheme as I wanted the page to feel vibrant and energetic. The 'Orbitron' typeface from google fonts was chosen for the Milestone logo for it's modern and geometric form, as it helped to portray both robustness and refinement. I paired it with the Raleway font for use in the body text, as it was equally modern and appropriately legilble.

### User Stories
- As a customer looking to join a gym, I want to know what this gym has to offer and whether it will provide value for money
- As a customer looking to join a gym, I want find out where the gym is located and what time it opens
- As an existing gym member, I want to access the class schedule to see when my prefered class is available

## Features

1.  ### Facilities
    An overview of what the gym can offer its mambers to facilitate their fitness journey. For example, a swimming pool, 2 studios, a fully quipled gym and a snack bar

1. ### Timetable: 
    A downloadable schedule to provide members with timings for the available classes.

1. ### Membership: 
    Provides 3 different membership options and the cost of each.

1. ### General information
    Provides other key information such as the location, contact details and opening hours.
 
### Existing Features
- Feature 1 - allows users X to achieve Y, by having them fill out Z
- ...

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement
- In the future I would like to add

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

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

### Content
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
- The photos used in this site were obtained from ...

### Acknowledgements

- I received inspiration for this project from X