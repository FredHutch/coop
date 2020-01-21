# Guidelines for contributing to The Coop blog

We welcome submissions from any members of the [Coop Community](https://research.fhcrc.org/coop/en.html)!

The content below includes:
- [What kind of posts are appropriate for our blog?](#what-kind-of-posts-are-appropriate-for-our-blog)
- [Required content for a blog post](#required-content-for-a-blog-post)
- [Contribute via email](#contribute-via-email)
- [Contribute via GitHub](#contribute-via-github)
- [Adding yourself as a contributor](#adding-yourself-as-a-contributor)
- [Errata](#errata) (for the Coop blog maintainers: reviewing posts, publishing, and changing site layout)

## What kind of posts are appropriate for our blog?

Each post published here belongs to at least one of our three main categories:
 - *Community*: announcements and explanations about Coop events and programs
 - *Technical*: descriptions of tools and approaches used by our data-intensive research community and support staff
 - *Science*: reports on new and interesting research findings from our community using data and computational methods

Possible content includes:
- repost content from your own blog
- description of a new data-oriented tool you're using
- report from a community group meeting
- announcements about events
- anything else you think would be of interest to the broader community!

For some ideas, check out our [GitHub issues for potential blog topics](https://github.com/fredhutch/coop/issues?q=is%3Aissue+is%3Aopen+label%3Apost). Also feel free to [file an issue](https://github.com/FredHutch/coop/issues/new?assignees=&labels=post&template=blog-post-idea.md&title=) if there is a topic you'd like to see blogged about and discussed! Additionally, if you [come across a bug please report it here](https://github.com/FredHutch/coop/issues/new?assignees=&labels=&template=bug-report.md&title=) and if there is a [feature or enhancement you would like to suggest for the site please make that here](https://github.com/FredHutch/coop/issues/new?assignees=&labels=infrastructure&template=feature-or-enhancement-request.md&title=).

## Required content for a blog post

- **title:** A short, catchy description to entice readers
- **author:** Your name, which should match your [contributor file](#adding-yourself-as-a-contributor). If you do not have a contributor file, please feel free to contact one of our team members to assist you.
- **categories:** Community, Technical, or Science, as described [above](#what-kind-of-posts-are-appropriate-for-our-blog)
- **tags:** Suggested keywords that can help readers find information from among our blog posts. Please suggest a few tags following [our guidelines](#tags).
- **content:** This is the body of the blog post! We recommend relatively short posts (no more than five paragraphs), equivalent to a three minute read. Pictures and links to other sites are also great!

## Contribute via email

If you'd like to submit a blog post and don't want to deal with technical details, please email your [content](#required-content-for-a-blog-post) to `coophelp` at `fredhutch.org`.

## Contribute via GitHub

This blog is published through [GitHub](https://github.com), and we are happy to accept submissions via pull requests. If you are new to GitHub or haven't worked collaboratively, please feel free to email `coophelp` at `fredhutch.org` to meet with one of the Coop blog maintainers to walk you through the process.

- Fork the [repository](https://github.com/FredHutch/coop)
- In your fork, create a new branch with a name that reflects your blog post (e.g., `python-december`)
- Copy the [markdown blog post template](/drafts/TEMPLATE-post-title.md) to a new file named to reflect your post (e.g., `python-december.md`)
- Modify the header and body of the template to reflect [required content](#required-content-for-a-blog-post), save to the [drafts folder](https://github.com/FredHutch/coop/tree/gh-pages/_drafts), and commit to your branch
- Submit a PR to the `gh-pages` branch in [this repository](https://github.com/FredHutch/coop)

The Coop blog maintainers will review your content and ask for clarification if needed. When everyone is satisfied, we'll accept the pull request and arrange for the post to be published.

## Adding yourself as a contributor

We list all contributors on our [Contributors](https://fredhutch.github.io/coop/contributors/) page. This page is rendered from files in the [gh-pages/contributors/](https://github.com/FredHutch/coop/tree/gh-pages/_contributors) folder. You should create one of your own by using one of our current authors as a template, changing the following fields:
- title
- position
- affiliation
- links (GitHub, Twitter, personal website, lab website, etc)

If you would prefer to not be listed on our contributors page, you should encase your name in quotation marks in the `author` field of your post.

## Errata

The information below is for maintainers of this blog (members of the team coop-blog-maintainers). This includes:
- [Reviewing and publishing blog posts](#reviewing-and-publishing)
- [Tags](#tags)
- [Formatting and style](#formatting-and-style)
- [Rendering and layout](#rendering-and-layout)

### Reviewing and publishing

Submitted posts are reviewed, edited, and published by the Coop blog maintainer team.

For team members:

- If a submission is received via email, create a new branch and add the post to the drafts folder, then proceed as described below for pull requests.
- Pull requests (PRs) are accepted from contributors forking the repository and adding a new file to the [drafts folder](/drafts/).
- Review the pull request to ensure all [required content](#required-content-for-a-blog-post) is present, and also edit for grammar, spelling, and formatting.
- Accept/merge the PR when the content meets requirements, ensuring the file is located in the [drafts folder](/drafts/).
- Change the filename to include the required [`YEAR-MONTH-DAY-title.md` format](https://mmistakes.github.io/minimal-mistakes/docs/posts/) and ensure the [front matter](https://jekyllrb.com/docs/front-matter/) is accurately formatted. Extra notes on front matter:
  - `categories` should be one or more of `Science`, `Technical`, `Community` (note capitalization)
  - `tags` should be lowercase
  - `last_modified_at` is only required to override the date in the filename
- If the author is a first-time contributor, you may need to create a [contributor file](#adding-yourself-as-a-contributor) for them.
- If necessary, build the site locally to [render posts in the drafts folder](https://jekyllrb.com/docs/posts/#drafts) prior to publishing.
- Publish the post by moving it to the [posts folder](/posts/), and notify the submitter when it is available.
- Delete the branch for the PR (if necessary).

### Tags

Tags should appear in lowercase, and may represent a variety of different characteristics:
- coding language (e.g., r, python)
- a community group or slack channel (e.g., data viz, shiny)
- your lab, research group, or division at Fred Hutch
- general topics (e.g., workflows, automation, reproducibility)

Tags are added to your post by adding the following structure to your post's markup:
```
tags: # here we have added tags to R and python to the blog post
   - r
   - python
 ```

### Formatting and style

- For subheadings, use second-level markdown formatting (```##```) and [sentence case](https://apastyle.apa.org/style-grammar-guidelines/capitalization/sentence-case).
- Please do not include entire email addresses in a post. If you would like to include contact information for a Fred Hutch email, please put the username in backticks like this:

```
`username`
```

### Rendering and layout

- The template for the blog is [Minimal Mistakes Jekyll theme](https://github.com/mmistakes/minimal-mistakes). Additional modifications for the blog theme are from:
  - [Bioinformatics Interest Group (FHBig)](https://fredhutch.github.io/FHBig/)
  - [Fred Hutch Biomedical Data Science Wiki](https://sciwiki.fredhutch.org)
- General information on Minimal Mistakes rendering was included in the template's README and are copied here for convenience:
  - Please see [this page](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) for additional information on configuration.
  - If you have a question about using Jekyll, start a discussion on the [Jekyll Forum](https://talk.jekyllrb.com/) or [StackOverflow](https://stackoverflow.com/questions/tagged/jekyll).
  - [Ruby 101](https://jekyllrb.com/docs/ruby-101/)
  - [Setting up a Jekyll site with GitHub Pages](https://jekyllrb.com/docs/github-pages/)
  - [Configuring GitHub Metadata](https://github.com/jekyll/github-metadata/blob/master/docs/configuration.md#configuration) to work properly when developing locally and avoid `No GitHub API authentication could be found. Some fields may be missing or have incorrect data.` warnings.
- This blog renders from the `gh-pages` branch.

#### Building the site locally

You may want to build a copy of this wiki locally (on your own computer) to make sure that it looks the way you want before pushing your changes.

1. Clone the repo locally
1. Install Ruby (version 1.9.2 or later).
**Note**: most modern Mac computers already have Ruby installed. If you still need Ruby,
it can be found [here](https://www.ruby-lang.org/en/downloads/).
1. On Mac, install xcode commandline tools `xcode-select --install`

1. You may need to install `bundler`. Type
   `which bundler` to see if it is already
   installed. If nothing is returned, then
   install `bundler` with `gem install bundler`.
   If that fails, try `sudo gem install bundler`.
   
1. You may need to install gems used by the site.
   Type `gem install -g Gemfile` to install all of the gems the site uses.

1. To build and view the site locally, from the cloned repo directory run
   `bundle install` then run `bundle exec jekyll serve`. Once the
   site is built you can view it at
   [http://localhost:4000](http://localhost:4000).

#### Checking for broken links

To check for broken links, run `rake test` on your clone of the repository. This will exit with an error if there are any broken links, and list the broken links and the files they are found in.

If you are inside the Fred Hutch network, you can type `rake testlocal` and that will include internal URLs in the check.
