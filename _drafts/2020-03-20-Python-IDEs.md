---
title: "Python User Group's: Python IDEs"
author: The Coop Team 
categories:
  - Community
  - Technical
tags:
  - IDE
  - python
---

From 2016 to now [Fredhutch.IO](https://www.fredhutch.io/resources/) has taught roughly 342 Fred Hutch employees in the _Introduction to R_ course and since the middle of 2018, 245 in the _Introduction to Python_. In those introductory courses we use integrated development environments or IDEs like Rstudio and [Jupyter Notebook](https://jupyter.org/) respectively to teach the material and run the code yet, they are not the only ones.

Even though [Rstudio](https://rstudio.com/) is widely used by many R users the same cannot be said for Python. If you are just starting out with Python or want to explore other options now might be a good time.

In the [_Python User Group_](https://sciwiki.fredhutch.org/scicomputing/reference_training/#community-groups), we recently looked at three popular IDEs for python. Frequent attendees of the group wrote-up a couple of overviews highlighting the more popular Python IDEs nowadays which you can peruse below.

- [VSCode](https://github.com/kmayerb/visual_studio_code_demo/blob/master/README.md) - **Free**

[![VSCode]({{ site.baseurl }}/assets/Python-IDEs/2020-03-20-15-31-55.png)](https://github.com/kmayerb/visual_studio_code_demo/blob/master/README.md)

- [PyCharm](https://github.com/zyd14/pycharm_demo/blob/master/README.md) - **Free/Paid**

[![PyCharm]({{ site.baseurl }}/assets/Python-IDEs/2020-03-20-15-39-46.png)](https://github.com/zyd14/pycharm_demo/blob/master/README.md)

- [Jupyter Lab](https://github.com/Chilliwack/jupyter_demo/blob/master/README.md) - **Free/Open Source**

[![Jupyter]({{ site.baseurl }}/assets/Python-IDEs/2020-03-20-15-41-39.png)](https://github.com/Chilliwack/jupyter_demo/blob/master/README.md)

But these aren't the only ones..

- [Atom](https://atom.io/) - **Free/Open Source**
- [Spyder](https://www.spyder-ide.org/) - **Free**

Therefore, with so many free options it really comes down to personal preference. There are though some features that you should look for in your IDE of choice such as:

- **PEP-8 Linter** - [linting](https://en.wikipedia.org/wiki/Lint_%28software%29) highlights syntactical and stylistic problems in your Python code which helps to mitigate potential errors and improves your coding. [PEP-8 is the most common style guide](https://www.python.org/dev/peps/pep-0008/) for python.

- **Debugger** - a [debugger](https://en.wikipedia.org/wiki/Debugger) allows you to quickly resolve bugs, issues or errors in your code by allowing you to quickly setup breakpoints at a particular line and then step in, out, or thru the code while viewing not only code output and actions but also variable assignment.

- **Version Control Integration** - [version control](https://en.wikipedia.org/wiki/Version_control) facilitates collaboration as it assists in the management of changes to documents or code and constructs some rigor around a development process. A popular version control platform is GitHub but it isn't the only one. What _is_ important is that your IDE of choice integrates with the version control your team is using.

- **Shell Integration** - this isn't a deal breaker but it makes it nice and most IDEs have this where with a keystroke you can pull up a window that has a shell instance running allowing you to interact with your OS, or [ssh into remote computing]((https://sciwiki.fredhutch.org/scicomputing/access_methods/#ssh-clients-for-remote-computing-resources)) or cloud resources.

- **Text Editor Integration** - again not a deal breaker but most of them have a text editor. What is important is that it can render or preview [Markdown files](https://sciwiki.fredhutch.org/compdemos/vscode_markdown_howto/)

Word to the wise, most of these features just mentioned are usually not built into the IDE itself and are made available to the user as an extension that they have to install in the IDE. The major IDEs though are getting better at including these features/extensions as default or pre-installed for the user. If not you might have to search and install to add them to your IDE environment.

I hope these points have inspired you to try out a new IDE and or help to make you more productive. Thanks for supporting the bioinformatics and data science community!
