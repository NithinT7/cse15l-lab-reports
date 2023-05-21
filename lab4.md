# Lab Report 4
---
## Logging into Ieng6:
![Image][Screenshot 2023-05-21 at 2.08.21 PM.png]

Keys pressed: ```<ssh><space><cs15lsp23ox@ieng6.ucsd.edu><enter><Password><enter>```

The commands ran incude ssh which enables connection to the server and from there I entered my username and password to access the ineg6 server.

---
## Cloning fork from Github Account:
![Image][Screenshot 2023-05-21 at 2.31.45 PM.png]

Keys pressed: ```<git><space><clone><space><ctrl+v><enter>```

The command ran is git clone which clones the git repo into the local files and ctrl+v pasted over the url for the repo which was https://github.com/NithinT7/lab7.git. 

---
## Demonstrating the tests fail
![Image][Screenshot 2023-05-21 at 2.36.39 PM.png]

Keys pressed:```<ls><cd><space><lab7><javac><space><ListExamples.java><enter><javac><space><ctrl+v><enter><java><space><ctrl+v><space><ListExamplesTest><enter>```

There were multiple commands run. The ls command was to find directories within our active directory then we knew which directory to cd (change directory) into from their I compiled ListExamples.java using javac and compiled junit using javac and ctrl+v which pasted the command (-cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java) which is the command to compile junit. After I ran the tests on ListExamplesTests with the command I pasted over (-cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore).

---
## Edit the code to fix the test
![Image][Screenshot 2023-05-21 at 3.00.49 PM.png]

Keys pressed: ```<vim><space><ListExamples.java><?index1><5l><x><i><2><esc><:wq>```

The command vim allows you to edit files contents in the terminal which I used on ListExamples.java to fix its code. The problem with the code is that the last instance of index1 is supposed to be index2. To fix that I went to the last instance of index1 with ?index1 and then 5l goes to the right 5 spaces which is where 1 is, then I delete the 1 using x and replace it with i (insert mode) 2. To save the changes I hit escape and :wq.


