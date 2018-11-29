
# Chatbot Built Using Pytorch

## Getting Started
------------
To start, Download the data ZIP file 
`here <https://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html>`
and put in a ``data/`` directory under the current directory.

## Create the a directory name it data
```
mkdir data
wget http://www.cs.cornell.edu/~cristian/data/cornell_movie_dialogs_corpus.zip
unzip cornell_movie_dialogs_corpus.zip
cd ..
```
#### run python file using ipython kernel 
``` %run chatbot.py ```

###Sample Chat
```
   > hello?
   bot: hello .
   > where am I?
   bot: you re in a hospital .
   > who are you?
   bot: i m a lawyer .
   > how are you doing?
   bot: i m fine .
   > are you my friend?
   bot: no .
   > you're under arrest
   bot: i m trying to help you !
   > i'm just kidding
   bot: i m sorry .
   > where are you from?
   bot: san francisco .
   > it's time for me to leave
   bot: i know .
   > goodbye
   bot: goodbye .
```
## **Acknowledgements**

 1) Yuan-Kuei Wu’s pytorch-chatbot implementation:
    https://github.com/ywk991112/pytorch-chatbot

 2) Sean Robertson’s practical-pytorch seq2seq-translation example:
    https://github.com/spro/practical-pytorch/tree/master/seq2seq-translation

 3) FloydHub’s Cornell Movie Corpus preprocessing code:
    https://github.com/floydhub/textutil-preprocess-cornell-movie-corpus
