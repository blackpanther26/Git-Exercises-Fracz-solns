# merge-conflict
- git start next
- git merge another-piece-of-work
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
