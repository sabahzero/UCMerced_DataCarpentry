### [Nov 1-2, 2018 UC Merced Workshop Schedule](https://noracmitchell.github.io/2018-11-01-ucmerced/), by Dr. Nora C Mitchell


Etherpad
https://pad.carpentries.org/_2018-11-01-ucmerced

### [Unix](http://man7.org/linux/man-pages/man1/ls.1.html) 

https://www.shell-tools.net/index.php?op=regexp
https://regex101.com/r/yE3tO8/1 
<br /> Best practices: avoid spaces and underscores in file folder names <br /> Text editors handle text. <br /> nano is a text editor. <br />In nano, the ^ symbol means to press Control key. <br /> Microsoft Word is not a text editor, it's a word processor.<br /> Reuse a previously entered command by pressing the "up arrow"<br /> Pressing tab helps fill in the rest of your file name in a command <br /> Once space is the same as multiple spaces <br /> No space vs one space results in different outcomes <br /> <br />pwd   = present working directory <br /> cd    = change directory <br />cd .. = moves you up in directory <br />cd -  = takes you back to your previous working directory <br />ls    = shows what's in your directory <br />mkdir = makes a new directory <br />rm    = removes a file in your directory (cannot recover)<br />rm -r = remove folder <br />mv    = moves a file, changes its name (overwrites file) <br />cp    = copies a file <br />cp -r = copies a directory <br />wc    = gives you the line, word, and character count of a file <br />wc -c = character count<br />wc -l = line count<br />wc -w = word count <br /><br />To make a new file, type:           > myfile.txt   <br />To open that file with nano, type:  nano myfile.txt <br />Close the file by pressing:         CTRL + X
  <br />cat draft.txt will show you the text in draft.txt
  <br />nano /draft.txt will open a new draft in nano named draft.txt 
  <br />echo hello > testfile01.txt will write hello into testfile01.txt 
  <br />echo hello >> testfile02.txt will append hello into testfile02.txt
  <br />head -3 animals.txt will return the top three lines of animals.txt
  <br />tail -2 animals.txt will return the bottom two lines of animals.txt


### [R](https://tinyurl.com/ycvyop3r)      
http://swcarpentry.github.io/r-novice-gapminder/
<br />Data management       http://openrefine.org/
  <br />project management  https://tinyurl.com/y77tbloo 
  <br />jupyter             https://tinyurl.com/ybx6mbjm
  <br />tidyverse           https://www.tidyverse.org/
                      http://hackmd.io/ 
  <br />r-bloggers          https://tinyurl.com/ybfb9rqo 
<br /><br />Data vizualization    https://www.r-graph-gallery.com/
  <br />ggplot2             https://tinyurl.com/ya4lxpfg 
  <br />colorbrewer         https://tinyurl.com/ycklsjkf 
<br /><br />Code troubleshotting  https://stackoverflow.com/ 
                      <br />https://www.r-bloggers.com/
                      
  Reading or writing format .csv, .txt
  <br />Seeing code for function  print(function_name)
   <br />                         print(summary)
  <br />Packages    Type function_name without brackets for function's code
    <br />          http://masterr.org/r/how-to-view-source-code-in-r/
    <br />versions  https://tinyurl.com/ya25e85b       
  <br />methods() View different methods
  <br />Using R for large datasets and cluster vs RStudio for quick viz
  <br />Lists   One-dimensional arrays of data containing multiple data types
  <br />Vectors One-dimensional arrays of data with single data type
  <br />Dataframe usually has rows that are lists and columns are vectors
    <br />Rows are usually samples of a sort
    <br />Columns are usually the observations


### [Git](https://noracmitchell.github.io/git-novice.html )   
git init                  initiates a new repository
<br />git add <filename>        stages that file / those files
<br />git commit -m "message"   commits the staged files to the repository
<br />git diff                  looks at diffs versions 
<br />git log                   shows the commits
<br />git log --oneline         shows commits using one line
<br />git reset HEAD <filename> unstages the file
<br />git status                status of the repository
<br />git checkout              restore past state
