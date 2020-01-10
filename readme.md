#### this is for learning Git And Backup config some stuff
- .zsh
- .p10k


### visual studio code extension and other stuff
- atom one dark theme
- tabnine
- bracket colorize
- change font to Fira Code
- change terminal font to mesloLGS NF so it'll work with zsh
- command + shift + p then search shell, install so it'll work in terminal to use code
- todo

### ssh to gihub
- https://www.youtube.com/watch?v=H5qNpRGB7Qw&list=PLwAKR305CRO-fenwcN2-IC0rgaB6vaJgD&index=7
- ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
- eval "$(ssh-agent -s)"
- ssh-add ~/.ssh/id_rsa
- pbcopy < ~/.ssh/id_rsa.pub
- 

### setting up git
- git config --global user.name 
- git config --global user.email
- git init, to start tracking files
- git status, to see which staging area
- git add filenames / git add . for adding all files
- git commit -m "message here, explain what changes"
- git ignore, touch .gitignore write files you want to ignore
- 

### plugin zsh osx
Command	                              Description
- tab	            =>                  Open the current directory in a new tab
- split_tab	      =>                  Split the current terminal tab horizontally
- vsplit_tab	    =>                  Split the current terminal tab vertically
- ofd	            =>                  Open the current directory in a Finder window
- pfd	            =>                  Return the path of the frontmost Finder window
- pfs	            =>                  Return the current Finder selection
- cdf	            =>                  cd to the current Finder directory
- pushdf	        =>                  pushd to the current Finder directory
- quick-look	    =>                  Quick-Look a specified file
- man-preview	    =>                  Open a specified man page in Preview app
- showfiles	      =>                  Show hidden files
- hidefiles	      =>                  Hide the hidden files
- itunes	        =>                  DEPRECATED. Use music from macOS Catalina on
- music	          =>                  Control Apple Music. Use music -h for usage details
- spotify	        =>                  Control Spotify and search by artist, album, track…
- rmdsstore	      =>                  cRemove .DS_Store files recursively in a directory