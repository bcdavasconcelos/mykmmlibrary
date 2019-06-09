Table of Contents
=================

* [Pandoc and MMD Conversion with prompt for Parameters](#Pandoc-and-MMD-Conversion-with-prompt-for-Parameters)
  * [Pandoc DT3 For use in DEVONthink 3](#Pandoc-DT3-For-use-in-DEVONthink-3)
  * [Pandoc Macro with selected files on Finder](#Pandoc-Macro-for-selected-files-on-Finder)
  * [Multimarkdown Converter on Finder](#Multimarkdown-Converter-on-Finder)

# Pandoc and MMD Conversion (with prompt for Parameters)

Both macros have several dependencies, such as PANDOC, LATEX and Multimarkdown. 
If you don’t have them installed, it won’t work.

To do:  
Add other inputs and outputs  
Add bibliography support  
Add template options  
If you would like to contribute, please join the discussion at https://tinyurl.com/y2xv2lc5

## Pandoc DT3 For use in DEVONthink 3

* Select entry and trigger the macro. 
* You'll see this prompt:   

<p align="center">  
<img src="https://github.com/bcdavasconcelos/mykmmlibrary/blob/master/Screenshots/PandocDT3-1.png" alt="Prompt for Author or Work" width="70%" height="70%">  
 </p>  

* Currently, you can only choose input and output for most formats. Only the PDF conversion allows some customization of the variables:  

<p align="center">  
<img src="https://github.com/bcdavasconcelos/mykmmlibrary/blob/master/Screenshots/PandocDT3-2.png" alt="Prompt for Author or Work" width="70%" height="70%">  
</p>   

* It would be nice to add bibliography and templates support at some point.
 
* After conversion, the resulting file will be imported into DT3.

**PLEASE NOTE: For this macro to work, YOU MUST correct the path for the temporary conversion file:**  

<p align="center">  
<img src="https://github.com/bcdavasconcelos/mykmmlibrary/blob/master/Screenshots/PandocDT3-3.png" alt="Prompt for Author or Work" width="70%" height="70%">
 </p>  


## Pandoc Macro for selected files on Finder

This is essently the same as the last one, but it does not rely on AppleScript and will work directly on Finder.   
So, when you are on finder: select a file and run the macro:
  
<p align="center">  
<img src="https://github.com/bcdavasconcelos/mykmmlibrary/blob/master/Screenshots/Pandoc1.png" alt="Prompt for Author or Work" class="center" width="70%" height="70%">
</p>  

***

Likewise, this macro does essentially the same thing, but it uses the MMD engine for converting.  

## Multimarkdown Converter on Finder
<p align="center">  
<img src="https://github.com/bcdavasconcelos/mykmmlibrary/blob/master/Screenshots/MMD1.png" alt="Prompt for Author or Work" width="70%" height="70%">
</p>  


If you have any suggestions for improvement, they are more thane welcome.
