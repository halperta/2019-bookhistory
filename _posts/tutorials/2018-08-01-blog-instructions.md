---
layout: post
title: "Publishing a Digital Review"
modified:
categories: tutorial
excerpt: In this course, you will be invited to share a critical reflection with the public on this course website.  
tags: []
author: halperta
image:
  feature:
---
In this course, you will be asked to write and publish a critical review of a digital collection, using this course website as a platform ([more info](../../assignments)). You will do this using GitHub, an online platform for creating and sharing code that is owned by Microsoft.  

You can write your post in a text editor or directly on GitHub. For instructions on writing in markdown, open the [tutorial for writing in markdown](http://www.halperta.com/criticalarchives/tutorial/writing-in-markdown/).

To publish your post, you will need to learn how to:
* Create a GitHub account
* Fork a GitHub repository
* Write your article
* Upload your article
* Merge your changes

The basic principle for working with GitHub has to do with the way GitHub allows users to share work. On GitHub, users can create a temporary copy, or "fork," of someone else's project in their own account. You can make as many changes to the fork as you'd like. To make this website, for example, I made a "fork" of someone else's website, then modified it to suit my needs.  

As long as you are working with your "fork" of someone else's project, your changes won't impact the other project at all. But in this case, you will eventually want to merge your changes with the original project so that they show up on the website. These instructions show you how to do that.  

## Step 1: Creating a GitHub account
1. You can create a GitHub account here:  
[https://github.com/](https://github.com/)  
2. After you create an account, you'll need to verify your email before moving on to the next step.  

## Step 2: Fork the Critical Digital Archives Website  
[[Watch the video tutorial.](https://youtu.be/RDR-BhB-e84)]
1. Log in to GitHub.
2. Navigate to the GitHub project for the Critical Archives website. This is where all the files that make up the website are stored: [https://github.com/halperta/criticalarchives/](https://github.com/halperta/criticalarchives/)
3. "Fork" the project using the `fork` button on the upper right hand corner of the website.
4. When the "forking" is done, you will automatically be directed to a new copy of the website stored on your GitHub account. Its name should be something like "yourusername/criticalarchives", and it should say "forked from halperta/criticalarchives" in the upper left corner. This is now your copy of the project.

## Step 3: Create an author ID.
You'll need to create an author ID for the website so that your review can be attributed properly. To do this, follow these steps. Or [watch the video tutorial.](https://youtu.be/RDR-BhB-e84) (Note: turn on closed captions to view the text instructions.)  

1. Log in to GitHub and navigate to your fork of the critical archives website. If you don't remember the URL, you can find the fork among your repositories. Your repositories should be linked from your GitHub home page. 
2. **Important:** Change the branch from `master` to `gh-pages`. To do this, find the drop-down menu that says "branch" near the top left of the page, and select `gh-pages.`
3. Navigate to the "author" file (`_data/authors.yml`): 
	* Click on the `_data` directory to open it.
	* Click on the `authors.yml` file.
4. **Open the file for editing**: click on the pen icon in the upper right corner of the screen. 
5. **Create a biographical entry:** copy someone else's entry and paste it at the bottom of the document, replacing their information with your own info. At the very least, you should add a single-word author id, as well as your name. If you want to have a photograph of yourself to link to the page, enter the file name of the image, including the extension, under "avatar." It should look something like this:  

    authorid: oneword  
       name: Enter Name Here  
       email: email@utexas.edu  
       bio:  
       avatar:  image.jpg  
       twitter:  handle  
       google:  
         plus:  

6. **Commit your changes:** Once you've added your own author entry to the file, "commit changes":  
	* At the bottom of the page, in the text block where it says "Update authors.yml," enter a brief description of your proposed change. It should be something like: `Added author: Hannah Alpert-Abrams.`  
	* Click "commit."

7. *(Optional)*: If you want to upload an author image:  
	* Return to the home page of your fork of the Critical Archives project. 
	* Switch the `gh-pages` branch using the drop-down menu.
	* Open the `images` directory.
	* In the upper right corner, click `upload files.`
	* Drag and drop your image to upload the image.
	* Write a commit message: at the bottom, where it says "Add files via upload," write a brief message describing your change, i.e. "Uploading author photo for Hannah Alpert-Abrams."
	* Click `commit changes`.  

8. **Merge your changes:** To update the website, you'll need to merge your changes back into the original project by following these steps.  
	* Navigate to the repository home page and choose the `gh-pages` branch from the drop-down menu.
	* Click the `New pull request` button, which is right next to the `branch` dropdown menu. 
	* Make sure the base fork is `halperta/criticalarchives` and the branch is `gh-pages`. The head fork should be `yourusername/criticalarchives` and the branch should be `gh-pages`.
	* In the comment box, make sure the description matches what you're doing. It should say something like "Adding author id and photo for Hannah Alpert-Abrams."
	* Click `Create pull request`.

We'll check and approve your changes before the modification goes live.

## Step 4: Write your article
Instructions for writing an article in markdown [are found here.](http://www.halperta.com/criticalarchives/tutorial/writing-in-markdown/) Please note that you must include a YAML header, and use markdown for formatting.  

## Step 5: Upload your review 
Uploading your review is going to look a lot like editing your author id. The only difference is that you'll be having someone review your changes before you merge them with the website. You can also watch the [video tutorial](https://youtu.be/TRhuFvoOZXk). Note: turn on closed captions to view the text instructions].  

1. **Log in to GitHub** and navigate to your fork of the Critical Archives repository. Confirm that you're in your fork: it should be called "yourusername/criticalarchives" and it should be forked from "halperta/criticalarchives."
2. **Confirm location**: Switch to the `gh-pages` branch (upper left corner). Open the `_posts/blog` directory.
3. **Create file**: In the upper right corner, click on the button that reads `create new file`.
4. **Name your file** using the date you're planning to publish the review (your second due-date). The name should be `YYYY-MM-DD-short-title.md` . For example, this tutorial is named `2018-08-01-blog-instructions.md`
5. **Copy and paste** the text of your review into the text box. Use the `preview` tab (just to the right of the `edit new file` tab) to see what your post will look like. (*Note: If you feel comfortable on GitHub, you can write your review directly into this text editor.*)
6. **Save** the text of your review on GitHub by "committing a new file":
	1. At the bottom of the page, in the text block where it says "Create filename.md," enter a brief description of your proposed change. It should be something like: "Creating review of Article Title by Your Name." 
	2. Click "commit new file" to save your updates to your fork of the website. 
	3. You can continue editing this file. Just make sure you're always in your fork of the website (`yourusername/criticalwebsite`) and that you're always in the `gh-pages` branch.

## Step 6: Merge your changes
[[Watch the video tutorial.](https://youtu.be/54ORGhWaFKE) Note: turn on closed captions to view the text instructions.]
1. Navigate to your forked repository. You can do this by navigating to your profile, opening the `repositories` tab, and then selecting the `critical archives` repository. You can also follow the URL directly: it should be something like `https://github.com/username/criticalarchives`.
2. At the top of the page, you should see a highlighted alert showing your `recently pushed branches.` Click the green tab that says `Compare & Pull Request.`
3. **Open a pull request:** Make sure that the *base fork* is `halperta/criticalarchives`, the *base* is `gh-pages`, the *head fork* is `yourusername/criticalarchives`, and *compare* is `gh-pages`.
4. In the comment box, write: `submitting review for publication by Your Name`
5. Click `Create Pull Request`. Your changes will be reviewed before being published.



