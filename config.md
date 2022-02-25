<!--
Add here global page variables to use throughout your website.
-->
+++
author = "Kazi Abu Rousan"
mintoclevel = 2

# Add here files or directories that should be ignored by Franklin, otherwise
# these files might be copied and, if markdown, processed by Franklin which
# you might not want. Indicate directories by ending the name with a `/`.
# Base files such as LICENSE.md and README.md are ignored by default.
ignore = ["node_modules/"]

# RSS (the website_{title, descr, url} must be defined to get RSS)
generate_rss = true
website_title = "Phyvis -- Understand physics and visualize"
website_descr = "Learning different physical ideas and try to visualize them"
website_url   = "https://aburousan.github.io/physvis/"
+++

<!--
Add here global latex commands to use throughout your pages.
-->
\newcommand{\R}{\mathbb R}
\newcommand{\scal}[1]{\langle #1 \rangle}
\newcommand{\bolditalic}[1]{_**!#1**_}
\newcommand{\prettyshow}[1]{@@code-output \show{#1} @@}

<!-- name of repository -->
@def prepath = "physvis"
