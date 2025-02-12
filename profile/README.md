## PAMGuard Tutorials and Learning Resources

These repositories are all dedicated to development of PAMGuard training materials. 

Published materials are held in releases within the appropriate repository. A typical PAMGuard user wanting to learn how to use PAMGuard should probably **not** be looking through the pages in these repositories. 
Information linking the published tutorial documents is available in the appropriate 
page within the [tutorials section](https://www.pamguard.org/tutorials.html) of the PAMGuard website. If there isn't a link from the PAMGuard website, then you're possibly
looking at a tutorial document that is still under development, and you do so at your own peril. 

Configuration files and data for use with each tutorial are made available using  a variety of resources. Configuration files may be held on these pages with the tutorial documentation. Larger files, 
such as raw sound files will be hoseted on a different data repository, such as Zenodo. See the notes in specific tutorials on where to find the data and any configuration files you might need. 
Again, if you're a user, this information will be
clear in the tutorial documents themselves and the information on the [tutorials pages](https://www.pamguard.org/tutorials.html) do you don't need to be grubbing around here. 

Tools for preparing the materials vary. Some are using MS Word, others [Quarto](https://quarto.org/), which is a free word processing package built into [R Studio](https://posit.co/download/rstudio-desktop/) that uses a 
combination of [Markdown](https://en.wikipedia.org/wiki/Markdown) and [Tex](https://en.wikipedia.org/wiki/TeX). 

Materials on this site are open source. You're free to look around and fork the source material, and to incorporate it into your own training programmes.

| Tutorial | Prerequisites |  Outcomes |
| -------- | --------- | --------- |
| [Getting Started](https://github.com/PAMGuardLearning/GettingStarted) | None | Basic understanding of running detectors in PAMGuard, mostly using pre-built configurations |
| [Introduction to PAMGuard](https://github.com/PAMGuardLearning/Intro2Pamguard) | None | More advanced configuration of detectors in PAMGuard, starting with a blank configuration, Looking at processed data using the PAMGuard Viewer, and exporting data to Matlab and R |
| Deep Learning | Introduction to PAMGuard | Learn how to load Deep Learning (AI) models, run them in PAMGuard, and view the results |
| [Tethys Tutorial](https://github.com/PAMGuardLearning/pamguard_tethys/tree/main/TethysTutorial) | Introduction to PAMGuard | Guide to configuring [Tethys](https://tethys.sdsu.edu/), launching the server, and exporting PAMGuard data |
| [Tethys in a Hurry](https://github.com/PAMGuardLearning/pamguard_tethys/tree/main/QuickTethys) | Introduction to PAMGuard  and know how to setup and run a [Tethys](https://tethys.sdsu.edu/) Sever | Quicker version of the above tutorial for those already familiar with Tethys and who know thier way around the PAMGuard Viewer |
| [Batch Processing](https://github.com/PAMGuardLearning/batchprocessing/tree/main/BatchBasics) | Introduction to PAMGuard | Learn how to process multiple datasets with the same configuration using  normal mode to process raw data and offline tasks on already processed data (e.g. click reclassification) |
|  [Batch Tethys Output](https://github.com/PAMGuardLearning/batchprocessing/tree/main/BatchAndTethys) | Batch Processing Tutorial and one of the Tethys Tutorials | Learn how to output multiple datasets from PAMGuard to Tethys |

