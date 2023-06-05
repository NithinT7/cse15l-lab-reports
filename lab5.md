# Debugging
---
## Original Post of the Bug:
![Image](Screenshot 2023-06-03 at 3.24.28 PM.png)
---
## TA Response

Hey is your class actually called ArrayTests.java? If it is not (most likely not) drop the .java when running the second command because the second command looks for the class to compile which is most likely ArrayTests. The error is stating that it can't find the class which means it can't find what class to run the tests on since you provided ArrayTests.java instead of ArrayTests.

---

## Student trying to fix the bug

Fixing the bug:
![Image](Screenshot 2023-06-05 at 12.16.07 PM.png)

The bug was was the TA said in that the .java should be dropped when running the second command as ArrayTests.java is not a class. I made a bashscript streamlining the commands and also fixing the bug.

---
## Bug Report

The file needed was the ArrayTests.java file, which was implied to be in the same directory as the file it was testing. The contents of the file are the same before fixing the bug. The command line I did to trigger the bug is in the first image. To fix the bug .java was dropped from the second command so it could find the class.

---
## Reflection 
Something cool I learned over the second half of the quarter was Vim. I didn't know you could meticulously edit files in the terminal and Vim helps out in doing that. I could see it being very useful in the future for quick edits and maybe even longer edits.  

