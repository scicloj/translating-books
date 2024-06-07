*“One way to learn a lot of mathematics is by reading the first chapters of many books.”* -- Paul R. Halmos

# translating-books
In this project, we maintain a list of books that we wish to translate to Clojure, mostly around data and science.

## Background
A few of us at [Scicloj](https://scicloj.github.io/) have have started looking into translating books again.

There are quite a few great books for data and science written with another programming language, where the license allows converting them to Clojure and adapting the text.

This is discussed at the [Clojurians Zulip chat](https://scicloj.github.io/docs/community/chat/) at the revived topic thread [#data-science](https://clojurians.zulipchat.com/#narrow/stream/151924-data-science) > [translating a book](https://clojurians.zulipchat.com/#narrow/stream/151924-data-science/topic/translating.20a.20book).

These days we are figuring out a workflow for writing books as literate (and testable!) Clojure namespaces. It looks promising.

If you are a Clojurian looking to learn statistics, machine learning, data visualization, or some related algorithms, it can be a good pathway for a steady and insightful process.
We can pick one of the relevant books or part of it and start a journey. We will help you out, and we can pair up and explore together.

Please [reach out](https://scicloj.github.io/docs/community/contact/).

## Licenses

Various licenses of books' text and code determine the ways we may use them as inspiration for Clojure books.

- [MIT](https://opensource.org/license/mit) - just fine
- [CA BY-SA 3.0 DEED](https://creativecommons.org/licenses/by-sa/3.0/deed.en) - free to adapt
- [CC BY-NC-SA 4.0 DEED](https://creativecommons.org/licenses/by-nc-sa/4.0/) - free to adapt
- [CC BY-NC-ND 3.0](https://creativecommons.org/licenses/by-nc-nd/3.0/) - no derivatives allowed
- [GNU GPL 2](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html) - adaptation and reuse should also be GPL, which means some users will have to avoid using the code
- [GNU GPL 3](https://www.gnu.org/licenses/gpl-3.0.html) - similar to GNU GPL 2

## List of books

This is currently an unordered list, collected from Zulip discussions.

| Book                                                                                                                                                                                         | Authors                                                      | Source                                                                                                                                                  | License                                                                                 | Comments                                                                                                                                                                                                                                                                                     | Translation status                                                                                                                                                                                                                                 |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)                                                                                                         | Jake VanderPlas                                              | [jakevdp/...](https://github.com/jakevdp/PythonDataScienceHandbook)                                                                                     | text - CC BY-NC-ND 3.0; code - MIT                                                      |                                                                                                                                                                                                                                                                                              | started at [scicloj-data-science-handbook](https://github.com/scicloj/scicloj-data-science-handbook/) (2021), recently restarted at [python-data-science-handbook-in-clojure](https://github.com/scicloj/python-data-science-handbook-in-clojure/) |
| [R for Data Science 1st ed.](https://r4ds.had.co.nz/)                                                                                                                                        | Hadley Wickham and Garrett Grolemund                         | ?                                                                                                                                                       | CC BY-NC-ND 3.0                                                                         |                                                                                                                                                                                                                                                                                              | started some drafts in the past                                                                                                                                                                                                                    |
| [R for Data Science 2nd ed.](https://r4ds.hadley.nz/)                                                                                                                                        | Hadley Wickham, Mine Çetinkaya-Rundel, and Garrett Grolemund | [hadley/r4ds](https://github.com/hadley/r4ds)                                                                                                           | CC BY-NC-ND 3.0                                                                         | permission from the authors & publisher                                                                                                                                                                                                                                                      |                                                                                                                                                                                                                                                    |
| [Introduction to Data Science](https://rafalab.dfci.harvard.edu/dsbook-part-1/)                                                                                                              | [Rafael A Irizarry](https://github.com/rafalab)              | [rafalab/dsbook-part-1](https://github.com/rafalab/dsbook-part-1)                                                                                       | CC BY-NC-SA 4.0 DEED                                                                    | The author's [earlier book](https://rafalab.dfci.harvard.edu/pages/books.html) has mixed reviews                                                                                                                                                                                             |                                                                                                                                                                                                                                                    |
| [Advanced Data Science](https://rafalab.dfci.harvard.edu/dsbook-part-2/prob/intro-to-prob.html)                                                                                              | [Rafael A Irizarry](https://github.com/rafalab)              | [rafalab/dsbook-part-2](https://github.com/rafalab/dsbook-part-2)                                                                                       | CC BY-NC-SA 4.0 DEED                                                                    |                                                                                                                                                                                                                                                                                              |                                                                                                                                                                                                                                                    |
| [Clojure for Data Scince](https://clojuredatascience.com/pages/about.html)                                                                                                                   | [Henry Harner](https://henrygarner.com/)                     | -                                                                                                                                                       | nonfree                                                                                 | Great teaching, outdated use of libraries, can be a great source of inspiration                                                                                                                                                                                                              |                                                                                                                                                                                                                                                    |
| [IPSUR: Introduction to Probability and Statistics Using R](https://github.com/gjkerns/IPSUR)                                                                                                | G. Jay Kerns                                                 | [gjkerns/IPSUR](https://github.com/gjkerns/IPSUR)                                                                                                       | GNU GPL 3                                                                               | great teaching of probability contepts through code (dedicated package)                                                                                                                                                                                                                      |                                                                                                                                                                                                                                                    |
| [Think Stats 2e](https://greenteapress.com/thinkstats2/html/index.html)                                                                                                                      | [Allen B. Downey](https://www.allendowney.com/wp/)           | [AllenDowney/ThinkStats2](https://github.com/AllenDowney/ThinkStats2)                                                                                   | CC BY-NC-SA 4.0 DEED, but the repo is GPL3                                              | The author has agreed we'd convert it.                                                                                                                                                                                                                                                       | 1e has been partially converted by differen people; Karthik is looking into 2e;                                                                                                                                                                    |
| [Modern Statistics with R](https://modernstatisticswithr.com/)                                                                                                                               | [Måns Thulin](https://mansthulin.se/)                        | [mthulin/mswr-book](https://github.com/mthulin/mswr-book)                                                                                               | CC BY-NC-SA 4.0 DEED                                                                    | RMarkdown, notebook conversion can be partially automated                                                                                                                                                                                                                                    | Carsten, generateme, Daniel independently started working on some parts                                                                                                                                                                            |
| [Regression and Other Stories](https://avehtari.github.io/ROS-Examples/)                                                                                                                     | Andrew Gelman, Jennifer Hill, Aki Vehtari                    | [examples in various languages and libraries](https://avehtari.github.io/ROS-Examples/examples)                                                         | [the tidyverse port](https://github.com/behrman/ros) by Bill Behrman is CC BY-NC-SA 4.0 | discussions: [Learn Bayes Stats](https://learnbayesstats.com/): [#20](https://learnbayesstats.com/episode/20-regression-and-other-stories-with-andrew-gelman-jennifer-hill-aki-vehtari/) & [#106](https://learnbayesstats.com/episode/106-active-statistics-two-truths-a-lie-andrew-gelman/) |                                                                                                                                                                                                                                                    |
| [Time Series Forecasting in Python](https://www.manning.com/books/time-series-forecasting-in-python-book)                                                                                    | Marco Peixeiro                                               | [marcopeix/...](https://github.com/marcopeix/TimeSeriesForecastingInPython)                                                                             | code - Apache 2.0                                                                       |                                                                                                                                                                                                                                                                                              | Amer started - [xfthhxk/time-series-analysis](https://github.com/xfthhxk/time-series-analysis)                                                                                                                                                     |
| [Bayesian Methods for Hackers](https://dataorigami.net/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/)                                                                          | Cameron Davidson Pilon                                       | [CamDavidsonPilon/...](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers) - original version (using PyMC3) | MIT                                                                                     | Conversions to other Bayesian libraries exist, e.g. [to R + Stan](https://jduncstats.com/bayes-hackr/2021-01-08-bayes-hackr-ch1/) by [Josh Duncan](https://github.com/joshualeond)                                                                                                           |                                                                                                                                                                                                                                                    |
| [Think Bayes 2e](https://greenteapress.com/wp/think-bayes/)                                                                                                                                  | [Allen B. Downey](https://www.allendowney.com/wp/)           | [AllenDowney/ThinkBayes2](https://github.com/AllenDowney/ThinkBayes2)                                                                                   | MIT                                                                                     |                                                                                                                                                                                                                                                                                              |                                                                                                                                                                                                                                                    |
| [Bayesian Modeling and Computation in Python](https://bayesiancomputationbook.com/welcome.html)                                                                                              | Osvaldo A Martin, Ravin Kumar, and Lao Junpeng               | [.../BookCode_Edition1](https://github.com/BayesianModelingandComputationInPython/BookCode_Edition1)                                                    | text - CC BY-NC-SA 4.0 DEED; code - GPL 2                                               | we had a reading group at the [Jointprob community](https://scicloj.github.io/docs/community/groups/jointprob/)                                                                                                                                                                              | Alexandru and Daniel are looking                                                                                                                                                                                                                   |
| [Introduction to Modern Statistics (2e)](https://openintro-ims2.netlify.app/)                                                                                                                | Mine Çetinkaya-Rundel and Johanna Hardin                     | [openintrostat/ims](https://github.com/openintrostat/ims)                                                                                               | [OpenIntro license](https://www.openintro.org/license/) - CC By-SA 3.0                  | WIP; a Quarto book with R Tidyverse code, lots of styling and illustrations                                                                                                                                                                                                                  |                                                                                                                                                                                                                                                    |
| [Causal Inference for the Brave and True](https://matheusfacure.github.io/python-causality-handbook/landing-page.html)                                                                       | Matheus Facure                                               | [matheusfacure/...](https://github.com/matheusfacure/python-causality-handbook)                                                                         | MIT                                                                                     |                                                                                                                                                                                                                                                                                              |                                                                                                                                                                                                                                                    |
| [Introduction to Statistical Learning](https://www.statlearning.com/)                                                                                                                        | Gareth James, Daniela Witten, Trevor Hastie, Rob Tibshirani  | ?                                                                                                                                                       | GPL?                                                                                    |                                                                                                                                                                                                                                                                                              |                                                                                                                                                                                                                                                    |
| [The Elements of Statistical Learning](https://hastie.su.domains/Papers/ESLII.pdf)                                                                                                           | Trevor Hastie , Robert Tibshirani , Jerome Friedman          | ?                                                                                                                                                       | GPL?                                                                                    |                                                                                                                                                                                                                                                                                              |                                                                                                                                                                                                                                                    |
| [Machine Learning Foundations](https://github.com/jonkrohn/ML-foundations/)                                                                                                                  | John Krohn                                                   | [jonkrohn/ML-foundations]((https://github.com/jonkrohn/ML-foundations/))                                                                                | MIT                                                                                     | a series of Jupyter notebooks accompanying a video course, offering introductions to core topics at the foundations of ML                                                                                                                                                                    |                                                                                                                                                                                                                                                    |
| [First Semester in Numerical Analysis with Julia](https://open.umn.edu/opentextbooks/textbooks/710) ([pdf](https://uilis.usk.ac.id/oer/files/original/aa4c33bd9eeba8b979b3033a615b60c8.pdf)) | Giray Ökten                                                  | ?                                                                                                                                                       | CC BY-NC-SA 4.0 DEED                                                                    |                                                                                                                                                                                                                                                                                              |                                                                                                                                                                                                                                                    |

## Other resources
- [Big Book of R](https://www.bigbookofr.com/) by OScar Baruffa - a large collection of R resources
- [Open Intro](https://www.openintro.org/) is a project creating free resources directed at teaching (college, high-school)
  - [Github project](https://github.com/OpenIntroStat)
  - [OpenIntro License](https://www.openintro.org/license/) - CC BY-SA 3.0 DEED
- [Open Textbook Library](https://open.umn.edu/opentextbooks/) - a collection of open textbooks
