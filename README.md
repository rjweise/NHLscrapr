# NHLscrapr
Scraper for play by play data from NHL API, using R
This code is written in RStudio, using the jsonlite package. I am just a beginner in R so I am sure many improvements can be made, but as I am writing this I already scraped almost 600 files for the 2015 season without a glitch (knock, knock). I also did a good amount of testing.

Purpose is to read NHLs Game Feed files in JSON one by one, select a subset of headers / variables, organize these and convert them to a csv-file. These files can then be combined in the Windows command line (CMD) with "copy * combined.csv" to a single season file, which on its own can be used in Tableau (or any other tool of choice that reads CSV).

I did run into the issue that apparently some of the files are empty. They have some base information, but there are no plays. these files are not written CSV (in case you are wondering why the list is not complete)

Any thoughts? Please let me know, here or on twitter @rjweise
