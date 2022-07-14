# Paul Anzel's Portfolio

## Introduction

Hello there, my name is Paul Anzel! I'm a Data Engineer currently employed with [Codecov](https://about.codecov.io/), managing our data infrastructure. Prior to that I worked at [H-E-B](https://www.heb.com/) (data workflow productionalization and data quality management), at [Metromile](https://www.metromile.com/) (managing our ETL system and using telematics data to detect vehicle crashes and evaluate potential insurance fraud), and at [Wiser](https://www.wiser.com/) (price-demand estimation).

I did doctoral research (left ABD) in Applied Physics at Caltech with [Chiara Daraio](http://daraio.caltech.edu/) where I worked on developing a new type of acoustic imaging system for non-destructive evaluation. During my graduate research I received a NASA Space Technology Research Fellowship and a M.S. in Applied Physics. I have a B.S. and B.A. in Chemical Physics and Mathematics (respectively) from Rice University.

Outside of work, I've been involved in different political efforts. I was a volunteer with [Tech for Campaigns](https://www.techforcampaigns.org/) where I was recognized as a "Super Volunteer" for improving our processes and documentation around email fundraising. Before that, I worked with [East Bay For Everyone](https://eastbayforeveryone.org/) to advocate for building more housing in the SF Bay Area. I am an instructor with [Software Carpentry](https://software-carpentry.org/), have helped organize the mentorship program for the [SciPy conference](https://www.scipy2021.scipy.org/organizers), and am on the [NumFocus Affiliate Project Selection Committee](https://numfocus.org/sponsored-projects/affiliated-projects). I managed Caltech's [bicycle repair cooperative](https://caltechbikelab.blogspot.com/) for three years, play accordion and piano, and have started getting into ham radio.

I live with my lovely wife Rose, young son Isaac, and fussy cats Coltrane and Simone.

## Public talks

### [How do you test data workflows? (SciPy 2022)](https://docs.google.com/presentation/d/1FHBYw8IreSA1DsMxS6opVR-9qP0x6vC6ejCxyR4-xYU/edit?usp=sharing)

I've long wondered how I could go about testing data code - but how do you even unit-test a SQL query? After some time and effort trying to figure this problem out, I think I have an approach I'm happy with. Most advice I see focuses on the standard Python testing tooling, but I see a three-pronged approach--testing, static analysis, and data quality management--as the solution to this problem.

### [Introdution to Bayesian A/B testing (local DS Meetup, 2022)](https://docs.google.com/presentation/d/1MDE4loVaA9lAm-umZbP-mxPyOzuk49uXrCZJllx28yE/edit?usp=sharing)

With my involvement in Tech for Campaigns, I was always stymied that the email lists I worked with never had enough of a population for good statistical power for A/B testing. I wondered if Bayesian methods could play more of a role, and after looking into them I'm never going back to Frequentist statistics. I cover a lot of the approach outlined by the [VWO paper](https://cdn2.hubspot.net/hubfs/310840/VWO_SmartStats_technical_whitepaper.pdf) and go a bit into picking sample sizes for A/B tests based on a multi-armed-bandit approach.

### [PandasUDFs - One Weird Trick to Scaled Ensembles (Data + AI Summit 2021)](https://github.com/anzelpwj/dais_conference_2021_presentation/blob/main/DAIS_PandasUDFs.pdf)

Presentation on the use of Spark PandasUDFs to speed up workflows where you might use regular Python UDFs or are building ensembles of models. They really were my One Weird Trick for productionalization at H-E-B.

### [Git-ting along with others (PyDataLA 2019)](https://www.youtube.com/watch?v=7mm9p1UBHlw)

Tutorial on using Git for collaboration. Topics included creating issues, branching, and doing code review. I'm very proud of the pun. Slides can be found [here](https://docs.google.com/presentation/d/1njdRK0la0cCh3AiPoYeOiqgw36jRGnt70Gz80emG9Sc/edit?usp=sharing).

### [Hi, I'm Your Technical Interviewer: Advice for Breaking Into Industry (Scipy 2019)](https://github.com/anzelpwj/advice_for_getting_into_industry/blob/master/advice_getting_into_industry.pdf)

Quick talk for folks looking at making the transition from academia to industry of some of the advice I wish I had had.

### [The Science(?) of Documentation (WriteTheDocs 2017)](https://github.com/anzelpwj/writethedocs2017)

Inspired by [Greg Wilson's commentary](http://third-bit.com/talks/greatest-hits/#/) that the state of software-development research is thin and poorly distributed on the ground, I did some investigation on my own looking into what research there is regarding software documentation. Long-story-short, there's precious little. I attended the WTD conference to see if I could find any more, and ended up giving a lightning talk about how little we know and how to assess relevant scientific evidence.

## Some projects

### [Statistics Study Group Notes](https://github.com/anzelpwj/Stats-week)

During my time at Wiser, I started a journal club to go over some techniques I wanted to learn more about, and to teach some of the other analysts some basic techniques (e.g. what a Fourier transform is). Upon moving to Metromile, I was pleased to see that they had an active study group there. Here is a collection of iPython notebooks where I go through implementing various algorithms myself and demonstrate their use.

Some ones I'm particularly proud of:

- [The Hilbert and Hilbert-Huang Transform](https://nbviewer.jupyter.org/github/anzelpwj/Stats-week/blob/master/Hilbert_Transform.ipynb)
- [HOT-SAX for discord discovery](https://nbviewer.jupyter.org/github/anzelpwj/Stats-week/blob/master/HOT_SAX.ipynb)
- [Robust outlier detection techniques](https://nbviewer.jupyter.org/github/anzelpwj/Stats-week/blob/master/Grubbs_and_Qtest.ipynb)

### [Beer analysis](https://nbviewer.jupyter.org/github/anzelpwj/Beer_server/blob/master/Beer_analysis_v2.ipynb)

I had some friends in grad school with whom I'd grab a Friday afternoon beer, and eventually I started rating the different beers we'd try. Many years and beers later, I've learned some interesting things about the beers I like.

### [A Moveable Feast Kinetic Sculpture](http://www.danielbusby.com/a-moveable-feast/)

An eight-person pedal-powered dining table. Project led by Daniel Busby, I provided many bicycle parts, ergonomic advice, and plenty of drilling and grinding.

### [PyBadge conference badge](https://github.com/anzelpwj/basic_pybadge_project)

Some code for an Adafruit PyBadge to work as a fun name badge for conferences. Has some blinkenlights for good measure.

### [Pantsuit Politics bingo card](https://mybinder.org/v2/gh/anzelpwj/pantsuit_politics_bingo/master?filepath=card_maker.ipynb)

Little bingo card generator based off of [this tweet](https://twitter.com/LouRovegno/status/1169967063559020544) for one of my favorite podcasts. Biggest challenge was finding a good way to get interactive widgets to work online. I initially tried to get this operational with Pyodide ([link](https://alpha.iodide.io/notebooks/3190/)) but came to the conclusion that Pyodide wasn't ready for me to use. Current version hosted in [Binder](https://mybinder.org/v2/gh/anzelpwj/pantsuit_politics_bingo/master?filepath=card_maker.ipynb).

### [Domestic Violence Program mapping](https://github.com/anzelpwj/DV_program_analysis)

Mapping and basic analysis of domestic violence programs in the Los Angeles area completed on request of a colleague.
