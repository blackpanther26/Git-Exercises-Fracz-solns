# fix-old-typo
- git start next
- git log
> <img width="805" alt="Screenshot 2024-03-18 at 2 56 18 PM" src="https://github.com/blackpanther26/Git-Exercises-Fracz-solns/assets/148771840/e0bccd4e-a00d-4221-8c86-44b96b4913d0">
- git rebase -i 98e6b86bbed506a2225aec8f1bc9791b88e5ba8f
> <img width="535" alt="Screenshot 2024-03-18 at 2 59 53 PM" src="https://github.com/blackpanther26/Git-Exercises-Fracz-solns/assets/148771840/c273f064-d541-4524-9b68-684fb8913b86">
> <img width="508" alt="Screenshot 2024-03-18 at 3 00 30 PM" src="https://github.com/blackpanther26/Git-Exercises-Fracz-solns/assets/148771840/e649c18e-086f-4c51-b183-fffeddd2ecf1">
> - mark the first commit with "edit" command , fix the typo in the file 
> - initiates an interactive rebase session starting from the commit specified by the hash 98e6b86bbed506a2225aec8f1bc9791b88e5ba8f. Interactive rebasing allows us to modify the commit history in various ways, such as reordering, editing, squashing, or dropping commits. 
- nano file.txt
> - <img width="158" alt="Screenshot 2024-03-18 at 3 01 24 PM" src="https://github.com/blackpanther26/Git-Exercises-Fracz-solns/assets/148771840/7e39b49b-3384-434e-9f20-6b5660d1a10c">
> - <img width="162" alt="Screenshot 2024-03-18 at 3 01 52 PM" src="https://github.com/blackpanther26/Git-Exercises-Fracz-solns/assets/148771840/f6d9efd5-e720-43c8-b109-37ede30bbab9">
- git add .
- git rebase --continue
> - <img width="877" alt="Screenshot 2024-03-18 at 3 05 56 PM" src="https://github.com/blackpanther26/Git-Exercises-Fracz-solns/assets/148771840/39667c65-c192-4e50-9e6c-a86776efdfa8">
> - <img width="237" alt="Screenshot 2024-03-18 at 3 06 38 PM" src="https://github.com/blackpanther26/Git-Exercises-Fracz-solns/assets/148771840/415fd9f7-7d29-478f-85c7-dcf43aa8b03c">
> - This command tells Git to apply the changes we've resolved or made and continue applying the remaining commits in the rebase sequence.
> - <img width="880" alt="Screenshot 2024-03-18 at 3 07 47 PM" src="https://github.com/blackpanther26/Git-Exercises-Fracz-solns/assets/148771840/fc1bb464-64d8-4d8b-a07f-7031f24aba6c">
> - fix the typo in the commit message
- ls
- nano file.txt
> - <img width="598" alt="Screenshot 2024-03-18 at 3 11 12 PM" src="https://github.com/blackpanther26/Git-Exercises-Fracz-solns/assets/148771840/c60576f8-60f6-4100-bf47-193bb7eb509a">
> - <img width="418" alt="Screenshot 2024-03-18 at 3 11 46 PM" src="https://github.com/blackpanther26/Git-Exercises-Fracz-solns/assets/148771840/69036fd4-b8aa-4af1-bf87-fdf3e9ef2faa">
- git rebase --continue
- git commit -am "smth"
- git verify
