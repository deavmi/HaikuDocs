FuzzyTime
=======

>_FuzzyTime_ is a desktop applet displays the time and date not in the precise format you would expect from a computer, but in a deliberately 'fuzzy', human-friendly way

## Installation

FuzzyTime is available on the clasqm repos for x86_gcc2 and x86_64. For instructions on how to add one of these repos to your system, please see [here](http://clasquin-johnson.co.za/michel/haiku/repo/index.html). Once the repo is installed, you can install the program from the HaikuDepot app.

## Usage

Select Fuzzytime from the Deskbar, or in Terminal type 

    fuzzytime

The program window will appear.


![FuzzyTime](img/FuzzyTime0.png "FuzzyTime")


To MOVE FuzzyTime, left-click the 5-pixel yellow border. It mysteriously grows a standard yellow tab so you can move it anywhere on your screen. Left-click again to make the tab go away after you have moved the applet.

![FuzzyTime](img/FuzzyTime1.png "FuzzyTime")

To EXIT FuzzyTime, right-click that same border. FuzzyTime will remember its previous position every time you start it.

FuzzyTime bundles Chris Tsai's CLI utility fuzzy_time.py, obtained from SourceForge and slightly adapted

If you want FuzzyTime to appear on every boot, put a link to it in /boot/home/config/settings/boot/launch.
