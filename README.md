# CI-MilestoneProjectOne

uGym is a made-up gym based in Shavington, Crewe.

This website has been designed to display the offerings of this local gym to encourage the local populus to sign up to the gym.

The website has been designed to look professional and showcase the gym offerings.

## Live site
A live demo can be found [here](https://lewisclark4.github.io/CI-MilestoneProjectOne/).

## UXD
### User stories

**Prospective Customer 1** 
This prospective customer is relatively well accustomed to the gyms in the local area, and is therefore looking to identify either the cheapest (or perceived best value) gym in the local area.

**Prospective Customer 2**
This prospective customer is keen to find the gym in the local area that caters for all of their training requirements, and therefore wants to be able to view all of the facilities in the gym.

**Prospective Customer 3**
This prospective customer is a fitness enthusiast, but is not a 'traditional' gym-goer, and is more interested in the different fitness classes that the gym has to offer.

**Prospective Customer 4**
This prospective customer is completely new to the world of fitness, and wants to be able to learn from friendly and knowledgeable personal trainers.

### Strategy
My goal in the design was to make the site very visual with lots of images, and minimal amounts of text for the customers to read. 
Ultimately the client is looking for a gym and just wants to see what facilities and services are available.

### Scope
The scope was to try and cater customers of all fitness levels & experience. Therefore it was very important to identify the key customers needs.

I narrowed this down to;

1. Cost
2. Facilities provided
3. Services provided (fitness classes etc.)
4. Personal training

### Structure

Ultimately, the cost of services is the biggest driver in customer purchases, and they want to get the most value for their money.

It was therefore key to highlight the cost of joining the gym in the first instance, which is clearly displayed as the customer lands on the site.

It was then important to show the value for money, and displaying all of the facilities, classes and personal training options provided by the gym.

Each of these can be easily navigated by scrolling down the page, or using the scrolling features in the navbar links.

It is also important for customers to be able to contact the gym should they need to.

### Skeleton

[Mobile wireframe](https://github.com/lewisclark4/CI-MilestoneProjectOne/blob/master/Wireframes%26Plans/Milestone%201%20Project%20-%20Mobile%20Wireframe.pdf)

[Desktop wireframe](https://github.com/lewisclark4/CI-MilestoneProjectOne/blob/master/Wireframes%26Plans/Milestone%201%20Project%20-%20Webpage%20Wireframe.pdf)

## Technologies
1. HTML
2. CSS
3. Bootstrap (3.3.7)

## Features
### Nav Bar 
The navbar contains links to each section of the page, and a smooth scrolling feature has been added to make the site more professional.
This allows the prospective customer to quickly navigate to the information that they are looking for.

### Sign up button
There is a visible sign up button on the landing page, that the client can click on which opens a modal to allow the client to begin the sign up process and select the type of membership they would like.

### Facilities
The facilities section contains a carousel, which automatically scrolls through a number of images of the gym's facilities. 
The prospective customer is also able to cycle through the images at the click of a button.

###Contact
This section of the site details address, phone number and email address for the gym, as well as a 'send a message' modal, allowing a prospective customer to submit queries online. 

It also includes iframe of Google Maps displaying the location of the gym and the local area.

## Future Features to implement
The next iteration of the site should include calendar of the fitness classes available, detailing start & end times. This could be an additional webpage, or available for download (or both).

## Testing
I have run my HTML and CSS code through the W3C validation websites.

[W3C Markup Validation Service](https://validator.w3.org/)

[W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/)

This allowed me to identify any issues with my code, such as incorrect/ missing closing of div tags, duplicate ID tags etc.

I frequently used [Responsinator](http://www.responsinator.com/) and Google DevTools, to allow me to test the responsiveness of my site across different devices & resolutions.

### Nav Bar
1. Test links to all page sections work
2. Test links change color on hover.
3. Test toggle works on smaller devices.

### Landing page
1. Test image responsiveness across devices (fullscreen)
2. Ensure pricing and sign up feature visible on the landing page across all devices and resolutions.

### Sign up button
1. Test clicking button and modal is opened
2. Test that I am only able to select one radio button (not able to select multiple at the same time).
3. Test that I am able to fill out all of the data boxes.
4. Test that I am able to click the send message button.
5. Test that I am able to close the modal if required.


### Facilities
1. Test that the images automatically cycle.
2. Test that I am able to cycle through the images manually.
3. Test image responsiveness across devices (does not blur or distort).

### Classes
1. Test image responsiveness across devices.
2. Test breakpoints/ some classes are hidden on smaller devices.

### Trainers
1. Test image responsiveness across devices.

### Contact
1. Test responsiveness across devices.
2. Test I am able to open, or scroll across the map to see the wider local area for directions.
3. Test that I am able to select the email address to send an email to the gym.
4. Test that I am able to select the phone number to call the gym.

#### Send a message modal
1. Test clicking button and modal is opened
2. Test that I am able to fill out all of the data boxes.
3. Test that I am able to click the send message button.
4. Test that I am able to close the modal if required.

### Socials
1. Test that the color on hover changes.
2. Test that the links take you to the respective social pages.

## Deployment
The site is deployed on GitHub. 

1. Create a git hub repository.
2. Open in GitPod
3. Create index.html file.
4. Add the file to staging area using the command git add index.html (or git add .)
5. We then want to commit the file, with the command git commit -m "Intial commit" (standard practice for the first commit into a repository).
6. We then want to push the file back to the repository, which can be done with the command git push.
7. You should now be able to see this commit in your repository.
8. You can repeat steps 5-7 for any further updates to the file (though your git commit message should contain more detail regarding the updates).
9. In your repository, select the settings option.
10. Scroll Down to the github pages section and click on the dropdown option under source, and select master branch.
11. This now publishes the site, and provides the URL to the site.

## Credits
### Content
All content was written by myself. 

I used many local gyms for ideas and comparison.

[Area51](https://www.area51gym.co.uk/)

[Simply Gym](https://simplygym.co.uk/gyms/crewe/)

[Total Fitness](https://www.totalfitness.co.uk/)

[Bannatyne](https://www.bannatyne.co.uk/health-club/crewe)

[Snap Fitness](https://www.snapfitness.com/uk/gyms/crewe/)

I utilised concepts from the 'Whiskey Drop' mini project to help with the design principles of my site, for example the overlay and the 'hiding' of items on smaller devices.

I also utilised various explanations on [Bootstrap](https://getbootstrap.com/) in the design of my page, such as the carousel, card and modal sections.

### Media
My images were sourced from the following stock images library, and were all free for use, sharing or modification, even commercially.

[Flickr](https://www.flickr.com/)

[Unsplash](https://unsplash.com/)

[Pixabay](https://pixabay.com/)

All of the icons on the page were sourced from [Font Awesome](https://fontawesome.com/)

### Acknowledgements
#### Anna Greaves
I used Anna's excellent "How to make a Kick Ass first Milestone" and UXD documents to help provide some structure and guidance to my project.

#### Cacoo
I used [Cacoo](https://cacoo.com/) to create my wireframes for this project.
