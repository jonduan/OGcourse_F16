# MACS 40000: Economic Policy Analysis with Overlapping Generations Models

|  | [Dr. Richard Evans](https://sites.google.com/site/rickecon/) |
|--------------|--------------------------------------------------------------|
| Email | rwevans@uchicago.edu |
| Office | 250 Saieh Hall |
| Office Hours | W 2:30-4:30pm |
| GitHub | [rickecon](https://github.com/rickecon) |

* **Meeting day/time**: T,Th 10:30-11:50am, TBD
* Office hours also available by appointment

## Prerequisites

Advanced undergraduate or first-year graduate microeconomic theory, linear algebra, multivariable calculus, recommended coding experience.


## Texts

Evans, Richard W., _Overlapping Generations Models for Policy Analysis: Theory and Computation_, unpublished draft (2016).


## Course description

This course will study economic policy questions ideally addressed by the overlapping generations (OG) dynamic general equilibrium framework. OG models represent a rich class of macroeconomic general equilibrium model that is extremely useful for answering questions in which inequality, demographics, and individual heterogeneity are important. OG models are used extensively by the Joint Committee on Taxation, Congressional Budget Office, Department of the Treasury, and Federal Reserve System for policy analysis.

This course will train students how to set up and solve OG models. The standard nonlinear global solution method for these models--time path iteration--is a fixed point method that is similar to but significantly different from value function iteration and policy function iteration. This course will take students through progressively richer versions of the model, which will include endogenous labor supply, nontrivial demographics, bequests, stochastic income, multiple industries, non-balanced government budget constraint, and household tax structure.

We will be focusing on computational strategies, modularity of code, sensitivity and robustness to assumptions, and policy questions that can be answered with this framework. Students can use whatever programming language they want, but I highly recommend you use Python 3.x ([Anaconda distribution](https://www.continuum.io/downloads)). I will be most helpful with code debugging and suggestions in Python. We will also study results and uses from recent papers listed in the "References" section below. The dates on which we will be covering those references are listed in the "Daily Course Outline" section below.


## Course Objectives and Learning Outcomes

* You will know how to augment the standard overlapping generations model framework to answer policy questions.
* You will know the computational methods to solve for the steady-state and transition path equilibria of the model.
* You will learn computational tools such as:
	* Constrained minimization
	* Multi-equation root finder with occasionally binding constraints
	* Interpolation
	* Curve fitting
	* Parametric and nonparametric estimation
* You will learn coding and collaboration techniques such as:
	* Best practices for Python coding ([PEP 8](https://www.python.org/dev/peps/pep-0008/))
	* Writing modular code with functions and objects
	* Creating clear docstrings for functions
	* Collaboration tools for writing code using [Git](https://git-scm.com/) and [GitHub.com](https://github.com/).


## Grades

Grades will be based on the four categories listed below with the corresponding weights.

Assignment   | Points | Percent |
-------------|--------|------|
Homework     |   100  |  50% |
Midterm      |    50  |  25% |
Final Exam   |    50  |  25% |
-------------|--------|------|
Total points |   200  | 100% |

\begin{itemize}
* **Homework:** I will assign 8 problem sets throughout the term, and I will drop your one lowest problem set score.
	* You must write and submit your own computer code, although I encourage you to collaborate with your fellow students. I \textbf{DO NOT} want to see a bunch of copies of identical code. I **DO** want to see each of you learning how to code these problems so that you could do it on your own.
	* Problem set solutions, both written and code portions, will be turned in via a pull request from your private [GitHub.com](https://git-scm.com/) repository which is a fork of the class master repository on my account. (You will need to set up a GitHub account if you do not already have one.)
	* Problem sets will be due on the day listed in the Daily Course Outline section of this syllabus (see below) unless otherwise specified. Late homework will not be graded.
* **Midterm:** The midterm will be given on the day listed in the Daily Course Outline below and will cover the material up to that point in the course.
* **Final Exam:** The final exam will be comprehensive and will be given on Tuesday, Dec. 6, from 10:30a.m. to 12:30p.m. in our classroom.


## Course schedule (lite)

| Date | Topic | Lab | Assignment |
|--------------|---------------------------------------|-----|-------------------|
| Mon, Sep. 26 | Intro to Computational Social Science |  |  |
| Tue, Sep. 27 |  | TBD |  |
| Wed, Sep. 28 | Scientific method |  |  |
| Mon, Oct. 3 | No class (conference) |  |  |
| Tue, Oct. 4 |  | TBD |  |
| Wed, Oct. 5 | Ethics |  |  |
| Mon, Oct. 10 | Observational data |  | Short Paper 1 due |
| Tue, Oct. 11 |  | TBD |  |
| Wed, Oct. 12 | Observational data |  |  |
| Mon, Oct. 17 | Observational data |  |  |
| Tue, Oct. 18 |  | TBD |  |
| Wed, Oct. 19 | Observational data |  |  |
| Mon, Oct. 24 | Collecting your own data |  | Short Paper 2 due |
| Tue, Oct. 25 |  | TBD |  |
| Wed, Oct. 26 | Collecting your own data |  |  |
| Mon, Oct. 31 | Experiments |  | Short Paper 3 due |
| Tue, Nov. 1 |  | TBD |  |
| Wed, Nov. 2 | Simulated data |  |  |
| Mon, Nov. 7 | Simulated data |  | Short Paper 4 due |
| Tue, Nov. 8 |  | TBD |  |
| Wed, Nov. 9 | Data visualization and description |  | Problem Set 1 due |
| Mon, Nov. 14 | Data visualization and description |  |  |
| Tue, Nov. 15 |  | TBD |  |
| Wed, Nov. 16 | Data visualization and description |  |  |
| Mon, Nov. 21 | Data visualization and description |  | Problem Set 2 due |
| Tue, Nov. 22 |  | TBD |  |
| Wed, Nov. 23 | Data visualization and description |  |  |
| Mon, Nov. 28 | Collaboration |  | Problem Set 3 due |
| Tue, Nov. 29 |  | TBD |  |
| Wed, Nov. 30 | Collaboration |  |  |
| Fri, Dec. 2 |  |  | Problem Set 4 due |
| Wed, Dec. 7 | Final exam [10:30am-12:30pm] |  |  |

## Course schedule (readings)

All readings are required unless otherwise noted. Adjustments can be made throughout the quarter; be sure to check this repository frequently to make sure you know all the assigned readings.

1. Introduction to computational social science
    * [Watts, D. J. (2007). A twenty-first century science. *Nature*, 445(7127), 489-489.](http://www.nature.com.proxy.uchicago.edu/nature/journal/v445/n7127/pdf/445489a.pdf)
    * [Lazer et. al. (2009) Computational Social Science. *Science*, 323, 721-723.](http://science.sciencemag.org.proxy.uchicago.edu/content/323/5915/721.full)
2. The scientific method
    * [Bhattacherjee, A. (2012). Social science research: principles, methods, and practices.](http://scholarcommons.usf.edu/oa_textbooks/3/) Chapters 1-4. Skim/review as needed.
    * [Anderson, C. (2008). The End of Theory: The Data Deluge Makes the Scientific Method Obsolete. *Wired*.](http://www.wired.com/2008/06/pb-theory/)
    * [Einav, L., & Levin, J. (2014). The Data Revolution and Economic Analysis. *Innovation Policy and the Economy*, 14(1), 1-24.](http://www.journals.uchicago.edu/doi/full/10.1086/674019)
    * [Schrodt, P. A. (2014). Seven deadly sins of contemporary quantitative political analysis. *Journal of Peace Research*, 51(2), 287-300.](http://jpr.sagepub.com.proxy.uchicago.edu/content/51/2/287.full)
3. No class ([Big Questions, Big Data, and Big Computation (B³): Frontiers of Computational Social Science](http://www.knowledgelab.org/events/detail/B3CSS/) conference)
4. Ethics
    * ["Chapter 6: Ethics." *Bit by Bit*.](http://www.bitbybitbook.com/en/ethics/)
    * Facebook emotional contagion study
        * [Kramer, A. D., Guillory, J. E., & Hancock, J. T. (2014). Experimental evidence of massive-scale emotional contagion through social networks. *PNAS*, 111(24), 8788-8790.](http://www.pnas.org/content/111/24/8788.full)
        * [Editorial Expression of Concern: Experimental evidence of massive-scale emotional contagion through social networks. (2014) *PNAS*, 111(29), 10779.](http://www.pnas.org/content/111/29/10779.1.full)
        * [Watts, D. J. (2014). Stop complaining about the Facebook study. It's a golden age for research. *The Guardian*.](https://www.theguardian.com/commentisfree/2014/jul/07/facebook-study-science-experiment-research)
        * [Rosen, J. (2014). Facebook's controversial study is business as usual for tech companies but corrosive for universities. *The Washington Post*.](https://www.washingtonpost.com/posteverything/wp/2014/07/03/dont-blame-facebook-for-screwing-with-your-mood-blame-academia/?utm_term=.e2bd90d038b1)
        * [Vertesi, J. (2014). The Real Reason You Should Be Worried About That Facebook Experiment. *Time*.](http://time.com/2950699/facebook-experiment-social-science-funding/)
    * [Parry, M. (2011). Harvard Researchers Accused of Breaching Students' Privacy. *Chronicle of Higher Education*.](http://chronicle.com/article/Harvards-Privacy-Meltdown/128166/)
    * [Zimmer, M. (2016). OkCupid Study Reveals the Perils of Big-Data Science. *Wired*.](https://www.wired.com/2016/05/okcupid-study-reveals-perils-big-data-science/)
    * [UChicago Social & Behavioral Sciences Institutional Review Board](https://sbsirb.uchicago.edu/)
        * Skim site
        * Specifically read ["Does My Research Need IRB Review?"](https://sbsirb.uchicago.edu/page/does-my-research-need-irb-review-0)
5. Observational data (counting)
    * ["Chapter 2: Observing Behavior." *Bit by Bit*.](http://www.bitbybitbook.com/en/observing-behavior/) Sections 2.1-2.4.1.3.
    * [King, G., Pan, J., & Roberts, M. E. (2013). How censorship in China allows government criticism but silences collective expression. *American Political Science Review*, 107(02), 326-343.](http://journals.cambridge.org.proxy.uchicago.edu/action/displayAbstract?fromPage=online&aid=8919476&fileId=S0003055413000014)
    * [Kossinets, G., & Watts, D. J. (2006). Empirical analysis of an evolving social network. *Science*, 311(5757), 88-90.](http://science.sciencemag.org.proxy.uchicago.edu/content/311/5757/88.full)
    * [Edelman, B. G., & Luca, M. (2014). Digital discrimination: The case of airbnb.com. *Harvard Business School NOM Unit Working Paper*, (14-054).](http://www.hbs.edu/faculty/Pages/item.aspx?num=46073)
    * [Chetty, R., Hendren, N., Kline, P., Saez, E., & Turner, N. (2014). Is the United States still a land of opportunity? Recent trends in intergenerational mobility. *The American Economic Review*, 104(5), 141-147.](http://pubs.aeaweb.org.proxy.uchicago.edu/doi/pdfplus/10.1257/aer.104.5.141)
6. Observational data (measuring)
    * [Bonica, A. (2014). Mapping the ideological marketplace. *American Journal of Political Science*, 58(2), 367-386.](http://onlinelibrary.wiley.com.proxy.uchicago.edu/doi/10.1111/ajps.12062/abstract)
    * [Wojcik, S. P., Hovasapian, A., Graham, J., Motyl, M., & Ditto, P. H. (2015). Conservatives report, but liberals display, greater happiness. *Science*, 347(6227), 1243-1246.](http://science.sciencemag.org.proxy.uchicago.edu/content/347/6227/1243.full)
    * Emotional timeline of September 11, 2001
        * [Back, M. D., Küfner, A. C., & Egloff, B. (2010). The emotional timeline of September 11, 2001. *Psychological Science*, 21(10), 1417-1419.](http://pss.sagepub.com.proxy.uchicago.edu/content/21/10/1417.short)
        * [Pury, C. L. (2011). Automation can lead to confounds in text analysis Back, Küfner, and Egloff (2010) and the Not-So-Angry Americans. *Psychological Science*, 22(6), 835-836.](http://pss.sagepub.com.proxy.uchicago.edu/content/22/6/835)
        * [Back, M. D., Küfner, A. C., & Egloff, B. (2011). "Automatic or the people?" Anger on September 11, 2001, and lessons learned for the analysis of large digital data sets. *Psychological Science*, 22(6), 837-838.](http://pss.sagepub.com.proxy.uchicago.edu/content/22/6/837.short)
7. Observational data (forecasting)
    * [2.4.2 Forecasting and nowcasting. *Bit by Bit*.](http://www.bitbybitbook.com/en/observing-behavior/designs/forecasting/)
    * [Goel, S., Hofman, J. M., Lahaie, S., Pennock, D. M., & Watts, D. J. (2010). Predicting consumer behavior with Web search. *PNAS*, 107(41), 17486-17490.](http://www.pnas.org/content/107/41/17486.full?sid%3D3c84ffa2-362d-46ba-b735-ea41ef21ace7)
    * Google Flu Trends
        * [Ginsberg, J., Mohebbi, M. H., Patel, R. S., Brammer, L., Smolinski, M. S., & Brilliant, L. (2009). Detecting influenza epidemics using search engine query data. *Nature*, 457(7232), 1012-1014.](http://www.nature.com.proxy.uchicago.edu/nature/journal/v457/n7232/full/nature07634.html)
        * [Lazer, D., Kennedy, R., King, G., & Vespignani, A. (2014). The parable of Google flu: traps in big data analysis. *Science*, 343(6176), 1203-1205.](http://science.sciencemag.org.proxy.uchicago.edu/content/343/6176/1203.full)
    * Forecasting terrorism
        * [Schrodt, P. A., Yonamine, J., & Bagozzi, B. E. (2013). Data-based computational approaches to forecasting political violence. In *Handbook of computational approaches to counterterrorism* (pp. 129-162). Springer New York.](http://link.springer.com.proxy.uchicago.edu/chapter/10.1007/978-1-4614-5311-6_7)
        * [Brandt, P. T., Freeman, J. R., & Schrodt, P. A. (2011). Real time, time series forecasting of inter-and intra-state political conflict. *Conflict Management and Peace Science*, 28(1), 41-64.](http://cmp.sagepub.com.proxy.uchicago.edu/content/28/1/41.short)
8. Observational data (approximating experiments)
    * [2.4.3 Approximating experiments. *Bit by Bit*.](http://www.bitbybitbook.com/en/observing-behavior/designs/approximating-experiments/).
    * [Phan, T. Q., & Airoldi, E. M. (2015). A natural experiment of social network formation and dynamics. *PNAS*, 112(21), 6595-6600.](http://www.pnas.org/content/112/21/6595.full)
    * [Hersh, E. D. (2013). Long-term effect of September 11 on the political behavior of victims' families and neighbors. *PNAS*, 110(52), 20959-20963.](http://www.pnas.org/content/110/52/20959.full)
    * [Cohen, P., et al. (2016). Using Big Data to Estimate Consumer Surplus: The Case of Uber. Working paper.](https://drive.google.com/file/d/0B3y6Efb4V73TdG9pV1F0VGpsM1E/view)
9. Collecting data (fundamentals)
    * ["Chapter 3: Asking Questions." *Bit by Bit*.](http://www.bitbybitbook.com/en/asking-questions/) Sections 3.1-3.4.
    * [Schuldt, J. P., Konrath, S. H., & Schwarz, N. (2011). "Global warming" or "climate change"? Whether the planet is warming depends on question wording. *Public Opinion Quarterly*, 75(1): 115-124.](http://poq.oxfordjournals.org.proxy.uchicago.edu/content/75/1/115)
    * Pew Research Center Survey Methodology
        * [U.S. Survey Research: Our survey methodology in detail](http://www.pewresearch.org/methodology/u-s-survey-research/our-survey-methodology-in-detail/)
        * [U.S. Survey Research: Sampling](http://www.pewresearch.org/methodology/u-s-survey-research/sampling/)
    * [Wang, W., Rothschild, D., Goel, S., & Gelman, A. (2015). Forecasting elections with non-representative polls. *International Journal of Forecasting*, 31(3), 980-991.](http://www.sciencedirect.com.proxy.uchicago.edu/science/article/pii/S0169207014000879)
    * [The Upshot: We Gave Four Good Pollsters the Same Raw Data. They Had Four Different Results.](http://www.nytimes.com/interactive/2016/09/20/upshot/the-error-the-polling-world-rarely-talks-about.html?_r=1)
10. Collecting data (digitally-enriched)
    * ["Chapter 3: Asking Questions." *Bit by Bit*.](http://www.bitbybitbook.com/en/asking-questions/) Sections 3.5-3.7.
    * [Lax, J. R., & Phillips, J. H. (2009). How should we estimate public opinion in the states?. *American Journal of Political Science*, 53(1), 107-121.](http://onlinelibrary.wiley.com.proxy.uchicago.edu/doi/10.1111/j.1540-5907.2008.00360.x/full)
    * [Ansolabehere, S., & Hersh, E. (2012). Validation: What big data reveal about survey misreporting and the real electorate. *Political Analysis*, 20(4): 437-459.](http://pan.oxfordjournals.org.proxy.uchicago.edu/content/20/4/437.full)
    * [Blumenstock, J., Cadamuro, G., & On, R. (2015). Predicting poverty and wealth from mobile phone metadata. *Science*, 350(6264), 1073-1076.](http://science.sciencemag.org.proxy.uchicago.edu/content/350/6264/1073.full)
    * [Salganik, M. J., & Levy, K. E. (2015). Wiki surveys: Open and quantifiable social data collection. *PLoS One*, 10(5), e0123483.](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0123483)
    * [Sugie, N. F. (2016). Utilizing Smartphones to Study Disadvantaged and Hard-to-Reach Groups. *Sociological Methods & Research*, 0049124115626176.](http://smr.sagepub.com.proxy.uchicago.edu/content/early/2016/01/18/0049124115626176.full)
11. Experiments
    * ["Chapter 4: Running experiments." *Bit by Bit*.](http://www.bitbybitbook.com/en/running-experiments/)
    * [Adams, T. G., Stewart, P. A., & Blanchar, J. C. (2014). Disgust and the politics of sex: exposure to a disgusting odorant increases politically conservative views on sex and decreases support for gay marriage. *PLoS One*, 9(5), e95572.](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0095572)
    * [Bond, R. M., Fariss, C. J., Jones, J. J., Kramer, A. D., Marlow, C., Settle, J. E., & Fowler, J. H. (2012). A 61-million-person experiment in social influence and political mobilization. *Nature*, 489(7415), 295-298.](http://www.nature.com.proxy.uchicago.edu/nature/journal/v489/n7415/full/nature11421.html)
    * [King, G., Pan, J., & Roberts, M. E. (2014). Reverse-engineering censorship in China: Randomized experimentation and participant observation. *Science*, 345(6199), 1251722.](http://science.sciencemag.org.proxy.uchicago.edu/content/345/6199/1251722.full)
    * [Edelman, B. G., Luca, M., & Svirsky, D. (2015). Racial Discrimination in the Sharing Economy: Evidence from a Field Experiment. *Harvard Business School NOM Unit Working Paper*, (16-069).](http://www.hbs.edu/faculty/Pages/item.aspx?num=50258)
12. Simulated data
    * "[Indirect Inference](http://www.econ.yale.edu/smith/palgrave7.pdf)," New Palgrave Dictionary of Economics
    * Wolpin, Kenneth I., *The Limits of Inference without Theory*, MIT Press, 2013.
    * Benoit, Kenneth, "[Simulation Methodologies for Political Scientists](http://www.kenbenoit.net/pdfs/benoit_2001_TPM.pdf)," *The Political Methodologist*, 10:1, pp. 12-16.
    * Davidson, Russell and James G. MacKinnon, "Section 9.6: The Method of Simulated Moments," *Econometric Theory and Methods*, Oxford University Press, 2004.
13. Simulated data (cont.)
14. Data visualization and description
    * Scott, David W., Chapters 1-4, *Multivariate Density Estimation: Theory, Practice, and Visualization*, 2nd edition, John Wiley & Sons, 2015.
15. Data visualization and description (cont.)
16. Data visualization and description (cont.)
17. Data visualization and description (cont.)
18. Data visualization and description (cont.)
19. Collaboration: distributed data collection and analysis
    * ["Chapter 5: Collaborating." *Bit by Bit*.](http://www.bitbybitbook.com/en/mass-collaboration/)
    * Chacon, Scott and Ben Straub, [*Pro Git: Everything You Need to Know about Git*](https://git-scm.com/book/en/v2), 2nd edition, Apress, 2014.
    * OSPC Data Visualizations project
20. Collaboration: distributed data collection and analysis (cont.)


## Disability services

If you need any special accommodations, please provide us with a copy of your Accommodation Determination Letter (provided to you by the Student Disability Services office) as soon as possible so that you may discuss with me how your accommodations may be implemented in this course.
