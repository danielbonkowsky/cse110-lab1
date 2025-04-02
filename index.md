# Daniel Bonkowsky

<img src="daniel.png" alt="Me, my sister, and my dad" width="500"/>

# About Me

I'm a computer engineering major here at UCSD. I like **climbing**, _ultimate frisbee_, <ins>skiing</ins>, ***reading on my kindle*** and <sup>surfing</sup>. The latest book I read was Sapiens, by Yuval Noah Harai, and a quote I found really interesting was

> We moderns have an arsenal of tranquillisers and painkillers at our disposal, but our expectations of ease and pleasure, and our intolerance of inconvenience and discomfort, have increased to such an extent that we may well suffer from pain more than our ancestors ever did.

My favorite programming language is C. I like C because the programs you end up writing can be very elegant. Consider this program that concatenates two strings (which I stole from _The C Programming Language_ by Kernighan and Ritchie). 

```c
/* strcat: concatenate t to end of s; s must be big enough */
void strcat(char s[], char t[]) {
  int i, j;

  i = j = 0;
  while (s[i] != '\0') /* find end of s */
    i++;
  while ((s[i++] = t[j++]) != '\0') /* copy t */
    ;
}
```

The code golf people play ends up creating very cool code, such as the last while loop.

I also really like webcomics. My favorite webcomics are [xkcd](https://xkcd.com/) and [smbc](https://www.smbc-comics.com/).

Hey, if you're bored, here's a list of things you could do which would be cool:
- Look at my [README](README.md) file
- Go on a walk
- Go to the beach

Here's the order of how fun those things will be:
1. Go to the beach
2. Go on a walk
3. Look at my [README](README.md) file
