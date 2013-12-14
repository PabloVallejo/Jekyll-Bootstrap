Jekyll Bootstrap
===========

Jekyll Bootstrap is a starting point to develop a Jekyll site which comes with [Bootstrap 3](http://getbootstrap.com) and [jQuery](http://jquery.com). it was created as help material for my blog post on [Hosting Jekyll sites on GitHub](http://pablovallejo.me/hosting-your-site-in-github-using-jekyll/).


![Alt text](/images/jekyll-bootstrap.png)


## Quick start

Download, or clone the repository and run it in you local machine.

```bash
# clone the repository
$ git clone https://github.com/PabloVallejo/Jekyll-Bootstrap.git

# run jekyll
$ cd Jekill-Bootstrap
$ jekyll serve

```

Jekyll Bootstrap will be available at `http://localhost:4000`.

## Uploading the site to GitHub
Decide whether you want to create a Project Page or a User/organization page.

#### Project page

Within your project's repository, create a branch called: `gh-pages` and place the content
of the base site there, after that, upload that branch to GitHub.


```bash
# create the gh-pages branch
$ git checkout -b gh-pages

# paste the base site files, commit and push
$ git add .
$ git commit -m "Add Jekyll Bootstrap files."
$ git push origin gh-pages
```
After this, you should be able to access the page at `http://your-username.github.io/your-project-name`. It may take up to 10 minutes to be available.

#### User/Organization page

Create a new repository called: `your-username.github.io`, place the content of the base site
in it and push it to GitHub.

```bash
# within the clone of your repository
$ git add .
$ git commit -m "Add Jekyll Bootstrap files."
$ git push origin master
```
Contrary to Project Pages, User/Organization pages are available at `http://your-username.github.io`


## Contributing

Everyone is welcome to contribute. Fell free to report a bug, request a feature or send a pull
request.
