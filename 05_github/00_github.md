# GitHub and Authorea

At the moment, you have one-click synchronisation between Authorea and GitHub.
Which means you don’t really have to fiddle around with SSH keys and whatnot, and get straight down to authoring your text.
What you’re going to do now is head over to Authorea and create a new document.
Make sure that you’ve selected the `Markdown` option.
Once your document is created with placeholder files and directories, click on the `…` button on the top-right-hand corner, click on the “Settings” cogwheel, and click on “Setup GitHub integration” button.
When you head over to your GitHub repos, you should find a newly prepared repo with all the files in it.
Clone the repo to your desktop.

The first thing you want to do is to create a `README` file with relevant information about your project and how people can contribute to it.
The second thing you want to do is establish a licence you intend to use for the document (CC BY-SA 4.0 would be my recommendation), and create a `LICENSE` file as well.
And we’re off!
Add the files, commit them, and push your changes to GitHub.
Authorea won’t show them but GitHub will prominently display your `README` on the landing page of your repo.

Now, to add content to your piece, just create `.md` files (in appropriate directories) and add them to `layout.md`.

In this example, I’m going to make some typos so that when I submit a pull request, one of you kind folk will leave a line comment reminding me to fix it.
Once the PR is merged, Authorea should magically build us our updates file.
