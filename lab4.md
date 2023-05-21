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



