# Simple Static Site

## HTML - getting started

1. Use command line to navigate to the folder where you're keeping your dsgf files  `cd`
2. Create a new directory (folder) for your new site `mkdir my-site`
3. Create a document in the directory and name it 'index.html' `touch my-site/index.html`
4. Create a css document in the same place `touch my-site/style.css`
5. Open the project in VS Code
   Try `code my-site/index.html` - if that doesn't work, open VS Code --> File --> Add Folder to Workspace
6. In VS Code, open index.html. Add the boilerplate for a basic html document:

```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
    <head>
        <meta charset="utf-8">
        <title></title>
    </head>
    <body>
    </body>
</html>
```

1. Add some elements and text to the `<body>` element. Save it.
2. In Finder, open your index.html file with a web browser. You should see your website.
3. Give your website a title in the `<title>` element. 
4. Return to your browser and refresh the page. Do you see what changed?
5. Add an image to your page, and some placeholder text


## CSS

5. Link your CSS: in the 'head' section of index.html, type this:

```html
<link rel="stylesheet" type="text/css" href="style.css">
```

9. Open style.css and write some css to style elements from your index.html file. 
    
10. Save it, open your browser, and refresh it to see your styled page.

## Deployment

To get your site on the internet, you'll need web hosting — that is, a remote computer or server that will stay on day in and day out to serve the website to visitors. There are many options for web hosting, but we'll focus on [Domain of One's Own](https://digital.brynmawr.edu).

Your website is on a **subdomain** of the digital.brynmawr.edu subdomain, which mean that your url will include:

- The subdomain you chose: e.g. `alice`
- The subdomain for our webhosting service: `digital`
- Bryn Mawr's **root** domain: `brynmawr.edu`

1. Compress the folder containing your website and its assets (html, css, and images)
   - On a Mac: in Finder, select the folder and right click to open the secondary menu. Select 'Compress folder'
   - On Windows: press and hold or right-click the folder and select Send to > Compressed (zipped) folder
2. Log into your Domain of One's Own cPanel Dashboard and navigate to the **File Manager** 
3. Make sure you are in the public_html directory
4. Upload the compressed file and extract it into your public_html directory. This should create a subdirectory named 'htmlpractice' (or whatever you named that folder initially) that contains your `index.html` file and other assets it refers to.
5. The web address for your new site will be the url for your domain of one's own account followed by a backslash and the name of the subdirectory containing your site files:  `alice.digital.brynmawr.edu/htmlpractice` 
6. Open a separate browser or tab and navigate to this URL to see your site live on the web!

## Learning Resources
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
- Domain of One's Own [Tech Docs](https://techdocs.blogs.brynmawr.edu/web-authoring)