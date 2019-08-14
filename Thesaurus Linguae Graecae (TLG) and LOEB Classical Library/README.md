# TLG & Loeb Macros

## 2019-08-13
A brand new macro was created and a lot of work was put into this.

* Both macros are now united and working perfectly in alfred-style. 

* Dependencies on third party plug-ins were eliminated!

* DT3: Author and work names, TLG code and tags are set automatically via Applescript. This relies on a new Keyboard Maestro 9.0 feature for JSON dictionaries.


## 2019-06-09
Both macros use data collected by @fractaledmind ([Stephen Margheim](https://github.com/fractaledmind/Classical-Studies-Resources)) in JSON format, with modifications, to populate the awesome *Spotlight Search Prompt* Macro by @dagware ([Dan Thomas](https://github.com/dagware/DanThomas/blob/master/Keyboard%20Maestro%20Macros%2C%20Plugins%20and%20Videos.md)). The result is a practical shortcut to lookup any ancient author on [TLG Online](http://www.tlg.uci.edu) and on the [LOEB Classical Library](https://www.loebclassics.com). 

The TLG Macro also relied on Regex Macros shared on the Keyboard Maestro Forum by [JMichaelTX](https://forum.keyboardmaestro.com/u/jmichaeltx/summary).

### Dependencies
* You must have [Spotlight Search Prompt installed](https://forum.keyboardmaestro.com/t/macro-spotlight-search-prompt/4665).
* [Keyboard Maestro](https://www.keyboardmaestro.com)

### Screenshots

* First, trigger the macro with the choosen shortcut.

* You'll see a prompt for authors and works. Enter search term, then using the arrows, select one and press return.
<img src="https://github.com/bcdavasconcelos/mykmmlibrary/blob/master/Screenshots/TLG2.png" alt="Prompt for Author or Work" width="70%" height="70%">

  
  
* You'll be taken directly to the text on TLG Online.
<img src="https://github.com/bcdavasconcelos/mykmmlibrary/blob/master/Screenshots/TLG3.png" alt="Prompt for Author or Work" width="70%" height="70%">
