# Researching the less command

## 1st Option: less -m
### Example 1:
Input:
```
[cs15lsp23ox@ieng6-203]:stringsearch-data:80$ less -m technical/biomed/1468-6708-3-7.txt
```
Output:
```
Background
        With the publication of the Antihypertensive and
        Lipid-Lowering Treatment to prevent Heart Attack Trial
        (ALLHAT), the role of peripheral alpha-1 antagonists in the
        treatment of hypertension has become controversial. The
        doxazosin arm of ALLHAT was stopped early, due to a
        doubling of the incidence of congestive heart failure in
        this group, as compared to the low-dose chlorthalidone arm
        [ 1 ] . Prior to this publication, there had been no
        obvious suggestion of a mechanism by which peripheral
        alpha-1 antagonists in general or doxazosin in particular
        would be inferior to chlorthalidone or would specifically
technical/biomed/1468-6708-3-7.txt 4%
```
The command outputs the % of the file shown instead of a simple colon at the end of the block. This is useful to see the extent of the length of the file content.
