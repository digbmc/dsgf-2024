# 04. Web Development

2024.10.24

## Agenda
1. Updates on logs
2. Review GH Pages
3. HTML & CSS

### Business

- Updates & announcements
- Other business

## Meeting notes
Note-taker: Yuzhu (HTML & CSS worshop only)

### HTML Basics
- HTML stands for Hyper Text Markup Language
- Anatomy of the HTML file: the structure is like a tree with branches and elements
  - Doctype need to be specified at the top
  - Each root element is demarcated by a set of opening `<html>` and closing `</html>` tags. 
  - Two main sections of all HTML documents: a head section (demarcated by `<head>` and `</head>`) and a body section (demarcated by `<body>` and `</body>`).
- Elements and tags
  - Common elements include: **div**, **p**, **img**, **h1**, **h2**.
  - Most elements must have an opening and a closing tag, with content in between (i.e. `<div>` and `</div>`).
  - The content in between can be additional elements creating the branch structure
  - Some elements are self-closing (i.e. `<img/>`)

### CSS Basics
- CSS stands for Cascading Style Sheets 
- Critical concepts:
  - cascading: later rules will override the previous rules
  - specificity: more specific selectors override less specific ones
  - inheritance: some CSS properties are inherited from the parent elements. 
- CSS establishes a set of rules that define how particular HTML elements are displayed. 
- Each rule includes: a selector (i.e. **h1**), a set of curly bracket (i.e. **{}**), one or more declarations of property and value within the bracket (i.e. **color: orange;**) 
- Common CSS Properties include: **font-size**, **font-family**, **color**, **background-color**, **width**, **height**.
- No need to memorize anything. You can always check a cheatsheet or use online resources (i.e. W3Schools) during development. 

### Integrating CSS and HTML
- HTML provides the web content, CSS provides the styling
- There are multiple ways of integrating CSS and HTML (inline, internal, and external). In this workshop, we practiced together the external way of linking them. 
- In order to make the documents readable (for both computers and humans), keep it clean and well-organized (i.e. add space to seperate different attributes, and consistently use proper syntax)

### Activity: Make a Website Using HTML and CSS
- Create a folder on our computer and open it with VS Code
- Add two files: index.html and style.css
- In index.html, add basic html sturcture and a link to style.css
- Open the html and check the updates on the web
- We then added images, paragraphs, header 1 and 2, and some other content; we also practiced defining color, font-family, background color, and more in style.css
- Remember to save your files or else you won't see your changes when you refresh the site

### Deploy Your Site to a Domain
- Guideline provided in resources
- The site you make only lives on your computer (locally) until you get it uploaded to a server

### Final Notes: Building Your Own Website
- It is important to understand how HTML and CSS work because the more you know, the more you can customize. And when you run into issues with webpages, you will be able to troubleshoot them easily
- Compared to Github, which can convert markdown into a basic website, CSS and HTML allow you to create and customize one for your needs
- Github page is a free way to host websites even after we leave Byrn Mawr, but Worldpress requires a subscription fee
- Github themes are modular: they allow you override some of the content from other themes default

### Next Session
- We will be working on 3D Scanning
- Session will likely be set up in the special collection room. More information to be shared.


## Review GH Pages

- Workshop: [Github Pages (DSRI)](https://github.com/tri-cods/github-pages)
  - Last time -- left off at [content](https://github.com/tri-cods/github-pages/blob/main/sections/05-content.md)

### Web Development with HTML & CSS
- [Activity](../resources/html-instructions.md)
- [Web Development: HTML & CSS slides](https://brynmawr-my.sharepoint.com/:p:/g/personal/amcgrath1_brynmawr_edu/Ebk0Itz2FClIj1Sbk5boNCYBa7Ip2LI8AAozEOYU8XJjFw?e=xixKog)
- [HTML & CSS tutorial](https://github.com/tri-cods/html-css)

#### HTML & CSS Resources
- Learning HTML
  - Self-paced interactive [HTML Tutorial](https://www.w3schools.com/html/) from w3schools.com
  - Free Code Camp [Responsive Web Design course](https://www.freecodecamp.org/learn/responsive-web-design/#basic-html-and-html5)
  - LinkedIn Learning: [HTML Essential Training](https://www.linkedin.com/learning/html-essential-training-4/) (2h 45m)
- Learning CSS
  - [CSS Diner](https://flukeout.github.io/)
  - Self-paced interactive [CSS tutorial](https://www.w3schools.com/css/) from w3schools.com
  - LinkedIn Learning: [CSS Essential Training](https://www.linkedin.com/learning/css-essential-training-3/) (4h 28m)
  - Templates and models
    - https://html5up.net/
    - http://www.csszengarden.com/


## Action items
- [ ] Add your updates by Wednesday morning
- [ ] Other

[<<< Previous](03-github-pages.md) | [Next >>>]()

[Return to syllabus](../syllabus.md)

[Home](../README.md)
