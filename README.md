# <center> Hosting and Formatting a Resume using Markdown, GitHub Pages, VScode and Jekyll<center>

## Purpose

The purpose of this README is to provide practical steps to help computer science students host and write their resumes using popular and current techinical documentation tools as described in Etter's Modern Technical Writing. (GitHub Pages, Jekyll, Markdown, and Visual Studio Code). Additionally, it helps students better understand Etter's book by pratcing the tools and model he recommends.

## Andrew's book highlights the importance of having an online resume

An online resume is easily accessible to anyone with an internet connection. You don't need to dupilcate your resume in pdf, word format again and again.Unlike traditional resumes that need to be print or sent to potential employers via email. Display your resume through the webssite. Here are some advantages. With an online resume, you have the ability to customeize your content and design your resume site. You can easily update your resume with new information or changes. In addition, you only need to update your document at one place. There are lots of static site generators which will help you create a simple static website. Making it possible to host them anywhere like Amazon and GitHub Pages. Markdown is the most widely used language in the world, it is easy to learn and use. 

## Prerequisites

- Before following the instructions below, you must have a resume formatted in Markdown. If you need help with how to use Markdown, please see [this Markdown tutorial](https://www.markdowntutorial.com/).
- Install Jekyll,VScode(optional) and required bundle
- A GitHub account


## Instructions

### Step 1: Create a GitHub repository

The first step is to create a new repository on Github

1. Go to GitHub.com and log in to your account.

2. Click on the "New" button on your GitHub homepage.

3. Name the repository "yourusername.github.io" (replacing "yourusername" with your GitHub username) and make it public.

### Step 2: Clone the repository

1. Click Code and copy your repository web URL
2. Open terminal.
3. Go to the directory you want to place your repository in terminal.
4. Clone the repository to your local machine using the command line in terminal:

```
git clone https://github.com/yourname/yourname.github.io.git
```

### Step 3: Add your readme

Drag your readme into your repository folder.

### Step 4: Create a Jekyll site

1. Install jekyll. Here is a tuitorial to teach [how to use jekyll](https://jekyllrb.com/)
2. Open terminal
3. Go to your repository folder
4. Execute command in terminal "jekyll new my-awesome-site" to create a local site.

### Step 4: Get everything into VScode(Optional)

To get your repository files organized I remmend you to use VScode to work with it.

1. Go to your repository directory in terminal
2. Run this command(**There is a space between code and .**) :

```
code .
```

### Step 5: Customize your Jekyll site

Edit the `_config.yml` file to customize your site. 
To make your site looks nice here are some tuitorial  [comfiguration options](https://jekyllrb.com/docs/configuration/)
Also you can find really good [jekyll theme](https://github.com/topics/jekyll-theme) provided. 
You can click fork on GitHub page and recustome it.(At this time I highly recommend you to work with VScode)

### Step 6: Add your resume

1. Open your repository folder.
2. Open `_posts` folder.
3. Rewrite the default file or drag your resume in this folder. The Markdown file in this folder should always named as  YYYY-MM-DD-Name.md. YYYY-MM-DD is the date

### Step 7: Preview your site

1. Preview your site locally by running the following command in your terminal: jekyll serve.
2. Open your browser and input localhost: 4000. (You can custom your localhost in `_config.yml`)

![Alt text](/Users/laisimon/Desktop/DeskTop/Assignment/comp3040/7863364_A2/View_resume.gif)

### Step 8: Upload your site folder

This is how you can upload on GitHub website

1. Go to your GitHub repository you have created.
2. Find upload files.
3. Drag everything  **in your site folder** on the drop box or choose all the files **in the site folder** .
4. Then commit changes
   This is the way you can upload in terminal
5. git add .
6. git commit -m 'Initial GitHub pages site with Jekyll'.
7. git push -u origin BRANCH

### Step 9: Find your GitHub page

1. Go back to your GitHub repository page.
2. Find and click settings.
3. Find Pages on the side navigate bar and click it.
4. Click visit site and you will see your resume


## More Resources

1. [Markdown tutorial](https://www.markdowntutorial.com/)
2. [Andrew Etter's book, Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
3. [GitHub Pages site with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll)
4. [Jekyll tutorial](https://jekyllrb.com/)
5. [jekyll theme](https://github.com/topics/jekyll-theme) 

## Authors and Acknowledgments

Author: Jiehao Lai

Group members: Mia Battad, Yash Vyas, Yirong Wang

## FAQs 

### 1. Why is Markdown better than a word processor?

A: Markdown is better than a word processor as it is simpler and faster to use. It produces cleaner and more consistent HTML output. Additionally, Markdown allows for quick and easy formatting of text and does not require the use of a mounse or menu bar, making it faster and more efficient to use.

### 2. Why is my resume not showing up?

A: There are several reasons why your resume may not be showing up, including errors in formatting, incorrect file names or file locations, or issues with the repository. Also it may take a few minutes 
