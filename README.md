# Getting Started with Git, GitHub, and GitHub Pages
This is a short guide for beginners on how to set up a basic coding workflow: an editor, a GitHub account, a live webpage, and a way to work with others. You will do each of these once, but you will repeat some of them often, so it helps to understand what they do.

## 1. Install an Editor
Install VSCode, a free code/text editor that's become a standard tool for writing and editing code and Markdown. Then add two extensions from the Extensions panel: Markdown All in One (for live preview and formatting shortcuts) and Peacock (lets you color-code different project windows, handy once you're working in multiple repos). Be careful when searching because there are similarly named extensions, so double check you're installing the actual one before clicking install.

## 2. Create a GitHub Account and Install GitHub Desktop
Sign up for a GitHub account. Then install GitHub Desktop, a separate app for your computer. GitHub.com is where your repositories live online; GitHub Desktop is what lets you sync changes on your computer with that online repo.

## 3. Create a Repository
Create a new public repository on GitHub, and inside it, add a file named exactly index.html. This specific name matters, since GitHub Pages looks for index.html as the homepage. Add a link back to your repo using an actual HTML link tag, not just plain text (it's an easy mistake to write the words without wrapping them in a link): <a href="https://github.com/SorourAskarzadeh/solo-doc">Link to repository</a>Link to repository</a>

## 4. Stage, Commit, and Push
In GitHub Desktop, changed files show up under the "Changes" tab. This is staging, choosing what to include in your next save. Write a short message describing the change, click Commit to main, then click Push origin to upload it to GitHub. Doing it in these separate steps, instead of one big save, means your project keeps a clear list of small changes over time, each with its own label. This is easier to read than one messy pile of edits.

## 5. Deploy with GitHub Pages
In your repo's Settings, under Pages, set the source to your main branch. GitHub will automatically build a live website from your `index.html` file.

## 6. Add a Collaborator and Review a Pull Request
Invite a collaborator through your repo's Settings, then Collaborators, on GitHub.com. This setting isn't available in GitHub Desktop, so make sure you're on the website. Once they accept, have them edit a file and open a pull request instead of committing directly to main. Review their changes under the Files changed tab, then approve and merge. Having someone else look at a change before it's merged catches mistakes the original author might miss. In my case, my collaborator caught a typo.

## 7. Write This README
Finally, create a `README.md` file at the top level of your repo. You're reading it now. A README is usually the first thing someone sees when they visit a repository, so it's where you explain what the project is and how to use or reproduce it. Save, commit, and push it like any other change.