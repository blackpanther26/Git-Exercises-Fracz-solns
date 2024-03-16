# ignore-them
- git start next
- touch .gitignore
> '.gitignore' a plain text file placed in the root directory of your Git repository that specifies files and patterns Git should ignore when tracking changes and committing them.
- nano .gitignore
> - *.exe
> - to ignore all files with a .exe extension, we use the pattern *.exe
> - *.o
> - *.jar
> - libraries/
- git add .
- git commit -m "Add .gitignore file with ignore rules"
- git verify
