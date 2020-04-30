---
title: "Best practices for asking for coding help"
author: Lauren Wolfe
categories:
  - Community
tags: # add 1-4 lowercase tags that are relevant to your post, ex: r, python, genomics, workflows
  - help
  - coding
  - communication
---

As some of us find ourselves with extra time on our hands in the COVID-19 era, many at Fred Hutch are looking to sharpen their programming skills. Luckily, we have some amazing opportunities and resources to learn digitally through groups like the Coop/fredhutch.io and TDS-IRC. A natural consequence of more people learning to code is an increase in messages to Slack channels, community groups, and personal messages asking for assistance with coding and software. At first glance, many of these messages seem straightforward: `Hi, I can't install tidyverse. Can you please help?`. This is a reasonable and polite request, but is actually difficult for us to answer. It will take a few back and forth messages, possibly running some code again, to diagnose the issue. How can you make this process run more smoothly? In this post we will go over some norms and best-practices for asking for coding help through slack, email, or online forum.

First, I want to note that a fear of asking for help can be compounded by very real oppressive structures and lived experience. Women, gender-diverse folks, and people of color experience vitriol online at higher rates. Further, these groups often encounter increased scrutiny at work that can make regularly asking for help more intimidating and possibly detrimental to career progress. It's important to cultivate a work environment that actively addresses power structures to create a space that encourages open, vulnerable communication and where asking for help feels comfortable to all. Here at the Coop we are committed to ensuring that everyone feels welcome and encouraged to ask for assistance. If you have any comments, suggestions, or concerns please reach out to either Kate Hertwick or Lauren Wolfe via email, Slack, or Teams.

**Do some research before posting/asking**

- The first step to encountering a problem is trying to solve it or at least understand it as much as you can on your own. Toss your error code on google, peruse help forums, try a few solutions. Get good search results by quoting the generic portions of your error string (ex: _ImportError: No module named ben_ becomes _"ImportError: No module named" ben_).

- *Best case scenario:* Someone has already asked your exact question and the solution provided works for you! It's good practice to double-check that your question has not already been answered on an Internet forum like [StackOverflow](https://stackoverflow.com/) or the [GATK Community Forum](https://gatk.broadinstitute.org/hc/en-us/community/topics) before posting..

- *Worst case scenario:* No working results turn up. While this can be a frustrating process it will help you further diagnose your problem (if only by determining what doesn't work) and enable you to describe the situation more clearly. 

**Clearly state your problem**

- The quality of the answers you receive is directly related to the quality of the question posed. A good question is concise and systematically addresses the problem. Make sure that before posting any code that you properly introduce and give context to the question you are asking. Enough detail should be provided that someone could answer you without requesting more information. 
- For example, if you're having trouble with software installation, it's incredibly helpful to include both the exact error message or behavior you're receiving, as well as the operating system of your computer. Extra points for versions (language/library/software) and network details if applicable (wifi/VPN).

**Make sure your problem is reproducible**

- If you are asking for help with a coding problem, it is best practice to provide a minimal reproducible example of the code that you need help with. An ideal example uses the minimal amount of code required to reproduce the problem and includes all the parts necessary to reproduce the problem including inputs and desired output. The test code should reliably reproduce the problem you're trying to solve. 

- Do not use images of code. Copy and paste text and then format it as code. It helps with readability and makes it easier to run your test code. In most markdown (inc. github and Slack), a backtick encloses monospace code, and triple backticks enclose blocks of code.

- Make sure that the code you show doesn't contain any sensitive information like personal information, passcodes, hostnames, etc.

**Ask your question**

- We welcome questions at every level. You may feel a question is too basic or simple to ask, but you are not the only person with that question. A searchable answer will help other users.

- After doing a basic search for your answer, please _ask your question_. You will not be chastised for not finding the answer on your own. This isn't the Internet - no one will send a [Let Me Google That For You](https://lmgtfy.com/?q=importerror).

**Be nice!**

- Generally, the people you're going to for help on online forums are unpaid and volunteering their time and expertise. Kindness and understanding go a long way.

- At Fred Hutch we have quite a few folks for whom assisting with software or coding questions is a part of their job. Please be aware that these people and teams are strapped for time right now and could possibly be handling many different requests for help.

- Try and remember there are real humans behind the screen and brush off folks who may be less than welcoming.

**Archive your discussion so it can be useful to others**

- No one else should have to suffer through pages of purple links to find the answer they're looking for. It's always good practice to share back what you've learned.
  - [File an issue](https://github.com/FredHutch/wiki/issues) for the content to be added to the Biomedical Data Science Wiki
  - Write up what you've learned and create your own blog post here or on a personal blog!

- If you have requested help through a forum and a response solved your problem make sure you go back and mark the correct answer to let folks know what worked. It can even be helpful to note what answers did not work for you and why.
  - This idea applies when asking for help through the Coop Slack channels. It's always encouraged to report back with what worked and what did not. Replying to/starting a thread on the original post is the best way.

## More resources
While this post generally focuses on getting help through online forums many of these tips apply when asking for help in person as well. For more in-depth information on effectively asking for coding help check out these two articles:

- [How do I ask a good question - StackOverflow](https://stackoverflow.com/help/how-to-ask)
- [Ten Simple Rules for Getting Help from Online Scientific Communities](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1002202#s9)

Fred Hutch offers in-person help in a number of ways, most of which are still offered, albeit in virtual form. Office Hours are held by a number of groups:

- Scientific Computing offers _live_ virtual help (text chat/audio/video) Wednesdays from 10am to noon through [Slack](https://fhbig.slack.com/archives/CD3HGJHJT) and [Teams](https://teams.microsoft.com/l/channel/19%3a0d3ec66c4dd1488a87467fa6a8e8b72d%40thread.skype/Office%2520Hours?groupId=1b968d63-dc19-460f-9e6d-cdbd539d1bc6&tenantId=0054a3ea-b394-418b-ad1a-174138231fd6). All topics are welcome including: accounts/permissions, storage/data management, Linux, bash, scripting, cluster use and parallelism, and basic software/language help primarily in R and Python.
