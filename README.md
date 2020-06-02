# nyxgeek-wordlists
wordlists for password cracking


### nyxgeek-2008-wikipedia-titles_lower.txt

List of titles from Wikipedia, lowercased, spaces and punctuation removed

Usage: Run with HEAVY rules. use multiple rules at once, and also try with and without -jc option. Obviously what rule combinations you can use will be influenced by your GPU power. I try to limit my sessions to 2 hours or under, unless I'm getting good consistent results.

Example rule combos:
* --rules=rules/best64.rule --rules=rules/dive.rule
* --rules=rules/best64.rule --rules=rules/dive.rule -jc
* --rules=rules/rockyou-30000.rule --rules=rules/best64.rule
* --rules=rules/rockyou-30000.rule --rules=rules/best64.rule -jc
* --rules=rules/InsidePro-HashManager.rule --rules=rules/InsidePro-PasswordsPro.rule
* --rules=rules/InsidePro-HashManager.rule --rules=rules/InsidePro-PasswordsPro.rule -jc


Source: https://dumps.wikimedia.org/other/static_html_dumps/2008-03/en/




### nyxgeek-unicode-globallist.txt

Unicode wordlist compiled from variety of dictionaries and top 1000 word lists. I made this years ago and I cannot honestly remember all of the sources that were used for these words. Lots of dictionaries. This list was made for use with John the Ripper originally. For it to perform correctly, use the flag ```--internal-encoding=UTF-8```
