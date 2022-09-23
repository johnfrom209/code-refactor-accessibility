# code-refactor-accessibility

## Description

In this project I was given some starter code with some HTML and CSS files. Now that I have an understanding of HTML and CSS, this project was an opportunity to put my knowledge to the test. I was able to look through those files and find redundant code. My goal was to reduce the amount of repeated code and consolidate it into the appropriate class without changing how the website looked on a webpage.  

```
.benefits h3 {
    margin-top: 10px;
    margin-bottom: 10px;
    text-align: center;
}

/* the 3 below were moved into the .benefits h3 class */
/* .benefit-lead h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-brand h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-cost h3 {
    margin-bottom: 10px;
    text-align: center;
} */

```
There were plenty of repeated settings, so I consolidated them into a single group. In the example above I created the .benefits h3 and copied the settings over. I commented out the redundant code and saved the file which resulted in the same look. I repeated this for several other lines of code. 

## Installation

No installation required. Simply go to github pages to view the webpage.

[Github Pages](https://johnfrom209.github.io/code-refactor-accessibility/)

## Usage

This is a webpage for viewing. Refer to the image below for the final product.

![Screenshot of the website](./assets/images/changes_code-refactor-accessibility_.png)

## Credits

Starter code was supplied by UCB Coding bootcamp. 

[View my Github Repo](https://github.com/johnfrom209)

## License
