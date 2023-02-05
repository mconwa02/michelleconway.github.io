# My Github Pages website about me, 
## statistics, machine learning and data science

### Using mkdocs and pelican 

For Pelican, it uses the content and output folder
Generate your site using
`pelican content`

Your site has now been generated inside the output/ directory. 
(You may see a warning related to feeds, but that is normal when developing locally and can be ignored for now.)

Preview your site
`pelican --listen`

Use to view pelican version website that uses content folder

For mkdocs, it uses the docs folder and pushes to branch gh-deploy
`mkdocs build`

`mkdocs gh-deploy`

I currently have an issue with when I deploy, it loads the index.html to 
the below weblink and not markdown files in docs. Need to check the folders 

https://mconwa02.github.io/michelleconway.github.io/