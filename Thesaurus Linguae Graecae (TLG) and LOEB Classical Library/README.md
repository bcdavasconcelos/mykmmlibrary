# Corpora - A Keyboard Maestro Macro for ultra-fast access to the Thesaurus Linguae Graecae and the LOEB Classical Library 

For a demonstration of how the macro works, see this [video](https://youtu.be/90hw0ER2bBQ).

## What's new?
### 2019-08-14 

* A brand new macro was created and a lot of work was put into this. Both macros (TLG Macro and LOEB Macro) are now united and working perfectly in alfred-style.

<p align="center">  
<img src="https://github.com/bcdavasconcelos/mykmmlibrary/blob/master/Screenshots/corpora.png" alt="Prompt for Author or Work" width="70%" height="70%">
 </p>  

* Dependencies on third party plug-ins were eliminated!

* DT3: Author and work names, TLG code and tags are set automatically via Applescript. This relies on a new Keyboard Maestro 9.0 feature for JSON dictionaries.


## How to use it

* Follow the instructions on the macro on how to set it up properly.

* Then, trigger the macro with the choosen shortcut.

* You'll see a prompt for authors and works containning both TLG and LOEB Classical Library volumes. Enter search term, then using the arrows, select one and press return.

* Choose whether you want this link to open TLG/LOEB online or Diogenes/LOEB Offline (if you happen to have the files).

* Choosse whether you want to open this link on the default browser or store it on DEVONthink 3.
  * If you choose DEVONthink 3, part of the relevant metadata (such as Author name, Work, TLG Code/LOEB Volume and tags will be set automatically via Applescript.
    
* You'll be taken directly to the text.


> The macro use data collected by @fractaledmind ([Stephen Margheim](https://github.com/fractaledmind/Classical-Studies-Resources)) in JSON format, with modifications.
