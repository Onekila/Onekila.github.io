# Hosting and Formatting a Resume using Markdown, VS Code, GitHub Pages, and Jekyll

## Purpose

The purpose of this README is to provide practical steps to help computer science student host and write their resumes using popular and current techinical documentation tools as described in Etter's Modern Technical Writing. (GitHub Pages, Jekyll, Markdown, and Visual Studio Code). Additionally, it helps student better understand Etter's book by pratcing the tools and model he recommends.

## Prerequisites

Before following the instructions below, you must have a resume formatted in Markdown. If you need help with how to use Markdown, please see [this Markdown tutorial](https://www.markdowntutorial.com/).

## Instructions

### Step 1: Create a GitHub repository

The first step is to create a new repository on Github

1. Go to GitHub.com and log in to your account.
2. Click on the "New" button on your GitHub homepage.
3. Name the repository "yourusername.github.io" and make it public.

### Step 2:

1. Go to your repository.
2. Click add file.
3. Upload your README.md file.
4. Commit changes.

### Step 3: Create a Jekyll site

1. Install jekyll. Here is a tuitorial to teach [how to install jekyll](https://jekyllrb.com/)
2. Execute command in terminal "jekyll new my-awesome-site" to create a local site.

### Step 4: Customize your Jekyll site

Edit the `_config.yml` file to customize your site. Here are [comfiguration options](https://jekyllrb.com/docs/configuration/)

### Step 5: Add your resume

1. Open your site folder.
2. Go to `_posts` folder.
3. Rewrite the file with your resume

### Step 6: Preview your site

Preview your site locally by running the following command in your terminal: jekyll serve

![Alt text](/Users/laisimon/Desktop/DeskTop/Assignment/comp3040/7863364_A2/gif/View_resume.gif)

![Alt text](https://github.com/Onekila/Onekila.github.io/blob/main/gif/View_resume.gif)

## More Resources

1. [Markdown tutorial](https://www.markdowntutorial.com/)
2. [Andrew Etter's book, Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
3. [GitHub Pages site with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll)

## Authors and Acknowledgments

Author: Jiehao Lai

Group members: Mia Battad, Yash Vyas, Yirong Wang

## FAQs 

### 1. Why is Markdown better than a word processor?

A: Markdown is better than a word processor as it is simpler and faster to use. It produces cleaner and more consistent HTML output. Additionally, Markdown allows for quick and easy formatting of text and does not require the use of a mounse or menu bar, making it faster and more efficient to use.

### 2. Why is my resume not showing up?

A: There are several reasons why your resume may not be showing up, including errors in formatting, incorrect file names or file locations, or issues with the repository. Also it may take a few minutes for GitHub Pages to update your site after you push changes.
