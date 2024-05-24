# 2024-ohbm-poster

Specific instructions: 
1. Install `posterdown`: `install.packages("posterdown")`
2. Generate generic template:  `rmarkdown::draft(file = "mydraft.Rmd", template = "posterdown_html", package = "posterdown", create_dir=FALSE)`
3. Add `knit: pagedown::chrome_print` to yml code chunk. 
4. Make edits to .Rmd, and render: `pagedown::chrome_print("poster_draft.Rmd")`
5. Most aesthetic/minor tweaks will be made using a CSS chunk, by looking at the template.html to see what the CSS already looks like, and making a change to overwrite it, example in poster_draft.Rmd.
   
References: 
https://www.shilaan.com/post/academic-conference-posters-using-posterdown/ 
https://github.com/brentthorne/posterdown/wiki/posterdown_html
https://loreabad6.github.io/posts/2023-04-26-betterposter-at-egu-2023/

Methods figure made with Canva. 

Other figures made by John Kruper in Altair. 