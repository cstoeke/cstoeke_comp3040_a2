# How to host a resume on GitHub Pages using Jekyll and Markdown
- - - 
### Purpose: 
Describe the practical steps of how to host and format a resume using Markdown, GitHub Pages, and Jekyll.
### Secondary Purpose: 
Relate the practical steps described above to the general principles of current Technical Writing, as explained in Andrew Etter’s book Modern Technical Writing
### Prerequisites: 
- A Markdown formatted resume (Example in mine: https://cstoeke.github.io/cstoeke_comp3040_a2/index )
- A GitHub account

- - -
![animated gif](https://media.giphy.com/media/2WD7iXievQaqFm2T7p/giphy.gif)

**Instructions:**

1.  *Create your resume using a Markdown-formatted file.* You can either generate the Markdown styling yourself in something as simple as notepad, or use an online editor such as ![dillinger](https://dillinger.io/) to live preview as you type and make changes. Once you have finished creating your resume and are satisfied with the results, make sure to save it as a Markdown file, with the extension of *.md*. We want to name this file "*index.md*" in order to save some time in the following steps. Ensure that you update your resume for each job you are applying for, as is in accordance with Andrew Etter's recommendations for defining the audience in his book *Modern Technical Writing*. 

2.  *Create a new repository in your GitHub account to host your resume.* If you do not already have a ![GitHub](https://github.com) account, be sure to create one with professional information, as since you are hosting your resume here, prospective employers will be able to see your information. It is recommended, as stated in Etter's book, that you create a central website rather than creating and distributing PDFs of your writing, and as such it is going to be a boon to have your resume hosted on a GitHub site like we are setting up.

3.  *Add README.md and _config.yml files to your repository.* These two files will provide information regarding the contents of your repository, and provide code for configuring a Jekyll theme for your resume. Make sure to populate the information you wish to provide in the README. The _config.yml file will look something similar to the following: 

`title: My Resume`

`author: Cain Stoeke`

`email: cstoeke5@gmail.com`

`theme: jekyll-theme-midnight`

This file's settings will be applied to any other pages you wish to host within this repository as well, satisfying yet another of Etter's recommendations for removing duplication of works. By applying the same settings in our _config.yml file to all other files we wish to manage, we minimize the amount of duplication required. You can also change the Jekyll theme of your resume by going to the repository's settings, under pages, and change the theme from there while viewing a preexisting preview of each theme available. 

4.  *Finalize your resume.* You can preview your resume's results by going to the link listed in the repository's settings and under pages. There it will list the link that your site is ready to be published at, and it is with this link that you can share your resume to others. By changing your Jekyll theme, the format of your website will also change, so try out several versions of your website before settling on the best one for your tastes and uses. 
- - -
### More Resources: 
https://www.markdownguide.org/cheat-sheet
https://dillinger.io/
https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS

## Authors and Acknowledgments: 
### Group Members: 
- Aman Preet Singh
- Johnson Makumator-Jones
- Hong Gao
- Adam Kroeker

### Author: 
- Cain Stoeke

Theme by ![mattgraham](https://twitter.com/mattgraham)

Special thanks to Andrew Etter for his book *Modern Technical Writing*.


- - -
## FAQ

### Why is Markdown better than a word processor?  
- Markdown allows for better control that is more widely applicable than typical word processor formats, as well as its simple syntax is quick and easy to learn. It also allows for certain HTML-like commands to be used, which overall allows for easy set-up and management, while also providing a high amount of control over the finer details of your work.

### Why is my resume theme not updating?  
- If you are using a Jekyll-based theme and changing it through the repository settings, it may take anywhere between 5-20 minutes to update. Be patient, refresh the page, and check back later if it's still not updating. 
