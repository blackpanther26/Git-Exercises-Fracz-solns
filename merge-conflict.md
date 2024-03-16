# merge-conflict
- git start next
- git merge another-piece-of-work
> git will give us merge conflicts when we try to merge the branches because both of them afre editing the same line , which is causing the conflicts , therefore we need to fix that manually now
- nano equation.txt
- ```  <<<<<<< HEAD
       2 + ? = 5
       =======
       ? + 3 = 5
       >>>>>>> another-piece-of-work 

- edit this manually by removing extra lines except :  ``` 2 + 3 = 5 ```
- git add .
- git commit -m "smth"
- git verify
