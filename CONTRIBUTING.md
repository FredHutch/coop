# Guidelines for contributing to The Coop blog

We welcome submissions from any members of the [Coop Community](https://research.fhcrc.org/coop/en.html)!

## What kind of posts are appropriate for our blog?

Each post belongs to at least one of our three main categories:
 - *Community*: announcements and explanations about Coop events and programs
 - *Technical*: descriptions of tools and approaches used by our data-intensive research community and support staff
 - *Science*: reports on new and interesting research findings from our community using data and computational methods

Possible content includes:
- repost from your own blog
- description of a new data-oriented tool you're using
- report from a community group meeting
- announcements about events

## Required content

COOP-TEMPLATE-title.md

- title
- category (see above)
- tags
- main content, we recommend posts on the shorter side (no more than five paragraphs)

## Contribute via email

If you'd like to submit a blog post outside of GitHub, please email your [content](#required-content) to `coophelp` at `fredhutch.org`

## Contribute via GitHub

Include info to introduce GitHub

- fork the [repository](https://github.com/FredHutch/coop)
- in your fork, create a new branch with a name that reflects your blog post (e.g., `python-december`)
- copy template, renaming file with date and short title, add content
- submit PR to `gh-pages` branch in main repo

## Adding yourself as a contributor

More information coming soon!

## Errata

The information below is for maintainers of this blog (members of the team coop-blog-maintainers). This includes:
- [Reviewing and publishing blog posts](#reviewing-and-publishing)
- [Formatting and layout](#formatting-and-layout)

### Reviewing and publishing

### Formatting and layout

- This blog renders from the `gh-pages` branch.
- The template for the blog is [Minimal Mistakes Jekyll theme](https://github.com/mmistakes/minimal-mistakes). The following links and language were included in the original README and are copied here for convenience:
  - Please see [this page](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) for additional information on configuration.
  - If you have a question about using Jekyll, start a discussion on the [Jekyll Forum](https://talk.jekyllrb.com/) or [StackOverflow](https://stackoverflow.com/questions/tagged/jekyll).
  - [Ruby 101](https://jekyllrb.com/docs/ruby-101/)
  - [Setting up a Jekyll site with GitHub Pages](https://jekyllrb.com/docs/github-pages/)
  - [Configuring GitHub Metadata](https://github.com/jekyll/github-metadata/blob/master/docs/configuration.md#configuration) to work properly when developing locally and avoid `No GitHub API authentication could be found. Some fields may be missing or have incorrect data.` warnings.
- Additional modifications for the blog theme are from:
  - [Bioinformatics Interest Group (FHBig)](https://fredhutch.github.io/FHBig/)
  - [Fred Hutch Biomedical Data Science Wiki](https://sciwiki.fredhutch.org)
