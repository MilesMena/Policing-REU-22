README REGARDING LARGE FILES (.gz)

Certain files are large enough that they require extra compression BEFORE
being added to the data cart.  Typically, these files are larger than 4
gigabytes uncompressed.  Such files are compressed using 'gzip' (GNU zip) and
have a ".gz" file extension.

After extracting files from the data cart, any files with an extension of
".gz" will need to be individually extracted before they can be used.
Utilities such as 'gunzip' (GNU unzip), WinZip and 7-Zip can decompress .gz
files.

This applies to following file(s) for ICPSR study 37066, dataset 1:

da37066-0001.dta.gz
da37066-0001.stc.gz
da37066-0001.tsv.gz
da37066-0001.txt.gz
