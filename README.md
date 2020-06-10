# 2PHPD Final Project

This is the seed project of 2020 2PHPD course final exam. It is for you to standardize the submission of your works. Git must be used for giving version control of your job. 

***To ensure your work to be correctly evaluated, please READ CAREFULLY the following instruction.***

## Submission Instruction

### I. Initial Configuration With Git

*You **MUST STRICTLY FOLLOW** this part STEP by STEP, otherwise your project might be treated as invalid (0 points for the score)!*

1. Configure your local git setting before committing any new changes:
  - user.name: "FamilyName GivenName"
  
    user.email: "SupinfoID@supinfo.com"
  - Run `git config ` command to configure these info, here's an example:
  
    `git config user.name "GUO Jiyan"`
  
    `git config user.email "57191@supinfo.com"`
3. To reveal you development history, there must be **at least 3 "uncontinuous commits"** in your commit history **(!!!IMPORTANT!!!)**
  
  - By "uncontinuous commits" means your commit histroy CANNOT be like this:
  
    `commit 1(2020/05/18): add file1`
  
    `commit 2(2020/05/18): remove file1`
  
    `commit 3(2020/05/18): add file1 back`
  
  - It's recommended to commit everytime (or everyday) you complete a function or work; (In passing, Git helps you to save checkpoints of your work, just like save-files in games, you can "go back" to anytime you want);

### II. Directory Structure

`/`stands for the root of this seed project.

- `/code`: Put all of your code files in this directory (.php, .html, .js, .sql etc.). So this should be **the root directory of your code**;
- `/doc`: Put your document files under this directory, if there's any;
- `/doc/README.md`: You MUST give a instruction in this file, to instruct users to deploy your system on their machines successfuly.
  - *(Missing the instruction will **`-3 points`** from your final score.)*
  - *(This user could be anyone otherthan yourself. You may ask one of your friends to try deploying your code using your manual, see if they can make your system run on a new machine.)*
  - *(I put a template in that file, you may remove them all and create your own as you like.)*
- No anyother file should be put under this root directory; 

### III. Packing Your Work

- Package your work as a .zip file for submission;
- The submitted file should be named as `PHPD_SupinfoID1_SupinfoID2.zip` (the less id in the front);
- **DO KEEP** .git repository(directory) within your submitted package *(Missing .git repo will cause your project to be a **INVALID WORK**)*;
- If you are using `composer` to manange your dependency, **DO NOT KEEP** `vendor` directory in your package *(Just keep composer.json and .lock files will be OK. Having `vendor` directory packaged will **-1 points** from your score)*;

For any further questions, you are welcome to ask me anytime.

Bon courage! 

