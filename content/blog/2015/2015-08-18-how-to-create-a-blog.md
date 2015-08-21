title=How To Create a Blog Using GitHub Pages and JBake
date=2015-08-23
type=post
tags=blog,jbake,github,git,pages,how to
status=published
~~~~~~

Recently I was looking into creating a blog in order to write down some thoughts. In looking for simple ways to create one, but being a bit more technical than the average user, I started by discarding [Blogger](https://www.blogger.com), [Wordpress](https://wordpress.com/), [Medium](https://medium.com/) and the like. I wanted to keep my content under my control (let's pretend for a second that GitHub is under my control) and still have a  workflow that allows me to write, save and publish with simplicity and flexibility. 

As a software engineer, a very simple solution that I found is by using Git, which I already use on a daily basis for development work. 

So without further ado let's get started with the details of what we need to get writing and publishing.

#### GitHub Pages setup ####
The first step is creating a regular [GitHub](https://github.com/) account. There is nothing fancy here and I will not go into any details on how to do this, although it should be pretty straightforward.

Once you have your repository created you should install [Git](https://git-scm.com/) locally in your machine. 

After you have Git locally set up you can clone the repository by copying the clone URL of your repository GitHub page and using it on your terminal.

`$ git clone https://github.com/jdmartinho/jdmartinho.github.io.git`

For user repositories GitHub Pages requires that you put your site in the `master` branch. For project repositories you should use the `gh-pages` branch.

 

