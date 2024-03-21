
I learnt the following codes while studying Python for data analysts. 

*All of the files,except datasources, are in jupyternotebook format to allow for display of both input and output.*

## User guide
For the really long files, make use of the table of contents under the View tab of your jupyter notebook.

## Quick Shortcuts 
* To switch between markdown and code you press the esc key+ m to switch to markdown then esc+y to switch to code and esc+r to switch to raw.
* Ctrl+ x is a shortcut to clear a cell. This is because it cuts  everything written.
* Just like here on  a Github .md file , Python's md file has many similar syntax , i.e to add a pointer use an asterix  and space before the sentence.
* Unlike a Github .md file where to add code to a markdown file you press Tab, in a jupyter notebook markdown, you press the right arrow key(>) before the code.
* To comment multiple lines of code, highlight the codes and place Ctrl+/
* To underline a text in a markdown pane use {u in between the left arrow key and right arrown key u} just before the text. <<u>>. Similarly, to bold and italize a text use b and i respectively in side the left and right arrow key. To bold and italize a text, the use the arrow keys method above but enclose the entire text from both sides with double asterixes.
* To paint over a text in markdown enclose inside grace accents `` i.e if i write fname inside that sign we get  `fname`

## Common Mistakes
* While pressing Alt+Enter or Shift+Enter is an easy way to go to the cell below and automatically have it be in edit mode. This can cause an error message to pop if the above code was a code that did a non-reversable operation such as dropping or adding an element in your variable.
This is because the above command re-run that cell's code before creating the active empty cell below. Thus, it is less riskier to add a new cell by pressing the down arrow key and pressing Enter, using your mouse or pressing ESC+b then Enter. Another common programmer practice is at the beginning, add many cells then just press the down arrow key/click/press Enter the next cell.
However, press Shift/Alt + Enter when you have typed out your code and you are read to run it **just once** and go to the next cell.
* Leading zeros aren't allowed, writing 001 as 1 might return an error.

## Additional useful syntax
* To delete an object use the del keyword e.g del(x)

 
 ### Key words in Python
 Keywords are reserved words that have a special purpose.

You can see a list of reserved words by typing help('keywords').

You are unable to use keywords as variable names in python

Similarly object class names such as str, list, dict, tuple and set should not be used as variable names either.

For example you should not use list as a variable name e.g. list = [1,2,3,4].

This is because "list" is used to identify a class object. So instead you could assign the previous list to a variable called list_1 = [1,2,3,4]



