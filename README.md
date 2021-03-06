# Suits Overused Phrases

<img src="images/suits.png" width="40%" />

## Motivation
Whoever has watched enough of the TV show [Suits](https://www.imdb.com/title/tt1632701/) knows that there are specific phrases repeated over and over in many episodes. 
Not only that but these phrases are used by many characters, as if they all have the same way of talking.

Feeling the urge to quantify this observation, this notebook downloads, parses and analyses all the subtitles 
from all 134 episodes (9 seasons) of Suits. It uses n-grams to assist finding common phrases and regular expressions to match them and similar ones in the subtitles corpus.

![](visualization.png)

Reddit [post](https://www.reddit.com/r/dataisbeautiful/comments/iwen9x/oc_what_did_you_just_say_to_me_and_other_overused/?utm_source=share&utm_medium=web2x&context=3)

## Tools
- [requests](https://requests.readthedocs.io/en/master/) and [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) to fetch and 
parse episode transcripts from online source
- Python's [re](https://docs.python.org/3/library/re.html) for Regular Expressions to match similar phrases
- [nltk](https://www.nltk.org/) for most common n-grams detection
- [matplotlib](https://matplotlib.org/) and PowerPoint for final visualization
