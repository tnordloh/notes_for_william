# today, we created a website, using github's 'pages' tool #

## initializing a repository ##

We initialized a repository; the first attempt failed to generate
useful content, so we deleted and recreated, making sure to 
create an initial 'README.md', which contains examples of how to 
make links, embed images, and so on.

## making a separately purchased domain link to it ##

we started using github's directions, but eventually gave up, and
switched to instructions specific to our domain host, 
[google domains](https://domains.google.com).

[here is a link, describing the process](http://www.curtismlarson.com/blog/2015/04/12/github-pages-google-domains/).


finally, here is a reference to the [markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet), to help format the site.


# TODO #
We need to figure out how to create multiple pages, with links
 between them.  We also need to be able to modify the template, 
because the default template format is pretty crappy.

## Making a new page to visit ##
This turned out to not be too bad.
First, in the repository base directory, make a new file.  I chose the name README2.md, which isn't a great name.  In real life, maybe
the page would be called 'services', and contain a list of the
services you offer, along with prices, such as "Clean up PC Case
wiring - $20.00/hour plus materials", 
then, to make a link, just have to create a 'relative' url reference.
Here's an example:

```
[link to README2.md](./README2.md)
```
Let me know if you need more instruction than this.


## suggested reading ##
[how to modify the template](https://help.github.com/articles/customizing-css-and-html-in-your-jekyll-theme/)

