Website Building with Jekyll
===

Presented by [Neal Grantham](http://nsgrantham.github.io) on February 6, 2015.

## What is [Markdown](http://daringfireball.net/projects/markdown/basics)?

> Markdown is a text-to-HTML conversion tool for web writers. Markdown allows you to write using an easy-to-read, easy-to-write plain text format, then convert it to structurally valid XHTML (or HTML). (John Gruber, inventor of Markdown)

- Hyptertext Markup Language (HTML) vs. Markdown
- Flavors of Markdown
	- GitHub
	- R

## What is [Jekyll](http://jekyllrb.com)?

> Jekyll is a simple, blog-aware, static site generator. It takes a template directory containing raw text files in various formats, runs it through Markdown (or Textile) and Liquid converters, and spits out a complete, ready-to-publish static website suitable for serving with your favorite web server. Jekyll also happens to be the engine behind GitHub Pages, which means you can use Jekyll to host your project's page, blog, or website from GitHub’s servers for free. (as described at [http://jekyllrb.com/docs/home/](http://jekyllrb.com/docs/home/))

- Why use Jekyll?
	- Clean, organized website generator
	- Very intuitive blogging platform 
	- Integration with Markdown
	- Free hosting on GitHub Pages  
- How does it work?
	- Markdown + Liquid + HTML/CSS
	- Configuration file: `_config.yml`  
	- Important directories:
		- `_layouts`
		- `_includes`
		- `_posts`
	- The generated site: `_site`    
- Things to do...
	- Add a research page
	- Create a new blog post
	- If we have time:
		- Extend to allow RMarkdown (Rmd) integration
		- Add MathJax (Javascript for typesetting LaTeX in your browser)
		


## Things to do before Friday

### Install Ruby and Jekyll
	
There are numerous guides online about how to do this. Here are several operating system specific guides to install Ruby and Jekyll:

- [Ubuntu 14.04](http://sharadchhetri.com/2014/06/30/install-jekyll-on-ubuntu-14-04-lts/)
- [Mac OS X](http://davidensinger.com/2013/03/installing-jekyll/)
- [Windows](http://jekyll-windows.juthilo.com)

Now do the following:

1. Download [Barry Clark's "Jekyll Now" repository](https://github.com/barryclark/jekyll-now) by choosing "Download ZIP" (right-hand side). Make sure to save it in a good place. I prefer `~/Documents`. Unzip it if necessary.
2. Open your terminal and navigate to this directory (e.g. `cd ~/Documents/jekyll-now-master`)
3. Before building the site, we must install a ruby gem (essentially like a package in `R`) called `jekyll-sitemap`. To do so, enter `gem install jekyll-sitemap` into your terminal.
4. Now we can build the website! Enter `jekyll serve`.  Hopefully you get some output that ends with "Server running ... press ctrl+c to stop"
5. Now open your browser of choice and head to the url     `http://localhost:4000`
6. If all goes well you will be staring at your website (nobody else can visit it online though, your machine is just hosting it locally).

If you get this far, you're in perfect shape for Friday! Please email me if you run into problems: `ngranth@ncsu.edu`.

### Download a Markdown Editor

There are many options, so go ahead and Google around. Personally I prefer [Mou](http://25.io/mou/) (Mac OS X) or [UberWriter](http://uberwriter.wolfvollprecht.de) (Ubuntu). I have heard good things about [MarkdownPad](http://markdownpad.com) (Windows).

You can also use [RStudio](http://www.rstudio.com) as a Markdown editor.


