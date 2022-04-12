---
title: Call for Papers
nav: Call for Papers
topics: GitHub; Optional Software
---
We invite submissions to the First Workshop on Geospatial Knowledge Graphs (GeoKG2022) to be held in conjunction with the 
<a href="https://www.knowledgegraph.tech/">The Knowledge Graph Conference 2022 (KGC2022)</a> that will take place at Cornell Tech campus, New York, 
and globally online, from May 2 to 6, 2022. GeoKG2022 is a half-day workshop consisting of two parts: paper presentations, and an interactive breakout
discussion session.

The workshop aims to bring together disparate elements of the environmental and geospatial community and provide a setting to discourse about
large-scale knowledge graphs for geospatial and environmental data integration and intelligence, state-of-the-art, spatiotemporally-explicit machine
learning methods, tools, and their potential as well as limitations on addressing geospatial challenges. More specifically, the goal is to foster
discussion on frameworks for leveraging spatial and temporal knowledge as the nexus to integrate environmental data of various themes within geospatial
knowledge graphs.


## Topics:
We particularly welcome contributions on topics related to environmental data integration using knowledge graphs and geospatial 
intelligence services using innovative machine learning techniques. The main topics of interest are:


1) Geospatial Ontologies and Geospatial Knowledge Graph Construction
    - Spatiotemporal Scoping of GKGs
    - Ontologies to encode environmental observations and events in GeoKGs

2) Querying Geospatial Knowledge Graphs
    - GeoSPARQL and Spatial Query Evaluation
    - GeoKGs Visualizations

3) Machine Learning for Geospatial Knowledge Graphs
    - Geospatial Knowledge Graph Embeddings
    - Spatiotemporally-explicit Machine Learning Models for Environmental Tasks

4) Other GeoKG Topics and Applications
    - Real-world use cases of GeoKGs
    - Applications of Geospatial Knowledge Graphs (e.g. knowledge graphs in environmental data integration and AI systems)


## Submissions:
We invite the submission of original research results and industry-level applications related to the focus areas of the workshop, in one of two categories given below. All submissions are requested through EasyChair.

1) Short papers (maximum 5 pages LNCS style) presenting proposed research directions, novel ideas, use-case scenarios, established results or more general positions or discussions.

2) Vision papers (maximum 4 pages ) presenting important directions for future research on GeoKGs. Such papers should identify key problem areas for GeoKGs, and propose potential solutions or strategies that could be developed to address such problems. Ideally the papers should highlight open research questions for GeoKGs, and should stimulate future research.

Submissions should be sent to  geokg.kgc22@gmail.com

Important Dates
---

<ul>
  <li>Papers submissions: April 12, 2022</li>
  <li>Papers notifications: April 16, 2022</li>
  <li>Camera-ready version submissions: April 22, 2022</li>
  <li>Workshop will be held on May 3rd between 9 AM -12PM </li>
