# Horiseon-work-up
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title



<!-- Horiseon online marketing mock up  
Has 7 images 

This is my secont attempt at this so lets hope all goes well



Currently there is no deployed application. 
Running the application locally there are a few areas of improvement: Title, Semantic HTML, Alt Attributes, Links, CSS consolidation and CSS comments. 
<!-- You did change the title of the site, but it should reflect the actual page. Something like Horiseon.  -->
<!-- For the Semantic HTML: Index.html line 11: instead of a div tag, maybe a header element Index.html ---> 
<!-- line 13: instead of a div tag, maybe a nav element Index.html  -->
<!-- line 28: instead of a div tag, maybe a main element Index.html  -->
<!-- line 29,36,43: instead of a div tag, maybe a section tag Index.html  -->
line 51: instead of a div tag, maybe an aside 
Index.html line 52,59,66 instead of a div tag, maybe an section tag 
<!-- Index html line 74:instead of a div tag, maybe a footer tag  -->
Regarding the alt attributes, you have 6 images, when you have an image, you want to add an alt attribute to help with accessibility. 
Regarding the link not working, I would look at line 29 and see what is different from that and lines 36 & 43 of the html. 
For Consolidating: Style.css line 89/94/99, if you notice all these are the same. So instead of making a different named class for each. Make 1 class(call it what you like), and change the class of the three that you changed in the style.css, in the index.html as well. You can do this same thing for the other duplicates throughout the styles.css. 
You also want to add some comments to the CSS, things like the location of the element you are dealing with are great, things like Header/Footer/Aside etc. 
Regarding the repo itself, you want to have a descriptive and extensive commit history. They are great for “save points” in your code, not only in case something broke at some point and you have a way to reference it, but also you can look back and read your thought process on how you did things(and future employers can as well). 
For the name of the repo, you want to use a name that describes the application. Avoid using just Module/Challenge/Homework #. Instead something like Horiseon Refactor. Currently the repo has a lot of extra files in the root, you want to get rid of unnecessary files and add folders to store things like the css and other assets. 
Regarding the README, you want to make sure to have, at minimum, a description, a screenshot and link to the live site/application. Think of the README as an “Advertisement and Information page” for the application/website.
