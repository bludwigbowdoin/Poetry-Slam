# Network Andre 


### Description of work:


### How to set up and run the code:

To run the code after cloning the repository, the mini.h5 file that contains 
the word embedding dataset (too large to push to GitHub) must be downloaded 
from this [page](https://github.com/commonsense/conceptnet-numberbatch) (the 
direct download link is [here](http://conceptnet.s3.amazonaws.com/precomputed-data/2016/numberbatch/19.08/mini.h5)).

Once mini.h5 is downloaded and in the directory, go to terminal and enter 
'streamlit run mainSL.py'. Depending on what packages and libraries you 
have installed, you might have to wait a while and/or enter the 
respective commands to download all libraries and packages. Large models are 
used for spaCy and GPT-2, so these might take a while to download. Just hold 
tight. Eventually, your default browser should open with a blank white 
Streamlit page with 'running' buffering in the top right. This will take up to 
a minute to load, and then an image and text options will appear. The buttons 
and entries are all pretty self-explanatory. For fullest functionality, turn 
on Developer Mode. If speaking mode is turned on, you will have to wait until 
the last output is spoken to try another round of Network Andre. 

Experimentation is paramount in this system. Each of the episodes presents its 
own vocabulary, and the last episode .txt groups all of them together. Further, 
the text_len directly impacts how long the outputs will be, while the 
generations number determines how many chances the systems gets to potentially 
generate better- or worse-scoring outputs. Above all, since the generations 
first come from a neural network, each round of Network Andre will 
produce entirely novel results, even with the EXACT SAME input selections. The 
tradeoff with this sort of novelty is that, yes, sometimes the results are not 
much better than gibberish or reveal some edge case behaviors of GPT-2, but on
the other hand, there can be some pretty cool results! See existing output 
folder for some arbitrarily created examples. 

### How working on this system challenged me as a computer scientist:



### Three scholarly papers in computer science that inspired your approach, and how:

  You can research scholarly papers to include by using Google Scholar Links to an external site..



