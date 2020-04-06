---
title: "Report from the Python User Group: Python IDEs"
author: Justin Burge
categories:
  - Community
  - Technical
tags:
  - IDE
  - python
---

Since summer 2018, 245 Fred Hutch employees have taken _Introduction to Python_ through [Fredhutch.io](https://www.fredhutch.io). This introductory course introduces participants to [Jupyter Notebooks](https://jupyter.org/) as an integrated development environment, or IDE.

While Jupyter notebooks are a great tool, there are other options for interfaces to write and run Python code. In the [_Python User Group_](https://sciwiki.fredhutch.org/scicomputing/reference_training/#community-groups), we recently looked at three popular IDEs for Python. Frequent attendees of the group wrote up a few overviews highlighting the more popular Python IDEs nowadays which you can peruse below.

## Visual Studio Code (VS Code)

[VS Code](https://code.visualstudio.com) is a free IDE from Microsoft. The screenshot below previews the demo by Koshlan Mayer-Blackwell; you can read the entire content [here](https://github.com/kmayerb/visual_studio_code_demo/blob/master/README.md).

[![VSCode]({{ site.baseurl }}/assets/Python-IDEs/2020-03-20-15-31-55.png)](https://github.com/kmayerb/visual_studio_code_demo/blob/master/README.md)

## PyCharm

[PyCharm](https://www.jetbrains.com/pycharm/download) is free with an option to pay for an upgrade with more services. Zach Romer's demo is screenshot below; view the entire report [here](https://github.com/zyd14/pycharm_demo/blob/master/README.md).

[![PyCharm]({{ site.baseurl }}/assets/Python-IDEs/2020-03-20-15-39-46.png)](https://github.com/zyd14/pycharm_demo/blob/master/README.md)

## Jupyter Lab

[Jupyter Lab](https://jupyterlab.readthedocs.io/en/latest/getting_started/installation.html) is a free and open source project. A demo by me (Justin Burge) is screenshot below, though the complete report is available [here](https://github.com/Chilliwack/jupyter_demo/blob/master/README.md).

[![Jupyter]({{ site.baseurl }}/assets/Python-IDEs/2020-03-20-15-41-39.png)](https://github.com/Chilliwack/jupyter_demo/blob/master/README.md)

## Other options and choosing one to use

But these aren't the only options...

- [Atom](https://atom.io/) - **Free/Open Source**
- [Spyder](https://www.spyder-ide.org/) - **Free**

Therefore, with so many free options it really comes down to personal preference. There are some features that you should look for in your IDE of choice such as:

- **Linter** - [linting](https://en.wikipedia.org/wiki/Lint_%28software%29) highlights syntactical and stylistic problems in your Python code which helps to mitigate potential errors and improves your coding. [PEP-8 is the most common style guide](https://www.python.org/dev/peps/pep-0008/) for python.

- **Debugger** - a [debugger](https://en.wikipedia.org/wiki/Debugger) allows you to quickly resolve bugs, issues or errors in your code by allowing you to quickly setup breakpoints at a particular line and then step in, out, or thru the code while viewing not only code output and actions but also variable assignment.

- **Version Control Integration** - [version control](https://en.wikipedia.org/wiki/Version_control) facilitates collaboration as it assists in the management of changes to documents or code and constructs some rigor around a development process. A popular version control platform is GitHub but it isn't the only one. What _is_ important is that your IDE of choice integrates with the version control your team is using.

- **Shell Integration** - this isn't a deal breaker but it makes it nice and most IDEs have this where with a keystroke you can pull up a window that has a shell instance running allowing you to interact with your OS, or [ssh into remote computing]((https://sciwiki.fredhutch.org/scicomputing/access_methods/#ssh-clients-for-remote-computing-resources)) or cloud resources.

- **Text Editor Integration** - again not a deal breaker but most of them have a text editor. What is important is that it can render or preview [Markdown files](https://sciwiki.fredhutch.org/compdemos/vscode_markdown_howto/)

Word to the wise, most of these features just mentioned are usually not built into the IDE itself and are made available to the user as an extension that they have to install in the IDE. The major IDEs though are getting better at including these features/extensions as default or pre-installed for the user. If not you might have to search and install to add them to your IDE environment.

I hope these points have inspired you to try out a new IDE and or help to make you more productive. Thanks for supporting the bioinformatics and data science community!
