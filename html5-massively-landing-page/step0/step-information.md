# Build the HTML structure

In this project will be try to build the Massively Landing Page and bring our web page design as close as possible to the original design


## 1: Getting the basic boilerplate of the landing page ready 

We would need to add a h1 heading along with the paragraph for the hero section. Create a section with the id 'header' and add the h1 and p tags inside it. 

Add the text from the image to the elements.

## 2: Add the arrow down icon

Your HTML already has Font Awesome CDN link added to it. You would just need to add the classes to add the arrow down icon. 

```html
<i class="fa-solid fa-arrow-down"></i>
``` 


## 3: Add the navigation bar

Now that we are done with the header. Create a new `<nav>` tag and setup two sections inside the nav tag, one for tabs and the second for the socials. 

Create a simple `<a>` tags for the tabs inside the first section. For adding social icons in your web page. We would be making using of Font Awesome icons. 

```html 
<i class="fa fa-twitter" aria-hidden="true"></i>
``` 

## 4: Creating the header blog
Inside the `<main>` tag create a simple post setup with an date,image, title and a paragraph. The images are already available to you in the `assets/images` folder. 


## 5: Creating the blogs section 

Now that we are done with the header blogs, we would have to setup the rest of the blogs that are visible on the page. You can create a separate container to hold all the blogs. All the images are available in the `assets/images` folder 

You can create the pagination component on your own, or you can choose to ignore it for this project as we won't be making it functional

## 6: Building the form & the footer
As per the design shared with us, the form has two sections, on the left side we have the form and on the right side we have the footer. 

Create a `<footer>` tag and a form tag inside and add the form elements to the name, email and message (text area) and a submit message with the value of "Send message". 

In the second section of the footer, we would be building four separate boxes with each containing a short headings and it's content. 

We will be using the same set of icons that we have used in the navigation bar. 


