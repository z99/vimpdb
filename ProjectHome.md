  * **Tired of debugging Python using print statements?**

  * **Don't like the cumbersome PDB (Python debugger) console?**

  * **Prefer using Vim for coding your Python programs?**


**VimPdb** is the solution - allows debugging Python in an IDE-fashion, right within the Vim editor.



### Features: ###
  * **Highlighting** of currently debugged line and breakpoint lines.
  * **F5** - Run/continue running.
  * **F2** - Toggle breakpoint at current line
  * **Ctrl-F2 / Shift-F2** - Toggle conditional/temporary breakpoint.
  * **F7 / F8** - Step into/over
  * **F12** - Print stack trace
  * **F3 / Ctrl-F3** - Eval/Exec a given statement (in the current debugging context)
  * **Save/load breakpoints** into session files.
  * **Cross-platform**
  * And many more... See readme.txt for details


![http://vimpdb.googlecode.com/files/screenshot.png](http://vimpdb.googlecode.com/files/screenshot.png)


### Download and Install ###

Click [here](http://vimpdb.googlecode.com/files/VimPdb.tar) to download the sources.
Just drop _vimpdb.py_ and _vimpdb.vim_ into your Vim plugin directory, and you're all set to go.




### Important Notes ###
  * It's still considered Beta, so I'm not too sure about its stability or lack of bugs. However, I do appreciate if you could report bugs, suggest features or help out with the known issues (see "Known Issues" section in readme.txt). Email me at [budowski@gmail.com](mailto:budowski@gmail.com)
  * It's possible to **easily implement the debugging capabilities for another editor (e.g. Emacs)** - you could write a Python class of your own, which inherits from the PdbIDE class, and implements editor-specific functionalities (such as highlighting).