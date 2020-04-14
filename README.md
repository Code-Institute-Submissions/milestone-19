#Goku Gym

This milestone project was used to build a website for a fictional local small business, specifically a gym. The website will allow the gym to draw attention to their offerings, what makes their trainers stand out amongst the crowd, all while showcasing touching testimonials from existing clients. The website will be online hub as destination for all their marketing efforts online offering the most important information that clients may be looking for inlcuding multiple contact methods. The website will also try to attain email subscriptions so the owner of the gym can continue to market to them through another channel.

## UX

As the small business owner did not have a lot of copyright and marketing content, we decided on building a one page scrolling website instead of a multi page website. It was decided that the website can be later converted to a multi page website by distributing the sections to their respective pages and maintaining the header as well as expanding on the footer to make it more aligned for a multi page website.

The website was built with the brand colours in mind with many visual aids to help project the message. A lot of whitespace was used to ensure easy legibility and processing of the information provided. Large jumbotron was used to provide contrast and to divide up the whitespace at times.

###User Stories

John visits the website to contact the gym to gain more information. He was able to easy navigate to the contact section and call using the phone number. If by chance, he did not want to call, he has the option to send an email using the contact form or the email address included.

Jane visits the website to compare the facility and trainers with another local gym. Using the easy to use fixed header, Jane was able to navigate through the entire website digesting information about the gym including the features of the facility, information about the trainers, and testimonials from their advocates. Once satisfied she was able to contact and sign up.

### Wireframe

Please find the wireframe below:


## features

### Header & Navbar

The header consists of a logo aligned to the left and a navbar aligned to the right. The logo was made using a vector image and a custom font. The navbar was created using bootstrap example and modified heavily except the toggle button. The toggle button is used to collapse the menu on smaller screen sizes ensuring a seamless transition from larger screen to smaller screens wihout affecting the layout of the entire header.

### Main Jumbotron 

The main jumbotron section is a full screen image used to draw the attention of the visitors. An image with a lot of contrast against the header was used. In order to ensure that the header and image did not overlap and the image did not exceed past the fold of the page, a calc function was used to determine the right height for the image. The image container was given a relative positioning so the overlay textbox can be positioned using absolute positioning.

### Features 

The features section was divided up into three columns and the remaining space was ignored as the content was centered using a built in bootstrap class. The features section used an icon from font awesome, heading, parapgraph and image to convey each point.

### Trainers 

This section introduced a section title that would be used in other sections repeating the same style. The trainers section was comprised of columns of different sizes. The smaller sized column was used to illustrate an image of the trainer whereas the larger column was used to indicate the name of the trainer, the role, and the bio.

### Email Subscribe

A full width jumbotron was used to create a division between the sections. This section used a full image background with a color that contrasted with the white background of the previous sections. The jumbotron had an overlaying row which had its opacity lowered to make the image see through. The textbox contained an email input along with some verbiage to motivate the visitor to subscribe to the gym's email list.

### Testimonials 

The testimonials section used the same layout as the features section amd the title introduced in the trainers section. The icons were removed and the image was moved to the top. The CSS had to be adjusted to make sure good spacing between elements as things had been rearranged.

### contact

The contact section again used the title created before. This section was divided up into 2 even columns. The left column contained contact information illustrated using icons, headers, and parapgraph text. The right column had a contact form made using placeholders as opposed to labels to provide a cleaner look. The contact section was completed with a full width brand coloured banner including links to all social media websites.

### Footer 

The footer simply consisted of a copyright statement in the brand font.

### Features Left to Implement

If the website was to be expanded to a multi page website, a more comprehensive gallery along with videos should be included. Also, a calendar should be provided that can be used to register for upcoming classes. Also, a multi page website will require the footer to be more comprehensive.

## Technologies used

HTML - Used to build basic content of the website
CSS - Used for complete styling of the website 
Bootstrap - Used to assist in creating the grid layout to align the content propertly
JavaScript/jQuery - Used to implement the toggle functionality for the navbar
Google Fonts - Used to use custom fonts on the website
Font Awesome - Used to input icons in the website wihout having to downlaod them

## Testing

The testing process was a constant process. As each section was reaching its end, the website would be tested again to ensure that nothing "broke". If a bug was realized, it was fixed first before moving on to the next section. This method makes it a lot easier to find the bug as opposed to having to comb through the entire website.

The webstie was throuhghly tested in multiple browsers (Firefox, Chrome, Edge, Safari, and IE). The website responsiveness acted correctly in all browsers.

The website was also observed in many different mobile and tablet resolution using Google Developer Tools, again acting as expected. 

The website was tested in W3C HTML & CSS validators and no errors were realized.

## Deployment

The website was pushed to github using gitpod. Once the final version of the website was committed and pushed, the website was hosted using gitpage. 

Please find the live website here: https://umujtaba-ci.github.io/milestone-1/

Currently the live version and development versions are identical. 

## Credits

### Content

All text content was created by myself. No content was copied from elsewhere.

### Media 

The logo image was attaing from www.flaticon.com with a free license for personal use.

The icons were inputted using Font Awesome

The images throughout the website were all attained from www.pexels.com againg with a free personal license.

### Acknowledgements

Code Institute - Learning from the code institute program were applied
Bootstrap - Bootstrap documentation was referenced to ensure Boostrap 4 was being utlized propertly
