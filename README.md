# About this repo

Here are the Figma design files from my [Personal Website](https://github.com/erikucenik/PersonalWebsite).

I've never been too keen on designing anything, but I wanted some consistency on a project like this. I think a chaotic visual language makes for a chaotic experience.

# History

I started out by improvising some clean home page design in Photoshop (`Home.psd`). After getting a hint of what I wanted to do, I transferred the concept to Figma (`Home.fig`).

For the articles, I improvised the general aesthetics in `Article.fig` and then implemented how special embeddings would fit in (`ArticleDownload.fig`, `ArticleCode.fig`). Note that I didn't make any design files for things like markup (bold, italics...) nor images. Rather I preferred to improvise those directly on CSS. I don't think you need a Figma file to find out that you want a border radius of 6px or whatever. Those details are already implemented [here](https://github.com/erikucenik/PersonalWebsite).

I also designed a favicon. It's just the profile picture I use pretty much everywhere (`media/profile_pic.png`) drawn schematically on Illustrator (`favicon.ai`). I played around with different colors and sizes for the background circle (`favicon_variations/`). Black looked really good but it was hard to distinguish when scaled to 32x32 pixels, so I ended up taking a shade of gray.

I didn't want to design how math rendering would look, as I understand that adapting to the aesthetics of pre-existing technologies like [MathJax](https://www.mathjax.org/) is simply more efficient. Never forget Pareto's Principle.

Update: the SQL database design can be found at [My DrawSQL account](https://drawsql.app/teams/uceniklabs/diagrams/personalwebsite).
