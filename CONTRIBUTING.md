# Guidelines for contributing to The Coop blog

We welcome submissions from any members of the [Coop Community](https://research.fhcrc.org/coop/en.html)!

The content below includes:
- [What kind of posts are appropriate for our blog?](#what-kind-of-posts-are-appropriate-for-our-blog)
- [Required content for a blog post](#required-content-for-a-blog-post)
- [Contribute via email](#contribute-via-email)
- [Contribute via GitHub](#contribute-via-github)
- [Adding yourself as a contributor](#adding-yourself-as-a-contributor)
- [Walkthrough for contributing via Github GUI](#walkthrough-for-contributing-via-github-gui)
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

This blog is published through [GitHub Pages](https://pages.github.com/), and we are happy to accept submissions via pull requests.

>See [this Github Guide](https://guides.github.com/activities/hello-world/) for more information on contributing using the GUI and an overview of branching, committing, and creating pull requests with helpful gifs. If you are new to GitHub or haven't worked collaboratively, please feel free to email `coophelp` at `fredhutch.org` to meet with one of the Coop blog maintainers to walk you through the process.

1. Fork the blog repository @ [https://github.com/FredHutch/coop](https://github.com/FredHutch/coop) by clicking `Fork` in the top right corner.
2. In your forked repo click the `Branch` button in the top left corner.
    - A menu will down, showing a text box and listing all branches.
3. Make sure you are on the `gh-pages` branch.
5. In the text box that says `Find or create branch` type in your new branch name and hit `Enter`.
    - Branch names should be concise and descriptive of the work you will be doing on that branch.
        - ex: `typo-fixes`, `2019-rstudio-conf`
    - This will take you to your new branch. The new branch name is listed on the branch button. You can toggle between branches using this button.
>**NOTE: From this point on your are working in the new branch**
6. If you haven't done so already - create a contributor file.
    - _If you would prefer to not be listed on our contributors page, you should encase your name in quotation marks in the `author` field of your post._
    - Navigate into the `_contributors` directory.
    - Click `Create new file` in the top right corner.
    - Name your file `<hutchid>.md`
        - Ex: `lwolfe.md`
    - Copy and paste the template below into your file.
    - Replace each comment with your personal information. Title, position, and affiliation are required but links are optional.
       ```
        ---
        title: #Replace this comment with your name
        position: #Replace this comment with your job title
        affiliation: #Replace this comment with your affiliation
        ---
        ## Title
        {{ page.position }}
        
        ## Affiliation
        
        {{ page.affiliation }}
        
        ### Links
        <!-- Add your links below -->
        - [Github](https://github.com/<your_github_handle>)
        - [Twitter](https://twitter.com/<your_twitter_handle>)
        - [<descriptive text>](<url>) #follow this format to create links
        ```
    - See an example filled out template [here](https://raw.githubusercontent.com/FredHutch/coop/gh-pages/_contributors/lwolfe.md).
    - Add a descriptive commit message like `created contributor file for lwolfe` and commit your changes.

5. Create your post!
    - Go back to the main directory and navigate to the `_drafts` folder.
    - There is a file called `TEMPLATE-post-title.md`. You can use this file as a template or copy and paste the template below into a new file.
    ```
        ---
        title: "Title goes here" # replace with the title of your post, a short catchy description to entice readers
        author: AUTHOR_NAME # the author value should match the 'title' value of your contributor file located here /gh-pages/_contributors. If you do not have a contributor file, please feel free to make one or contact one of our team members to assist you.
        categories: # delete the categories that do not apply and keep at least one
          - Community
          - Technical
          - Science
        tags: # add 1-4 lowercase tags that are relevant to your post, ex: r, python, genomics, workflows
          - r
          - python
        ---
        ##Replace this with the content for your blog post 
    ```
    - Add a descriptive commit message and commit your changes.

6. If you need to you can go back to your post at any time and edit by clicking the button with a pencil icon on it in the upper right corner of your document. Remember to add a descriptive commit message to log what changes you made!

7. Once your post is finalized you can create a pull request to alert the blog moderators that your post is ready!
    - Navigate to the main page of your repo (`<your-github-username/coop>`).
    - Click the Pull Request tab at the top of your repo page.
    - **Base Repository** should be set to `FredHutch/coop`
    - **Base** should be set to `gh-pages`
    - **Head Repository** should be set to `<your-gh-handle>/coop`
    - **Compare** should be set to `<your-working-branch>`
    - Click `Create Pull Request` to request a review of your material!
----
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
