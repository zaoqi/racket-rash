<p align="center"><img src="./img/rash-logo.svg" width="200"></p>
<h1 align="center">Rash: The Reckless Racket Shell</h1>

<p align="center">
<a href="https://travis-ci.org/willghatch/racket-rash"><img src="https://travis-ci.org/willghatch/racket-rash.svg?branch=master"></a>
<a href="http://docs.racket-lang.org/rash@rash/index.html"><img src="https://img.shields.io/badge/Docs-Scribble-blue.svg" alt="Scribble Docs"></a>
<a href="https://docs.racket-lang.org/rash/index.html#%28part._.Stability%29"><img src="https://img.shields.io/badge/Stability-experimental-orange.svg" alt="Experimental"></a>
</p>


Rash is a shell language, library, and REPL for Racket.

Use as a repl that is as convenient for pipelining programs as Bash is, but has all the power of Racket.  Use as a scripting language with `#lang rash`.  Embed in normal Racket files with `(require rash)`, and mix freely with any other Racket language or library.

Rash is in active development, and is not stable as a language.  But I use it as my default interactive shell on my laptop.  It's far from complete, but I already like it much better than Bash.  Give it a try.


## Getting started

### Prerequisites

Rash does work on windows, but it works better and is more useful on unix based systems.

To install, you will need a working instalation of [racket](https://download.racket-lang.org/) v6.12.

### Installation
You can either install with racket's built in package manager, [`raco`](https://docs.racket-lang.org/raco/), or install directly from github.  If you have DrRacket installed, you can install rash with `File -> Install Package`.
#### via raco:
`raco pkg install rash`

#### git version:
`git clone https://github.com/willghatch/racket-rash rash && cd rash/linea && raco pkg install && cd ../shell-pipeline && raco pkg install && cd ../rash && raco pkg install`

OR

use `raco pkg install --clone rash`


### Usage

Online documentation is [here](http://docs.racket-lang.org/rash@rash/index.html).  After installation, local documentation can be accessed with `raco docs rash`.

Here's a quick demo video of Rash in action:[
![asciicast](https://asciinema.org/a/mvBT1SNFDNqmKoOyMNnIPVk26.png)](https://asciinema.org/a/mvBT1SNFDNqmKoOyMNnIPVk26)

I published [a paper about Rash in GPCE 2018](http://willghatch.net/publications/rash-gpce-2018-preprint.pdf).

This repo also contains the [shell-pipeline](https://docs.racket-lang.org/shell-pipeline/index.html) and [linea](http://docs.racket-lang.org/linea/index.html) packages.  They mostly support Rash itself, so they live in the same repo.
