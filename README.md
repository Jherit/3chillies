# 3chillies
A single page built in HTML and CSS with some support for various screen sizes & devices via media queries.



## Installation 
Should you wish to download and run this page locally you might need some kind of [local server](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb). I would normally make **dist** my root but in this instance I've moved index.html up a few levels to make GitHub hosting easier. You may be able to load the local index.html in your browser without a server, it may just work. 

I used gulp and postCSS to do some light CSS tooling. With that in mind you will need to have node, npm and maybe npx installed on your compupter if you wish to make any changes once you've cloned the repo. 

Once installed, cd to the LittleLoft directory and do a:
`npm install`
to load the required node modules (based on package.json and package-lock.json).

When you edit the CSS files in **src/styles** you will need to use the following default gulp command to rebuild the dist CSS file:
`gulp`

Thanks 👋 


  