</ul>  
To create your own materials using `workshop-template-b`, please create a free [GitHub account](https://github.com/join) if you do not have one already.
Basic familiarity with the GitHub web interface will be helpful.

For a quick introduction check out GitHub's [Hello World guide](https://guides.github.com/activities/hello-world/), or the extensive [GitHub Learning Lab](https://lab.github.com/).

It is possible to create a website with this template using only GitHub's web interface--in fact, it works great!
However, for more advanced uses you will want Git, Ruby, and Jekyll installed on your computer to do local development.

{% capture text %}
1. Have a [GitHub](https://github.com) account.
2. Optional: have [Git](https://git-scm.com/), [Jekyll](https://jekyllrb.com/), and a nice [text editor](https://code.visualstudio.com/) installed.
{% endcapture %}
{% include card.html text=text header="Setup Overview" %}

-------------

## Local Jekyll Setup [very optional]

### Install Git

[Git](https://git-scm.com/) is a [free](https://www.gnu.org/philosophy/free-sw.en.html), [distributed](https://en.wikipedia.org/wiki/Distributed_version_control) version control system. [GitHub](https://github.com/) is a Git repository hosting service, a place to store and sync your work in the cloud--your Jekyll and GitHub Pages projects will be under Git version control, so you need the software on your machine. 

- Windows: install [Git for Windows](https://git-for-windows.github.io/) using the default options. This will give you Git, Git Bash, and Git GUI. Git Bash is a great terminal that lets you use UNIX style commands on Windows.
- Mac: check if Git is already installed by opening terminal and typing `git --version`. If you do not have it, download the official [Mac installer](https://git-scm.com/downloads).
- Linux: check if Git is already installed by opening terminal and typing `git --version`. If you do not have it, install from your distribution's software center or package manager (for Ubuntu `sudo apt install git`).

If you are interested in using a visual GUI application integrated with GitHub, Windows and Mac users should also install [GitHub Desktop](https://desktop.github.com/) using the default options.
You can install GitHub Desktop in addition to other versions of Git.

There are other [GUI apps available](https://git-scm.com/downloads/guis) for managing and visualizing Git repositories, including Linux options.

### Install Ruby

[Ruby](https://www.ruby-lang.org/en/){:target="_blank" rel="noopener"} is a open source programming language popular with web applications.
**_You do not need to know anything about Ruby_**, but you do need it to run Jekyll on your system!

Jekyll requires a Ruby version 2.4.0 or greater.
Below are quick start steps, but you may want to refer to Jekyll's official [installation guides](https://jekyllrb.com/docs/installation/) for tips.

- **Windows:** Use [RubyInstaller for Windows](https://rubyinstaller.org/){:target="_blank" rel="noopener"}.
    - First, [download](https://rubyinstaller.org/downloads/) the suggested stable version "WITH DEVKIT" (as of this writing, Ruby+Devkit 2.7.X (x64)) and double click to install. Use the install defaults, but make sure "Add Ruby executables to your PATH" is checked. On the final step, ensure the box to start the MSYS2 DevKit is checked.
    - Second, the installer will open a terminal window with options to install MSYS2 DevKit components. Choose option 3, "MSYS2 and MINGW development toolchain", or simply press ENTER to install all the necessary dependencies. The installer will proceed through a bunch of steps outputting a bunch of text in the terminal window. *Eventually*, this will conclude and you should see a message with the word `success` in it. If the window doesn't close, press `Enter` again or manually close it. (The installer can be restarted by typing `ridk install` into a command prompt).
- **Mac:** OS X has a version of Ruby installed by default. Check the version with `ruby -v`. If it is > 2.4.0 you can use the system Ruby. However, a newer version can be installed using [Homebrew](https://brew.sh/), `brew install ruby`, or a manager such as [rbenv](https://github.com/rbenv/rbenv) or [RVM](http://rvm.io/). Check the official Jekyll [Mac install docs](https://jekyllrb.com/docs/installation/#macOS) for tips.
- **Linux:** Even though the version will not be the most up-to-date, the simplest method is to use your distro's repositories. For example on Ubuntu, `sudo apt install ruby-full`. Make sure the repository version is > 2.4.0. You will also need the build tools Make and GCC, on Ubuntu get them with `sudo apt install build-essential`. For a more up-to-date version, use a manager such as  [rbenv](https://github.com/rbenv/rbenv) or [RVM](http://rvm.io/).

### Install Jekyll

Jekyll is a Gem, a software package installed via Ruby's management system called RubyGems (similar to Python's Pip). 
Open a terminal and type:
`gem install jekyll bundler`

This will take a minute as Gem installs all the dependencies and builds extensions. 

### Install Text Editor

When working with code you should have a good text editor.
Windows notepad does not handle UTF-8 encoding or UNIX line endings that are standard for cross platform applications. 
For basic editing, Windows [Notepad++](https://notepad-plus-plus.org/), Mac TextEdit, or Linux Gedit are sufficient.
However, a more complete code editor will be helpful for managing Jekyll projects.

Open-source cross platform suggestions:

- [Visual Studio Code](https://code.visualstudio.com/)
- [Atom](https://atom.io/)

Tip: you can click `.` on any GitHub repository to [open the web editor](https://docs.github.com/en/codespaces/the-githubdev-web-based-editor) (which is a light version of VS Code)!
