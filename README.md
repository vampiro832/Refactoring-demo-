#  Horisin-Refactoring-code

## Descriptions

- my motivation is to acquire new skills in this field and to grow in the tech industry.  
- I took thins project on to improve my coding skills and broden my horizon in html and css.
- This project was to find and understand how to group recurring codes, find codes that where missing, and label html correctly.  
- I learned that labeling correctly is very important. Labeling somthing wrong can cause a webpage to not work properly. As well as having to much repetitive coding can make it look very cluttered and hard to understand.

## Usage 
  
### Some examples are these sests of code that contain to many div in the html code. As well as missing som information.   
    <div class="benefits">
        <div class="benefit-lead">
            <h3>Lead Generation</h3>
            img src="image"
            <p>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
            </p>

### I ended up replacing the div with aside and article, and added a description to the image. 
    <aside class="benefits">
        <article class="benefit-lead">
          <h3>Lead Generation</h3>
            img src="image" alt="gears funulling in to money"
            <p>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
            </p>

### Other changes that where done. was to the css. If you can tell all contain the same information within the code.  

    .benefit-lead {
    margin-bottom: 32px;
    color: #ffffff;}

    .benefit-brand {
    margin-bottom: 32px;
    color: #ffffff;}

    .benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;}

### In order to shorten this code I grouped the children together. It will give you the same results and keeps the code looking cleaner. 

    .benefit-lead, .benefit-brand, .benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;}          
          
## Credit 

I acquired this starter code from The Coding Bootcamp. Their link is https://github.com/coding-boot-camp/urban-octo-telegram.


