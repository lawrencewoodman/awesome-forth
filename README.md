# Awesome Forth

Resources and links for the Forth programming language

> Forth is an imperative stack-based computer programming language and programming environment.

## Getting started

### Forth systems

I recommend trying GForth which is a cross platform forth compiler. It seemed to be the easiest version to install on any modern OS

+ [GForth](http://www.gnu.org/software/gforth/) Gforth uses GCC to compile a fast direct or indirect threaded Forth

    > brew install gforth (OSX)
    
    or
    
    > sudo apt install gforth (Debian-like Linux)
    
    Once installed, type `gforth` to start an interactive session.

+ [retroforth](http://retroforth.org/) modern forth with good infrastructure and docs
+ [SP-Forth](https://github.com/rufig/spf) crossplatform forth with [huge shared code library from different developers](https://github.com/rufig/spf/tree/master/devel) included

### Books

+ [Starting Forth](https://www.forth.com/starting-forth/) Free PDF of best introduction book on Forth
+ [Thinking Forth](http://www.dnd.utwente.nl/~tim/colorforth/Leo-Brodie/thinking-forth.pdf) Free PDF
+ [Programming Forth](http://www.mpeforth.com/arena/ProgramForth.pdf) Free PDF
+ [Beginners Guide](http://galileo.phys.virginia.edu/classes/551.jvn.fall01/primer.htm)
+ [Forth Primer](http://ficl.sourceforge.net/pdf/Forth_Primer.pdf)

### Videos

+ [A Little Bit of Forth](https://www.youtube.com/watch?v=Q6FflPMHZP4) A great introduction
+ [Over the Shoulder 1 - Text Preprocessing in Forth](https://www.youtube.com/watch?v=mvrE2ZGe-rs) A great example of how elegant and simple forth can be in the hands of an experienced forth programmer (Samuel A. Falvo II)

## Advanced stuff

### Chuck's Moore heritage

Check out _everything_ from Chuck Moore. He has very unusual style of both thinking and teaching, and you don't have to agree with everything he said, but it's really a fantastic intro to the highly-factored software. Main entry points are [here](https://colorforth.github.io/) and [here](https://www.youtube.com/results?search_query=chuck+moore).

### Forth Dimensions

Scanned copies of the Forth Magazine from the past: [Forth Dimensions](http://www.forth.org/fd/contents.html)

### Other Forths

There are lots of different customized Forths. Some of them are quite unconventional, some are standard. There's a list in no particular order, with some very opiniated comments:

+ [ColorForth](https://colorforth.github.io/install.htm) Latest Forth system made by Chuck Moore, the inventor of the very first Forth itself. Very unconventional: uses tokenized source with very early binding, and uses colorful visualisation of compilation/interpretation/comments modes.
+ [Rainbow Forth](http://rainbowforth.appspot.com/) Perhaps simpliest ColorForth that you may start in your browser. Tons of cool documentation too!


### Forth-as-a-Code

+ [Jones Forth](https://github.com/AlexandreAbreu/jonesforth/blob/master/jonesforth.S) "A sometimes minimal FORTH compiler", heavily commented -- you may follow up all the decisions made while building forth from the scratch.

# Similar languages

Forth inspired some similar languages which you may also find interesting. They are usually fall under the category of [Concatenative programming languages](https://en.wikipedia.org/wiki/Concatenative_programming_language).

## Joy

+ [Joy Homepage](http://www.latrobe.edu.au/humanities/research/research-projects/past-projects/joy-programming-language)

## Factor

A more modern and functional version of Factor.

[Factor: an extensible interactive language](https://www.youtube.com/watch?v=f_0QlhYlS8g)

# Misc

+ [OForth](http://www.oforth.com) Oforth is an imperative, dynamic, non-typed, stack-based language
