# **brad-coleman-portfolio**


# **Table of Contents**
1. [Description](#description)
2. [Testing](#testing)
3. [Technology Used and Credits](#technology-used-and-credits)
4. [Learnings](#learnings)
5. [About the Author](#about-the-author)
6. [License](#license)

[Visit the Deployed Site](https://bradcoleman60.github.io/brad-coleman-portfolio/)


# **Description**

This goal of this project was to to create my first website with no starter code and use many of the concepts that I learned in the first week of boot camp.  Here is a recap of the concepts of web development that I did not have any exposure to prior to my first week of this boot camp:

1. Basic and some advanced CSS including linking an external style.css file in the index.html file.
2. Use of semantic elements in HTML code.
3. General construct of a standard HTML page including the components of Head, Header, Main and Footer.
4. CSS Flex Box that allows the components of this website to flex (stretch or shrink) based on the size of the browser window. 
5. Media Queries that all the flex direction to change from "Row" to "Column" based on a screen size limit of 768px. 
6. Added effect on the hover to a linked image.
7. Use of an ```<a>``` tag to an entire section (or card) so that when the card is pressed, the visitor is sent my application.
8. Git commands of add, commit and push.


# **Highlighted Code Example**

The following is highlighted code that I created.  This particular snippet highlights one of my learnings during this project.  I inserted a link to the main project I wanted to highlight, but found that the link opened my application in the same browser window.  I found that this would be confusing to the visitor.  I researched how to open the link in a new browser window on Google and found the [target-"_blank"] syntax accomplishes this.  

```
<section class="container_1" id="main-project">
        <a href="https://bradcoleman60.github.io/marketing-refactor/" target="_blank">
        <div class="card_1">
            <h1>Code Refactor</h1>
            <p>In this project I refactored existing HMTL and CSS to add semantic elements and instituted aaccessibility ccessabilty standards. </p>
        </div>
        </a>
    </section>

```

# **Testing** 

N/A

# **Technology Used and Credits**

I used many useful references in completing this project including the following.  In particular, I found the layout of the w3schools reference materials to be extremely intuitive and helpful.  They even have a "try me" feature where elements of code can be reviewed and tested. 

- [W3Schools - HTML Code reference:](https://www.w3schools.com/html/default.asp)
- [W3Schools - CSS Code reference:](https://www.w3schools.com/css/default.asp)


# **Learnings**

I have many learnings  on this project.  The main learning was on the use of flex box - a CSS element  that allows components to shrink and grow in relation to the size of the window.  I started with a blank HMTL file and created a couple of containers.  To aid in this learning I temporarily applied a border around each container.  This allowed to see how the containers (or boxes) were reacting to the different flex display parameters that I applied.

Additionally, this is the first website that I built that contains a media query.

Lastly, though intuitive and a lesson I have learned throughout my career, collaborating with fellow bootcamp students is very rewarding.  I was able to see different viewpoints and approaches to understanding the concepts of this project.  Additionally, I was exposed to several short cuts and tricks when using VS code.   

# **About the Author**

My name is Brad Coleman. I am fairly new to web development but have considered it a hobby for several years and have hacked my way through learning various aspects including php, html and mysql.  I am currently enrolled in the Cal Berkeley Extension Web Development Boot camp and am excited to learn web development more holistically.  I have spent my earlier career working as a corporate controller / CPA.

- [Linkedin Profile](https://www.linkedin.com/in/brad-coleman-109529/)
- [GitHub Repos](https://github.com/bradcoleman60?tab=repositories)


# **License**

MIT License

Copyright (c) 2022 Brad Coleman

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.