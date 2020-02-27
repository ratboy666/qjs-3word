qjs-3word
=========

## What is it? ##
**qjs-3word** encodes and decodes 32 bit numbers to 3 words from a
2048 word dictionary. Javascript, tested with quickjs
<https://bellard.org/quickjs/>.

Quickly hacked together after reading a comment on HN (hacker news).

```
$ 3word -r
encoding 2422510259
else myself filter

$ 3word -d else myself filter
2422510259

$ 3word -h
/home/fred/bin/3word Encode or decode 32 bits to 3 dictionary words
-r                  encode random 32 bit number
-d word word word   decode words to number
-e n                encode n to 3 words
May be useful for passwords (32 bits entropy every three words,
and the attacker typically doesn't have the dictionary). Also, for
encoding 32 bit facts verbally
```

