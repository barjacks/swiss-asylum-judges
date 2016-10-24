# Biased Swiss Judges

## Analyzing 30'000 verdicts of the Swiss Federal Administrative Court on deportation appeals

- For years, lawyers and attorneys working in Switzerland have sensed that cases of migrants appealing deportation weren't treated equally by the 24 judges of the [Swiss Federal Administrative Court](http://www.bvger.ch/index.html?lang=en). To explore this claim we scraped the 30'000 verdicts of the court since 2007 from the court's data base. Then used the Python libraries [pandas](http://pandas.pydata.org/) and [glob](https://docs.python.org/2/library/glob.html) to explore what the data says.

- The article with our findings was published on 10.10.2016 in the [Tages-Anzeiger](http://www.tagesanzeiger.ch). You'll find the PDF in this repository. Along with the code and regular expressions we used to query the 30'000 text files.

- We haven't published the entire text files here as they total 700MB. However, you'll find an example of one of the files in the repository. If you require them, please get in touch with barnaby.skinner@sonntagszeitung.ch or simone.rau@tagesanzeiger.ch

- If you have problems viewing the [Jupyter Notebook](http://jupyter.org/) 'Analysing 30000 Verdicts.ipynb' (I'm not sure why Github sometimes throws an error message at you) view the raw version of the file, download it on to your device. Then open it locally.

- And we are sure that code is far from being pythonic enough. Please feel free to contribute smarter ways of writing this code.
