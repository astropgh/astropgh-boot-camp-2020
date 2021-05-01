**2020**: [GitHub](https://github.com/astropgh/astropgh-boot-camp-2020) | [website](https://astropgh.github.io/astropgh-boot-camp-2020/)

**2021**: [GitHub](https://github.com/astropgh/python-boot-camp-2021) | [website](https://astropgh.github.io/python-boot-camp-2021/)

Welcome to the 2020 AstroPGH Research Boot Camp and Weekly Seminar Series for summer undergraduate students and early PhD students new to research.  This program is designed to help you learn the basics of research, including coding, statistics, writing, and presenting.

We will start with a 1+3 day Python coding boot camp to help get everyone off the ground with their research.

Then we will have a weekly seminar series to discuss more advanced topics, including communication skills (reading, plotting, storytelling, and writing) that become more important as the summer goes on. My hope is to create a sense of community in spite of the remote operations this year, so that you can help others, can seek help, and can interact with each other.

## Boot Camp
### Installation and Setup
#### Python
Please install Python 3 before the Boot Camp. I recommend using the [Anaconda](https://www.anaconda.com/products/individual) package manager **_for Python 3.7_** and then install the following packages in the terminal:
```bash
conda install numpy scipy astropy matplotlib jupyter ipython
conda install -c astropy astroquery
conda install -c conda-forge jupyterlab
```

- [Conda Users Guide](https://conda.io/docs/user-guide/index.html)
- [Astropy Install Instructions](http://docs.astropy.org/en/stable/install.html)

#### Test Your Installation

1. Open a new terminal.
2. Type `ipython` into the terminal to open an interactive python session (the prompt should say `In [1]:`).
3. Copy this code:
```python
import numpy
import scipy
import astropy
import matplotlib
import astroquery
```
4. Type into the iPython shell the word `paste`, and press enter.
5. If no errors are raised, you're ready for bootcamp. You may close the terminal window.

If you are having difficulties with installation, please do not hesitate to reach out to Brett Andrews on Slack or via email.

#### Git and GitHub
- [Set up Git](https://help.github.com/articles/set-up-git/)
- [Sign up for GitHub](https://help.github.com/en/github/getting-started-with-github/signing-up-for-github)

### Instructors
- [Brett Andrews](https://bretthandrews.github.io/): Python Basics, Data Structures, Functions and Modules, Astropy I/II, Pandas I/II/III, Git, and GitHub
- [Christine Mazzola](https://cnmazz.github.io/): Matplotlib I and Matplotlib II
- [Biprateep Dey](https://biprateep.github.io/): Numpy I and Numpy II
- [David Setton](https://davidjsetton.github.io/): Linear Regression and Resampling
- [Alan Pearl](https://alanpearl.github.io/): Debugging
- [Daniel Perrefort](https://djperrefort.github.io/): Altair

### Schedule

| Time | Monday (5/18) | Tuesday (5/19) | Wednesday (5/20) | Thursday (5/21) |
|:-----:|:-----:|:-----:|:-----:|:-----:|
| 9:00-10:15 | Python Basics | Numpy I | Astropy I | Pandas I |
| 10:45-12:00 | Data Structures | Numpy II | Astropy II | Pandas II |
| 1:00-2:15 | Functions and Modules | Linear Regression | Matplotlib II | Pandas III, Git, and GitHub |
| 2:45-4:00 | Matplotlib I | Resampling | Debugging | Altair |


## Seminar Series

Wednesdays from 2-3 pm EDT

| Date | Title | Speaker |
|:-----:|:-----:|:-----:|
| 5/27 | [Effective Plotting](http://htmlpreview.github.io/?https://github.com/astropgh/astropgh-boot-camp-2020/blob/master/seminars/2020-05-27-plotting/plotting.html#/) | [Brett Andrews](https://bretthandrews.github.io) |
| 6/3  | [Coding Best Practices](seminars/coding_best_practices_2020-06-03.pdf) | [Daniel Perrefort](https://djperrefort.github.io/) |
| 6/10 | #strikeforblacklives |  |
| 6/17 | [MCMC](https://docs.google.com/presentation/d/1mVGKmY52kZpGOlFE78-F5ZXD1ciMeQKnq6srPQqFzqw/edit?usp=sharing) ([notebook](seminars/2020-06-17-mcmc/mcmc_notebook.ipynb), [emline.txt](seminars/2020-06-17-mcmc/emline.txt), [sndata.txt](seminars/2020-06-17-mcmc/sndata.txt)) | [Alan Pearl](https://alanpearl.github.io/) & [David Setton](https://davidjsetton.github.io/) |
| 6/24 | [From Passion to Action: Levers and Tools for Making Inclusive and Equitable](https://info.aps.org/delta-phy-webinar) | APS |
| 7/1  | [LaTeX and Overleaf](seminars/latex_2020-07-01.pdf) | [Cat Fielder](https://cfielder.github.io/) |
| 7/8  | [How to Give Effective Talks](seminars/effective_talks_2020-07-08.pdf) | Nathan Herring |
| 7/15 | [Strategies for Reading Papers](https://arxiv.org/abs/2006.12566) | [Rachel Bezanson](https://rachelbezanson.github.io/) |
| 7/22 | Nathan Herring Thesis Defense |  |
| 7/29 | [Overcoming Fear of Public Speaking](seminars/public_speaking_2020-07-29.pdf) | [Kuan Wang](https://kuanwang-astro.github.io/) |
| 8/5 | Elevator Pitches | [Brett Andrews](https://bretthandrews.github.io/) |
