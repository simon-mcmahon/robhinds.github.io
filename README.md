# My personal CV website.

This repository is a heavily modified fork of the open source github pages CV template provided by Rob Hinds. I have customized the CSS, names and contents of various sections, Linkedin integration, modified the header menu so it is responsive on mobile devices and added a pdf download functionality for people to retrieve my resume.

You can checkout the page generated for this repo here: http://simon-mcmahon.github.io


## Making your own CV

To make your own GitHub hosted CV:

1. Fork this repo into your github account 
2. Click the "Settings" button in your new forked repository (in the menu on the right), and change the repository's name to {{yourusername}}.github.io, replacing yourusername with your GitHub user name.
3. Update /_config.yml with the details of your CV - the comments will explain what is required
4. Visit http://{{yourusername}}.github.io to check it out
5. Share your new CV/Profile with the world!

If you want to test it locally, install Ruby & Jekyll, clone the repository locally and run "jekyll serve" from the repo root directoy.

If you want to host the page on your own web hosting, you will need to run it locally and jekyll will build the site files to the /_site directory which you can then push to your hosting provider - See https://jekyllrb.com/ for details.

## TO DO:
- Embed a picture to add some life to the resume.
