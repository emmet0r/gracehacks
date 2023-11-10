What better way to learn than with a functional sample project?

### Visiting the project on the web

Since this project is a website, I've specifically configured the repository so that whenever there is a push to it, it is made visible on the web. (This is the magic of GitHub Pages ✨)

You can see the live version of the project at [http://emmet0r.github.io/gracehacks/docs](https://emmet0r.github.io/gracehacks/docs/). Note that any changes in your fork won't show up there, though, until the maintainer of the project (Emily) merges them in.

### Fork the project on GitHub

- Log in to GitHub.
- Visit the project you want to fork, in this case:
  [https://github.com/emmet0r/gracehacks](https://github.com/emmet0r/gracehacks)
- Click the _Fork_ button in the top-right of the screen
- Wait for the animation to conclude...
- Notice that your browser is now visiting a copy of the project in your personal space, rather than the original one owned by Emily. You should also see a _forked-from..._ remark in the top-left of the screen.

### Clone the project to your computer

- On the right side of the screen, look for the clone URL. Copy it to the clipboard.
- Open a terminal and navigate to where you'd like to store a local working copy of the repository.
- Type `git clone` followed by the pasted URL. Hit enter.
- `cd` into the directory that you just created.

### Verify that the project is setup correctly

- Open your local copy of _index.html_ in VS Code, or your favorite editor. You should see some HTML code.
- Open your local copy of _index.html_ in your favorite web browser. It should render as a basic HTML page with some text and an image.
- Make a minor test change in _index.html_, save, and reload in the browser. Make sure what you see in the browser reflects that change.
- Undo that change with your editor, save, and then reload in the browser. Make sure that what you see in the browser reflects undoing the test change.

### Find a task to work on

- ***In pairs**, find a bug on the project's issue tracker that you would like to work on.
- Claim that bug! Leave a comment on the issue that says you're working on it. Whoever leaves the comment should tag their partner with their _\@‌githubhandle_.
- Before you proceed, refresh the page and make sure no one else claimed the bug first, while you were reading and deciding...

### Resolve the task

- How you do this depends on the issue you've chosen. You should only have to modify one file per issue. If you're working in _index.html_, your changes will be isolated to one part of the file.
- If you run into a problem you don't know how to solve, try looking for help online or asking a neighbor.
- Make sure to reopen your local copy of index.html and check that your solution works.

### Commit and push

- Once you've finished making changes, you can use the following command to get a list of files you changed: `git status`
- You can commit your changes by typing `git add` followed by the files you've changed, for instance: `git add index.html`
- Once you've added the changes, you can _commit_ them with a message specifying what you changes (in present tense): `git commit -m "Explanation of my changes"`
- Now publish those changes to your remote repository on GitHub by typing `git push`
- You will probably be prompted for your username and password.
- You can now visit GitHub and make sure that your personal fork contains these changes.

### Create a pull request

Visit your personal fork and click the _Pull Requests_ button on the right. This will offer you the chance to make a new pull request by clicking on _New Pull Request_. Explain what you did and make sure to include a comment stating which issues it addresses, so that it automatically closes the issue. You can see [here](https://help.github.com/articles/closing-issues-using-keywords/ "‌") for details on how to do this.

Now, get feedback from the project maintainer and await your pull request getting merged.

### Once merged, visit your changes on the web

When your changes are merged into the main project repo, the group website will update. Note that it can take a couple of minutes for the changes to be reflected live after they've been merged. Sometimes your changes will not show because of caching; to get around this, add `/?` to the end of the URL.
