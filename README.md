# aRchaic

An R package for exploration, clustering and visualization of DNA
damage patterns.

<img src="vignettes/vignette_fig.png" alt="Structure Plot" height="500" width="600">

## Authors

[Kushal K Dey*](http://kkdey.github.io), [Hussein Al-Asadi
*](https://halasadi.wordpress.com), [John Novembre](http://jnpopgen.org), [Matthew Stephens](http://stephenslab.uchicago.edu)

## Installation

First and foremost, the user is required to install 

* [python](https://www.python.org/downloads) 
* [R/RStudio](https://www.rstudio.co/) 

And Python packages,

* [pysam](http://pysam.readthedocs.io/en/latest/installation.html) 
* [pyfaidx](https://pythonhosted.org/pyfaidx/#installation)

**aRchaic** requires R version to be 3.4 or greater. If your R version
is lower than that, please upgrade.

Upon completion of these steps, start a new R session and install
aRchaic:

```
install.packages("remotes")
remotes::install_github("kkdey/aRchaic")
```

Now you should be able to load aRchaic into R.

```
library(aRchaic)
```

## Tutorial

Get started with the tutorial
[here](https://kkdey.github.io/aRchaic/articles/archaic.html).

## Support

* Create a new [issue](https://github.com/kkdey/aRchaic/issues) to report bugs and/or request features.
* Contact Kushal Dey (kkdey@uchicago.edu) or Hussein Al-Asadi (halasadi@uchicago.edu)

Also users are welcome to contribute to the package by submitting pull request. 

## Citation

Al-Asadi, H., Dey, K., Novembre, J. and Stephens, M., 2018. Inference and visualization of DNA damage patterns using a grade of membership model. bioRxiv, p.327684.


## License

Distributed under the terms of the GNU General Public License as
published by the Free Software Foundation, either version 3 of the
License, or (at your option) any later version.

The repository is distributed in the hope that it will be useful, but
without any warranty; without even the implied warranty of
merchantability or fitness for a particular purpose. Please see
LICENSE for more details.

## Acknowledgements

The authors would like to acknowledge Anna Di Rienzo, Choongwon Jeong,
Anna Gosling, John Lindo, David Witonsky, Joseph Marcus, John
Blischak, Peter Carbonetto and members of Stephens Lab and Novembre
Lab for helpful discussions.
