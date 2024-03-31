# Exercise-3
Exercise 3 Chinese name generating model trained with pinyin and percent encoding

Packages needed for “Percent encoding” code to work are: torch, torch.nn.functional, matplotlib.pyplot (for making figures), urllib.parse (hanzi to percent encoding), zhconv (percent encoding to hanzi) and tqdm (for showing progress).

Packages needed for “Pinyin” code to work are: re, torch, torch.nn.functional, matplotlib.pyplot (for making figures), xpinyin (hanzi to pinyin), Pinyin2Hanzi (pinyin to hanzi) and tqdm (for showing progress).

Sentence "%matplotlib inline" can be used to show figures in notebook, then "plt.show" will not be needed. But this will not work in Pycharm.

Chinese name data sourse: https://github.com/wainshine/Chinese-Names-Corpus/tree/master (100 000 names are used in training).
