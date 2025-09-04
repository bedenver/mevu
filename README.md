# Mevu Website README

Hello! This guide is here to help you make updates to the Mevu website. We'll keep things simple and straightforward.

## How This Website Works

This website is built using a tool called **Jekyll**. Think of Jekyll as a program that takes your text and turns it into a webpage. All the website files are stored on a platform called **GitHub**.

When you make a change to the website, a service called **GitHub Actions** automatically takes your changes and "deploys" them, which means it makes them live on the internet for everyone to see.

## Finding Your Way Around the Files

You only need to worry about a few files and one folder to update the website's content. Here's a simple map:

* **Markdown Files (`.md`)**: The main pages of the website are `.md` files located in the main (root) folder. You can edit files like `index.md` (the homepage), `ongoing-research.md`, and `questions.md` to update the content on those pages.
* **`/assets/img`**: If you need to add new images, you can upload them to this folder.

All the pages you will be editing are written in [**Markdown**](https://www.markdownguide.org/cheat-sheet/), which is a simple way to format text. We've included a link to a handy guide for Markdown below.

## How to Update the Website (Step-by-Step)

You can make all your changes directly in your web browser using the GitHub website. Here’s how:

### 1. Editing a File

* Navigate to the file you want to edit (for example, `ongoing-research.md`).
* Click on the file to open it.
* In the top-right corner of the file view, you'll see a pencil icon. Click it to start editing.

### 2. Saving Your Changes (Making a "Commit")

Once you're happy with your changes, scroll to the bottom of the page. You'll see a section called "Commit changes".

* A **commit** is like saving a version of your work. It's a snapshot of your changes.
* In the first box, type a short, clear message that describes the change you made (e.g., "Updated the ongoing research page").
* Make sure the option "Create a **new branch** for this commit and start a pull request" is selected. This is the safest way to make changes.
* Click the green "Propose changes" button.

### 3. Creating a "Pull Request" (PR)

After you propose your changes, you'll be taken to a new page to create a "Pull Request".

* A **Pull Request** (or PR) is a way of telling the main project that you have some changes you'd like to add. It's a way for your changes to be reviewed before they go live.
* The title and description will be filled in for you, but you can add more details if you want.
* Click the green "Create pull request" button to finish.

#### (Optional) How to Ask for a Review

If you'd like someone to check your work before it goes live, you can ask for a review. This can be done either when you create the pull request or after it's been created.

On the pull request page, look for the **"Reviewers"** section in the right-hand sidebar. Click the gear icon and select the person you want to review your changes. They will get a notification to look over your work.

### 4. (Optional) Adding More Changes to the Same PR

If you need to edit more files as part of the same update, you can!

* Go back to the main file view of the repository.
* You'll see a yellow box at the top of the page with the name of the branch you just created. Click on the branch name.
* Now, you can navigate to other files and edit them just like you did in step 1.
* When you save (commit) these new changes, make sure you are saving them to your new branch (the one you are already working in).

### 5. Merging Your Pull Request to Go Live

Once you're ready (and your pull request has been reviewed and approved, if you requested a review), it's time to "merge" it.

* **Merging** is the process of taking the changes from your branch and adding them to the main version of the website.
* Go to the "Pull Requests" tab of the repository and click on your pull request.
* You'll see a green button that says "Merge pull request". Click it.
* Click "Confirm merge".

And that's it! Once you merge your pull request, the GitHub Actions will automatically start the **deployment** process.

* A **deployment** is the final step where your changes are published to the live website. It usually takes a minute or two.

## Markdown Cheatsheet

Markdown is a simple way to format your text. Here is a link to a great cheatsheet that shows you how to do things like create headings, make text bold, add links, and more:

[**Markdown Guide's Cheatsheet**](https://www.markdownguide.org/cheat-sheet/)

## How to Undo Changes (Reverting a Pull Request)

Don’t worry if you make a mistake — it’s easy to undo changes!

If a pull request (PR) has already been merged and you want to undo it:

1. Go to the **Pull Requests** tab on GitHub and click on the PR you want to undo.
2. Scroll down to the bottom of the page. If the PR has been merged, you’ll see a button that says **“Revert”**.
3. Click **Revert**. This will create a *new* pull request that automatically contains the opposite of the original changes.
4. Just like before, click **“Create pull request”**, then merge it.

Once you merge the revert PR, GitHub will undo the original changes and the website will go back to how it was before.
