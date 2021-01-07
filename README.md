# multiword.github.io

This repository holds the source for the [Multiword Expressions Section](https://multiword.org/) of the [Special Interest Group on the Lexicon (SIGLEX)](https://siglex.org/).

## Making pull requests on github

You can propose improvements/corrections to the MWE Section's website via pull requests. A pull request is a modification sent to the website editors for review. Once a pull request is accepted, the modification is automatically applied to the website.

  1. When you want to contribute to a GitHub project, the first step is to fork the repository. Therefore, click on the _Fork_ button in the top-right corner. This creates a new copy of the `multiword.github.io` repository under your GitHub user account with a URL like: `https://github.com/<YourUserName>/multiword.github.io`.
  2. Next, clone the repository on your computer by opening the terminal and running the command: `git clone https://github.com/<YourUserName>/multiword.github.io` (or use the ssh URL if you prefer)
  3. You can either create a branch (e.g. `git branch issue12; git checkout issue12`) or work directly on the `master` branch. Probably creating a branch is a good idea to clearly indicate what issue you are addressing. Edit and/or create the markdown files locally using your favorite text editor, then commit and push the changes (`git commit -a; git push`) to the forked repository under your GitHub username. If you are not familiar with the Linux/Mac terminal, you can carry out these operations using GitHub's web interface.
  4. Once you push the changes to your repository, the _Compare & pull request_ button will appear in GitHub. Click it to create the pull request when you're ready.
  5. Add a description of your contribution, then open a pull request by clicking the _Create pull request_ button. This allows the website editors to review your contribution. From here, they can merge it if it is good, or they may ask you to make some changes.
  6. If this is a punctual contribution, you can remove the forked repository once your pull request has been merged into the website.

These instructions were adapted from [this tutorial](https://opensource.com/article/19/7/create-pull-request-github)

## Editing Markdown files with Jekyll

Markdown is a lightweight text markup language that supports titles, bold, itemized lists, etc. It uses some simple special symbols such as `*` and `_` inserted directly inserted in the text (as opposed to html tags), so the text remains readable even in raw format. In addition, if more complex formatting is needed, it is possible to insert raw html directly into markdown files. Markdown processors are usually integrated in websites such as github. For instance, this README is written in Markdown and converted to html by github's engine.

Our website uses [jekyll](https://jekyllrb.com/), a framework which allows converting a set of markdown files (with extension `.md`) into a website. If this is the first time you are editing Markdown files, a good place to start is this [website](https://www.markdownguide.org/). Markdown files in a jekyll web page usually start with a header which you should probably not modify (e.g. the absence of the `layout:` key prevents the page from displaying correctly)

If you want to modify the website's menu structure or design, you should edit the `_layouts/default.html` file directly. This layout is based on [Bootstrap](https://getbootstrap.com/) and an in-house CSS extension `_assets/css/mwe.css`. By playing with these files, most modifications should be possible without the need for complex CMS installation and training.
