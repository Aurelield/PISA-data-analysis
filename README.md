


<img src="https://s1.qwant.com/thumbr/0x380/b/d/9fda7c3e2d33a8cf9a1c426f9fb39a5ddcc1db1c4c0b1eaee0bcb8c6dc7d78/EDUCATION-text.jpg?u=https%3A%2F%2Figowithigho.com%2Fwp-content%2Fuploads%2F2021%2F03%2FEDUCATION-text.jpg&q=0&b=1&p=0&a=0" width="1280" height="650">

# PISA-data-analysis: impact of PISA rates on economic aspects

<!-- Add buttons here -->

<!-- Describe your project in brief -->

The aim of this project is to observe and analyse the impacts of PISA rates given specific economic data(employement rate,income inequality). The analysis is based on data extracted from the The Organisation for Economic Co-operation and Development website (OECD).
5 csv files have been used in this analysis: 3 PISA datasets, 2 economic datasets.



<!-- The project title should be self explanotory and try not to make it a mouthful. (Although exceptions exist- **awesome-readme-writing-guide-for-open-source-projects** - would have been a cool name)

Add a cover/banner image for your README. **Why?** Because it easily **grabs people's attention** and it **looks cool**(*duh!obviously!*).

The best dimensions for the banner is **1280x650px**. You could also use this for social preview of your repo.

