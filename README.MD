Partial C# port of nltk's [Twitter-aware casual tokenizer](https://github.com/nltk/nltk/blob/develop/nltk/tokenize/casual.py).

Use:
```
TwitterAwareTokenizer tokenizer = new TwitterAwareTokenizer();

string[] tokens = tokenizer.tokenize("This is a cooool #dummysmiley: :-) :-P <3 and some arrows < > -> <--");
```

Result:
```
 ['This', 'is', 'a', 'coool', '#dummysmiley', ':', ':-)', ':-P', '<3', 'and', 'some', 'arrows', '<', '>', '->', '<--']
```
