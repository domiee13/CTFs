**Cryptography**
*Link: https://ctflearn.com/challenge/192*

Problem
~~~
Base 2 2 the 6                      20 points Easy
There are so many different ways of encoding and decoding information nowadays... One of them will work! Q1RGe0ZsYWdneVdhZ2d5UmFnZ3l9
~~~
I use [Cipher Detect](https://www.boxentriq.com/code-breaking/cipher-identifier) and have result that's base64 encoded string\
So, I decode it and have a flag xD\
`
echo Q1RGe0ZsYWdneVdhZ2d5UmFnZ3l9 | base64 --decode
`
`Flag: CTF{FlaggyWaggyRaggy}
`