I personally use [**Canva**](https://www.canva.com/) for creating the banner images. All the basic stuff is **free**(*you won't need the pro version in most cases*).

There are endless badges that you could use in your projects. And they do depend on the project. Some of the ones that I commonly use in every projects are given below. 

I use [**Shields IO**](https://shields.io/) for making badges. It is a simple and easy to use tool that you can use for almost all your badge cravings. -->

<!-- Some badges that you could use -->

<!-- ![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/navendu-pottekkat/awesome-readme?include_prereleases)
: This badge shows the version of the current release.

![GitHub last commit](https://img.shields.io/github/last-commit/navendu-pottekkat/awesome-readme)
: I think it is self-explanatory. This gives people an idea about how the project is being maintained.

![GitHub issues](https://img.shields.io/github/issues-raw/navendu-pottekkat/awesome-readme)
: This is a dynamic badge from [**Shields IO**](https://shields.io/) that tracks issues in your project and gets updated automatically. It gives the user an idea about the issues and they can just click the badge to view the issues.

![GitHub pull requests](https://img.shields.io/github/issues-pr/navendu-pottekkat/awesome-readme)
: This is also a dynamic badge that tracks pull requests. This notifies the maintainers of the project when a new pull request comes.

![GitHub All Releases](https://img.shields.io/github/downloads/navendu-pottekkat/awesome-readme/total): If you are not like me and your project gets a lot of downloads(*I envy you*) then you should have a badge that shows the number of downloads! This lets others know how **Awesome** your project is and is worth contributing to.

![GitHub](https://img.shields.io/github/license/navendu-pottekkat/awesome-readme)
: This shows what kind of open-source license your project uses. This is good idea as it lets people know how they can use your project for themselves.

![Tweet](https://img.shields.io/twitter/url?style=flat-square&logo=twitter&url=https%3A%2F%2Fnavendu.me%2Fnsfw-filter%2Findex.html): This is not essential but it is a cool way to let others know about your project! Clicking this button automatically opens twitter and writes a tweet about your project and link to it. All the user has to do is to click tweet. Isn't that neat? -->
# Limits and issues

Some limits and issues have to be mentioned.

- Missing values 
- Joining the 5 csv files all together
- Selecting right values 
- Coordinate year economic datasets + year PISA datasets 
- Understanding  the different indexes and measures


# Demo-Preview

<!-- Add a demo for your project -->


<!-- After you have written about your project, it is a good idea to have a demo/preview(**video/gif/screenshots** are good options) of your project so that people can know what to expect in your project. You could also add the demo in the previous section with the product description.

Here is a random GIF as a placeholder.

![Random GIF](https://media.giphy.com/media/ZVik7pBtu9dNS/giphy.gif) -->

<img width="388" alt="PISAscience_time" src="https://user-images.githubusercontent.com/82478538/158059636-253537c3-f01d-4deb-aa33-fa9646cd6f33.png"> <img width="387" alt="l2S0foHClGkE5jTiEUZQ9mYYPZHvAvrYSOPapQBSoi-AF0M5C6TmRDQrbQ-0xbpcQfWblvdnxJ4DY_New0OsVeoB8dXlenuFSc3amwhlId15ewe-S0G18qSeI2UWbAiZTM6ZsUwLgq2x" src="https://user-images.githubusercontent.com/82478538/158059759-686facba-dba2-4722-87de-7487eef0aa54.png">

# Tools

- Python Langage 
- Tableau(Public)

# Table of contents

<!-- After you have introduced your project, it is a good idea to add a **Table of contents** or **TOC** as **cool** people say it. This would make it easier for people to navigate through your README and find exactly what they are looking for.

Here is a sample TOC(*wow! such cool!*) that is actually the TOC for this README. -->

- [Project Title](#project-title)
- [Limits and issues](#limits-and-issues)
- [Demo-Preview](#demo-preview)
- [Tools](#tools)
- [Table of contents](#table-of-contents)
- [Installation](#installation)
- [Usage](#usage)
    - [Going Further](#going-further)
- [License](#license)
- [Trello dashboard](#trello-dashboard)

# Installation
[(Back to top)](#table-of-contents)

Here are the command lines of the production environment.

```sh
import pandas as pd
from pandas_profiling import ProfileReport
import seaborn as sns
import pandas_profiling as pp
import matplotlib.pyplot as plt
```

<!-- *You might have noticed the **Back to top** button(if not, please notice, it's right there!). This is a good idea because it makes your README **easy to navigate.*** 

The first one should be how to install(how to generally use your project or set-up for editing in their machine).

This should give the users a concrete idea with instructions on how they can use your project repo with all the steps.

Following this steps, **they should be able to run this in their device.**

A method I use is after completing the README, I go through the instructions from scratch and check if it is working. -->

<!-- Here is a sample instruction:

To use this project, first clone the repo on your device using the command below:

```git init```

```git clone https://github.com/navendu-pottekkat/nsfw-filter.git``` -->

# Usage
[(Back to top)](#table-of-contents)

The present analysis can lead to social and economic aspects given the PISA rates.
The aim of the analysis would be to concretely act on economic inequalities between men and women throughout the world.
Highlighting inequalities can aware people of the women condition in the world of work. 

<!-- This is optional and it is used to give the user info on how to use the project after installation. This could be added in the Installation section also. -->



# Going further
[(Back to top)](#table-of-contents)

Three questions have been raised during the data analysis:

- Analysis with other economic variables (GDP): use of linear regressions
- Datasets from AFD (Agence Fran??aise de d??veloppement)
- Analysis with 2022 PISA assessments and datasets about COVID-19

<!-- Your project is gaining traction and it is being used by thousands of people(***with this README there will be even more***). Now it would be a good time to look for people or organisations to sponsor your project. This could be because you are not generating any revenue from your project and you require money for keeping the project alive.

You could add how people can sponsor your project in this section. Add your patreon or GitHub sponsor link here for easy access.

A good idea is to also display the sponsors with their organisation logos or badges to show them your love!(*Someday I will get a sponsor and I can show my love*) -->


# Citation
[(Back to top)](#table-of-contents)

All of cv files come from the website of the OECD.

- OECD (2022), Reading performance (PISA) (indicator). doi: 10.1787/79913c69-en (Accessed on 20 March 2022)
- OECD (2022), Income inequality (indicator). doi: 10.1787/459aa7f1-en (Accessed on 20 March 2022)
- OECD (2022), Employment rate (indicator). doi: 10.1787/1de68a9b-en (Accessed on 20 March 2022)

<!-- Adding the license to README is a good practice so that people can easily refer to it.

Make sure you have added a LICENSE file in your project folder. **Shortcut:** Click add new file in your root of your repo in GitHub > Set file name to LICENSE > GitHub shows LICENSE templates > Choose the one that best suits your project!

I personally add the name of the license and provide a link to it like below. -->

[GNU General Public License version 3](https://opensource.org/licenses/GPL-3.0)

# Trello dashboard
[(Back to top)](#table-of-contents)

<!-- Let's also add a footer because I love footers and also you **can** use this to convey important info.

Let's make it an image because by now you have realised that multimedia in images == cool(*please notice the subtle programming joke). -->

https://trello.com/invite/b/md0QGa8M/868a3d5826626f443765e1df511644f5/pisa-data-analysis

<!-- Add the footer here -->

<!-- ![Footer](https://github.com/navendu-pottekkat/awesome-readme/blob/master/fooooooter.png) -->
