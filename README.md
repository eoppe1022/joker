# joker
The package that you've always wanted -- a package that returns a random knock-knock joke

## Installation
You can install `joker` from github with:
````
# install.packages("devtools")
devtools::install_github("eoppe1022/joker", force = TRUE)
````

To load the package:
````
library(joker)
````

## The Bare Bones
The `joker` package is built on 1 function:
- `knock_knock()`

which returns a random knock-knock joke, one of the 300+ pre-installed knock-knock jokes.

## Examples
````
library(joker)

knock_knock()
#> 
#> 
#> Knock knock.
#> 
#> Who’s there?
#> 
#> Olive.
#> 
#> Olive who?
#> 
#> Olive you. Do you love me too?
#>
#> 

knock_knock()
#> 
#> 
#> Knock, knock.
#> 
#> Who's there?
#> 
#> Ozzie
#> 
#> Ozzie who?
#> 
#> Ozzie you later!
#>
#> 
````

## Final Notes
Please be kind. Report any issues [here](https://github.com/eoppe1022/joker/issues), and I'll do the best that I can to solve them. I'd welcome any Pull Requests too, if you have any changes in mind.

You can follow and message me on [Twitter](http://www.twitter.com/OppenheimerEvan). Feel free to e-mail me at eoppe1022 (at) gmail.com with any questions.

Enjoy!
