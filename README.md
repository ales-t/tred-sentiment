# tred-sentiment

Sentiment annotation extension for TrEd


## Installation

1. Install [TrEd](http://ufal.mff.cuni.cz/tred/).
2. Install nondeprel\_common extension: Run tred -> Setup -> Manage extensions -> Get New Extensions. Then select tne nondeprel\_common extension and click Install Selected).
3. Install this extension manually: clone this repository into ~/.tred.d/extensions/sentiment, then edit ~/.tred.d/extensions/extensions.lst file and add a line "sentiment" to it.

## Usage

Open a file with tectogrammatical annotation (.t.gz file). Select PML\_T\_Sentiment mode. Click Macros -> Current Mode -> Init sentiment attributes. If you are asked if you want to save the file, click Yes. Doubleclick a node and you will see that there are sentiment related attributes: sentiment\_eval, sentiment\_source.rf sentiment\_target.rf.

To annotate, select a node representing an assessing word and "remember it" pressing space. Then select a source of assessment and press s, then select a target of assessment and press t. Finally assing the sentiment\_eval attribute value POSITIVE or NEGATIVE.
