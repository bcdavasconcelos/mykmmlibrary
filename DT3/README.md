# Wiki-links and aliases in DEVONthink 3

- [Selected word as alias](#selected-word-as-alias)
- [Filtered text from clipboard as alias](#filtered-text-from-clipboard-as-alias)
- [Filtered text from entry as alias](#filtered-text-from-entry-as-alias)

## Selected word as alias
If you have a word you want to add as alias of a specific entry, all you'll have to do is select it and run the macro.
The macro will extract existing aliases, add the new word to the string and paste them all back to the `alias` field.



## Filtered text from clipboard as alias  
To understand the use of this macro, read [How I use wiki-links and aliases](https://discourse.devontechnologies.com/t/how-i-use-wiki-links-and-aliases/47846).

**What I will do**
1. Make sure I have the correct `entry` selected in DT3.
2. Open a app called Myosotis (https://github.com/gebrkn/Myosotis), which provides me with the full declension of ancient greek words. 
3. Select the declension tables of the word I need to parse.
4. Execute the macro. 

**What the macro will do**
1. Copy the selected text to clipboard.
2. Filter greek words out of the text.
3. Get these words into a comma-separated string.
4. Add this string to the selected DT3 `entry`.

**What you should do**
1. Find a place where you can easily get the full parsing of the word.
2. Figure out a way to filter it using `regex`. (You might want to check out https://regex101.com)
3. Edit the RED section marked for customization.

**Note**
* To filter out text in latin script, you might want to try ` \b[A-Z][A-Z]+\b `
* This macro is already set to filter polytonic greek using `\b\p{Greek}+`



## Filtered text from entry as alias
To understand the use of this macro, read the second part of the previous text [How I use Wiki-Links and Aliases (pt.2)](https://discourse.devontechnologies.com/t/how-i-use-wiki-links-and-aliases-pt-2/47873).

**What the macro will do**
* Copy the text of the selected ` entry ` to the clipboard.
* Filter out words/expressions matching regex ` \d*[a|b]\d\d `
* Get these words into a comma-separated string.
* Add this string to the ` alias ` field of the selected DT3 `entry`.

