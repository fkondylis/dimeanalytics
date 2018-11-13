# Software

This section lists step-by-step installation instructions for various software DIME Analytics recommends. Please let us know if any part of the instructions is not clear or does not work for you and we will improve the instructions, or if you would like to see any other software included.

## Stata & R

DIME has a Stata MP license for use on Bank and personal laptops. R is free, and we additionally have a powerful RStudio Server installation we can provide access to. Contact DIME Analytics for details.

## SurveyCTO

DIME Analytics administers the [World Bank's enterprise subscription with SurveyCTO](https://survey.wb.surveycto.com/). This installation is available to all Bank teams at a discount from the retail subscription and uses Bank single-sign-on when possible as well as allowing external email accounts. Please review the [World Bank SurveyCTO Documentation](https://showcase.dropbox.com/s/WBG-SurveyCTO-Documentation-HZN82ovmFR0hpnnsLYdns) and use eServices to request a server. To be added to the DIME Team for survey template sharing, please contact DIME Analytics.

## Git & GitHub

DIME projects are encouraged to use Git, a free [version control software](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004668), for writing data analysis code. They allow simultaneous editing and execution of code files and comparisons of hisotries and alternate versions. This enables maintaining and merging simultaneous ongoing workstreams without conflicts, unlike software like Dropbox. [Learn more here.](https://worldbank.github.io/dimeanalytics/git/)

## Atom

Atom is a powerful text editor that has easy integrations with Git/GitHub and Stata, as well as other languages and softwares like LaTeX. It is built by the same team that produces GitHub, and is free. You can set it up on a personal computer with administration privileges. We are currently working on setup instructions for World Bank computers.

1. First install Atom from https://atom.io/. Choose any theme you like!
1. In Atom, go to _Settings_ and then _Install_ and install the following two packages **language-stata** and **stata-exec**.
1. In _Settings_ / _Packages_, open **stata-exec** and read the instructions carefully.
    * _For Mac users_: Selecting the correct Stata version should be the only step. Ask for help if you don't understand something.
    * _For Windows users_: It is a bit more complicated. You need to follow [these](https://github.com/kylebarron/stata-exec#installation) instructions. Ask for help if you don't understand something.
1. Now open a Stata .do file in Atom and run it using the keyboard shortcuts in the **stata-exec** settings. The default keyboard shortcuts are slightly different than in the Stata dofile editor: `shift-cmd-d` (on Macs) and `shift-ctrl-d` (on PC) runs the whole file, and `cmd-alt-d` (on Macs) and `ctrl-alt-d` (on PC) runs only the selected code block. Let us know if you want to change these!

_Useful Atom Packages_

* [file-icons](https://atom.io/packages/file-icons): Adds icons to the project sidebar.
* [fonts](https://atom.io/packages/fonts): Supports beautiful programming fonts like [atom-firacode](https://atom.io/packages/firacode).
* [chary-tree-view](https://atom.io/packages/chary-tree-view): Stops Atom from trying to open .dta and .xlsx files.
* [indent-guide-improved](https://atom.io/packages/indent-guide-improved): Helps you understand the structure of your code and be a better coder.
* [minimap](https://atom.io/packages/minimap): Shows you a zoomed-out view of your code so you can navigate faster.
* [zebra-stripes](https://atom.io/packages/zebra-stripes): Makes alternating lines different colors in the editor (very good for coding).
* [language-latex](https://atom.io/packages/language-latex): Provides code highlighting for LaTeX.
* [latex](https://atom.io/packages/latex): Compile LaTeX documents with Atom. (Atom can replace TeXStudio also 😉)
* [hydrogen](https://atom.io/packages/hydrogen): See Stata results directly in your code. This is an advanced feature and we are happy to help you set this up.
* [teletype](https://atom.io/packages/teletype): Work on the same code file at the same time with any number of other people. This is _new_ software and can be a bit buggy but it can get you out of a pinch and is really cool.
