# Hosting Your Resume Online Using Markdown, GitHub Pages & Jekyll
### Purpose
The following instructions will allow you to take all the information you want on a resume, easily piece it together using Markdown and end up hosting it online using GitHub Pages with Jekyll formatting.  
This technique is a simple way to end up with a versatile resume format and an online version of your resume to share with potential employers.
### Prerequisites
No knowledge of Markdown, GitHub Pages or Jekyll is required.  
You will need a Markdown editor.  New users should go with [Atom.](atom.io)
### Instructions
The overall process is divided into: making your resume in Markdown, hosting this resume on GitHub pages and formatting its appearance with a Jekyll theme.
##### Writing Your Resume in Markdown
This step involves putting all your resume information together in a Markdown file using your Markdown editor.  If you are comfortable with Markdown, go for it!  Otherwise, here are the pieces you'll need.
1. Make sure you have a Markdown preview window open so you can see the output as you write it.  To open it in Atom, go to Packages > Markdown Preview > Toggle Preview.
2. You will need several headings to properly structure your resume.  Headings in Markdown are created by putting hash symbols '#' before the heading text.  One hash symbol makes the largest heading, six make the smallest heading and medium sizes can be made using 2-5 symbols.

>\# This will make a large heading.  
>\###### This will make a tiny heading.

* Use a large heading to put your name at the top of your resume.
* Use medium headings to create sections in your resume, e.g. _Education_ or _Work Experience_

3. For body text, no structuring is necessary!  Just start typing and watch your text appear in the preview window.
* Bullet points under each heading can help to structure your resume.  Simply start a line with an asterisk (\*) to create a bullet point.

> \* This text will be a bullet point.

* To distinguish certain parts of your resume, you can make text italicized by surrounding it with underscores (\_) or bolded by surrouding it with _two_ asterisks.

>\_This text will be italicized.\_  
>\*\*This text will be bold.\*\*

4. Ensure your completed resume is saved as index.md (.md indicates a Markdown file).

##### Hosting your Resume on GitHub Pages
Now that your resume is ready, it's time to get it online with GitHub Pages.
1. Make a [GitHub](github.com) account.  Fill out your account information and respond to the verification email.
2. Once logged in, create a [new repository,](https://github.com/new) which is where your resume will be hosted.
* Give it a name.  This will appear in its URL.
* Set it to _Public_.
* Check yes to _Initialize this repository with a README._
3.  Now, you'll want a git client.  Go for [GitHub Desktop.](desktop.github.com)
4.  With GitHub Desktop installed, you can now go to your main page at github.com and click _Set up in desktop_.
5. In GitHub Desktop, save your work.
6. You can upload your resume in the desktop or browser version.  It may be easiest just to drag the file into the big blank area on the left of GitHub Desktop.
7. Click the publish button to submit your changes.

Your resume is now almost ready to go live.  The final step in publishing it online is adding a Jekyll theme.

##### Formatting your resume using Jekyll

GitHub Pages requires a Jekyll theme for your website.  Though Jekyll is highly customizable, these steps are simply to get your page up and running.

1. On your main page at Github, go to the _Settings_ tab (on the far right).
2. Scroll down and click on _Change theme_.
3.  Choose a theme you like the look of and hit _Select theme_.
4.  This is sufficient for getting your page going, so check your repository URL to take a look at your resume!
> Note: Your changes can take some time to process, so the page may not appear for a few minutes.  

5. You may wish to change the title of your page to something more fitting.  This involves a tiny edit to your theme code.
* On your GitHub main page, go the the _Code_ tab (on the far left).
* Click on the file named ```_config.yml```.
* Select the pencil icon (on the far right) to edit the code.
* Add a second line to the text that reads ```title: My Resume or Whatever Title I Wish```.
* Scroll to the bottom of the page and hit _Commit changes_.

### FAQ
* Is it possible to align my text? For example, I want to put dates on the right of my resume.  
Unfortunately, no.  Markdown's strength is its simplicity, but in this case it is also its weakness as it doesn't permit advanced formatting.  Instead, maybe distinguish that text with italics.
