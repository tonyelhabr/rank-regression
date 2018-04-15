
Introduction
============

See my blog posts [here](https://tonyelhabr.rbind.io/posts/ranks-spearman-rho-r/) and [here](https://tonyelhabr.rbind.io/posts/ranks-spearman-rho-r-2/) for the full write-ups, or, check out the `.html` files in the `output/` directory in this repo, which was used as the basis for the blog post. The `figs/` directory also contains some of the visualizations in the post.

The documents can be recreated with the following commands:

``` r
rmarkdown::render("R/rank-regression-1.Rmd", output_dir = "output")
rmarkdown::render("R/rank-regression-2.Rmd", output_dir = "output")
```

Highlights
==========

Here are a couple of the coolest visualization, in my opinion.

![](figs/viz_summ_mntc_mod_0.png)

![](figs/viz_est_vs_pv.png)