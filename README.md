# Sublime-Text  
# Install Subl in terminal.  
1 ln -s "/Applications/Utilities/Sublime Text.app/Contents/SharedSupport/bin/subl" /usr/local/bin/subl  
"/usr/local/bin/subl" mean: /usr/local/bin/nameforsublyouwant.  
2 sudo ln -s "/Applications/Utilities/Sublime Text.app/Contents/SharedSupport/bin/subl" /usr/local/bin/subl  
   
![](https://scontent.fhan5-1.fna.fbcdn.net/v/t1.15752-9/34726545_1022007071295932_2129043536627105792_n.png?_nc_cat=0&oh=9480fff45d29b865895cf8eaca059689&oe=5B7E933C)   
  
#Usage
Run subl --help,

Usage: subl [arguments] [files]         edit the given files
   or: subl [arguments] [directories]   open the given directories
   or: subl [arguments] -               edit stdin

Arguments:
  --project <project>: Load the given project
  --command <command>: Run the given command
  -n or --new-window:  Open a new window
  -a or --add:         Add folders to the current window
  -w or --wait:        Wait for the files to be closed before returning
  -b or --background:  Don't activate the application
  -s or --stay:        Keep the application activated after closing the file
  -h or --help:        Show help (this message) and exit
  -v or --version:     Show version and exit

--wait is implied if reading from stdin. Use --stay to not switch back
to the terminal when a file is closed (only relevant if waiting for a file).

Filenames may be given a :line or :line:column suffix to open at a specific
location.
