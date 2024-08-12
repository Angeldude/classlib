## CLASSLIB for Abstract Algebra: a computational approach

### What is this?
This is a math library for the Abstract Algebra book by Charles C. Sims. It took me a while to hunt this down before I decided to search on Github and found just one repository with a single file: a Dyalog APL workspace.

It was from here that I took it upon myself to export all the components so that I can put it in a more 'universal' APL format.

### Work in Progress
This is still incomplete, if you want to start using the full CLASSLIB, use the Dyalog file (.dws), all the other files are missing some variable definitions but all the functions are there!

### What's in it?
I provide `.atf` files for each function and variable, 1 full `.atf` file with everything in it, an APLX workspace with everything in it, and an exported Dyalog extended workspace from the original Dyalog file.

I've also included pdf printouts of the function and variable definitions so they can be viewed and open up potential for porting to other systems.

Speaking of porting, I started a `.ijs` file for JLang with some of those variable definitions. Who knows, maybe I'll port the entire library into J.

### To be converted?
This file contains all the variables that I need to re-introduce because the export feature on Dyalog was erroring on matrix variable definitions.

### What's this html file?
I found this on a site which was supposed to be hosting the classlib atf file, unfortunately I can't load the site again and I had the foresight to save the html page.
