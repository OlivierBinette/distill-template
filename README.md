This blog is constructed using RStudio's [Distill for Rmarkdown](https://rstudio.github.io/distill/) framework.

## How to create a blog post

In order to contribute a post to this blog, you will need R, RStudio, and an installation of the `distill` R package:
```r
install.packages("distill")
```

Then, follow the instructions below:

1. Fork this repository and open it as a project in RStudio.

2. Use the R command below to create a new blog post:
```r
distill::create_post("Post Title", author="Author")
```

3. Edit and knit the corresponding Rmd file created in the _posts folder. See [https://rstudio.github.io/distill/basics.html](https://rstudio.github.io/distill/basics.html) to learn more about editing Rmarkdown files in the Distill format.

4. Commit the Rmd and generated html files, push, and make a pull request to integrate the post to this blog.

