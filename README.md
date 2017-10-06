# where I mess around with trying to identify sources found using wavdetect
.dat files in "object_catalogs" show coordinates of sources that did not match to a known source
.txt files in "object_catalogs" show sources that were identified in simbad. 

Things I would like to do: \\
a. figure out what objects show up consistently in all observations
b. look at the objects that only show up in the short (10ks) observation
c. find a way to automate some kind of flux estimate--perhaps using python to get source count rates (not sure how to do background), then use some kind of interface with pimms to convert count rate to a flux. 
d. use this to see if there is variability in sources, or if anything is especially bright.
e. see if any of the coordinates that didn't have a simbad match are persistant. 
