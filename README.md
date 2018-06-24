### Stream-1-project

## A project for Stream 1 module
1.	My objective is to create a simple to navigate web site regarding Garden Landscaping
- When hovering on the nav icon it will turn white.
- When you click on it turns neon green.
- Latest project nav bar icon has a drop down  function.
2.	My 1st objective is to create a simple nav bar
3.	Nav Bar 1: HOME
- The home page consist of a carousel in the centre. - It also has a Learn More button that takes you to the paragraph in the About us section of the page. 
The button was created using the modal class in bootstrap. This is available for users who do not want waste time and get straight to business. Basically you skip one step where instead of clicking on About us you can do what you need to from the Home itself.
- An additional link will take you to the Our Work section.
You can either navigate away from the box popup by clicking on either which links you interested in or click Close Me! which will close the popup box.
- You can also go directly to Contact by clicking on the form link.
4.	Nav Bar 2: About us
- This part of the website will have a video from youtube embedded as well the company motto.
- The form link takes you to the contact page.
5.	Nav Bar 3: Our Work
- The Our Work page goes into more detail on the images part of the carousel in the Home page.
- If you scroll down far down enough a Return back to the top button will appear. This is done using JS.
Again this is done to aid the user get back to the navigation quicker rather than scrolling to the top all the time.
6.	Nav Bar 4: Latest projects
- In this section I talk about the more extravagant projects on offer.
- Latest project is split in to 3 groups. Using the dropdown funtionality clicking on Latest Projects will create a dropdown that gives you the choice of 3 projects. Simply click on the on you wish to look at to navigate to the desired location.
7.	Nav Bar 5: Contacts
- Using Bootstrap a simple form is created.
- Inside the form fields are descriptions to aid the user on how to fill the form.
- There is also a separate box for the address details of the HQ.
- Like the Home page there are also the social media icons.
8. Create a carousel using bootstrap
- There is 8 images each with a description
- Also there is a video on the last slide of the carousel.
9. Create a button that popups with information window when clicked using Bootstrap (Modal class) and popover Javascript.
- Clicking on the button takes divulges the text in the About us section.
- Also it provides a shortcut to go to the Our Work tab.
- Another shortcut takes the user to the Contact for page.
10. Javascripts
- A javascript is used to create a dropdown in the Latest Projects tab.
- Also when clicking on Learn More on the first page inside the modal window higlighting the link will bring about a tooltip (Beautiful gardens).
- On the Our Work page there is a Javascript that if you scroll down far enough it will generate a prompt giving you the option to go right up the page.


## Testing


- In this Section we will cover the various tests for the website.

### Test 1
- Clicking on Home button while on the Home page does nothing unless Home is clicked from the other tabs in the Nav Bar.

### Test 2
- Clicking on About us takes you to the About us page no matter where in the site you might be. 

### Test 3
- Clicking on Our Work takes you to the Our Work page no matter where in the site you might be.

### Test 4
- Clicking on Latest projects does nothing instead a dropdown appears where you can choose any of 3 from Project 1, Project 2 & Project 3.

### Test 5 
- Clicking Contatc brings you to the Contatc page no matter where in the site you might be.

### Test 6
- Clicking on the left handed chevron takes you to the left of the carousel.
Clicking on the right sided chevron takes to the right of the carousel.

### Test 7
- Clicking on Learn More! will bring about a popover window. Inside the popover click on the hyperlink calle the link brings you to the Our Work page and clicking on form bring you to the contact page.
Further clicking on Close Me will close the window.

### Test 8
- On the Our Work page if you start scrolling down a prompt will appear giving you the option to go back to the top. For test purposes the page was scrolled all the way down then the Return Back to Top prompt was clicked. Once clicked the page was back in the top part as expected.

### Test 9
- Further testing was done by shrinking the the browser page and as expected. The navbar change dynamically to include te 3 bars icon. Clicking on the 3 bar icon reveals the navbar in vertical.

### Test 10
- The website was tested in mobile environment using different screen sizes devices. 