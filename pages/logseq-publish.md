github:: https://github.com/pengx17/logseq-publish
author:: [[Peng Xiao]]
tags:: #[[Github/Pages]], #Github/Actions, #LogSeq

- Use in your GitHub Actions to publish your site
- Note: this has big down sides
	- it creates one large index.html that contains all your content
		- At one point this was a 50MB file for my site `index.html` - so every visitor to any link has to first download the entire amount
		- As of [[Aug 9th, 2023]], it’s just under 10MB
	- uses hash routing to get to various parts of the site, which means basically zero #SEO
	- it takes quite a long time to run the action and publish
- The pros
	- Works today with a one time setup
	- It will even include theme styling and export.css
	- You have a very “app” feeling LogSeq version of your notes online!
	- Cool node visualizer and graph explorer
	- Search!