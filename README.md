# Debugging Olympics 2


## Setup

1. Create folder for this Olympics assignment and cd into it

2. Perform the following commands in the command line
```bash
git clone https://github.com/omarakamal/olympics-2.git .
rm -rf .git
rm README.md
```

3. Create a .env file with the following values:
```
MONGODB_URI=your-connection-string
```


4. run:
```bash
npm i
```

5. run:
```bash
node seed.js
```






## Introduction

This exercise will test your understanding of the things we learned so far in unit 2. Fix the bugs as fast as you can. On some of the tasks there won't be an error message but the game won't function correctly.


## Acceptance Criterea
This is a website with almost full CRUD. This website has create, read, and delete for the resource provided. Once you have cloned the repo correctly its time to run the app and fix all the errors you notice. Go through the app like a normal user and see if things work correctly




## Scoring

Each bug is worth 3 points. In total there are 14 bugs in this code.

### Bonuses
- Bonus: Commits for each task done. For each meaningful commit for an error you will get .25 points. meaning after each task is done you commit that change with a <b>clear commit message</b>.