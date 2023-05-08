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

### Example 2:
Input:
```
[cs15lsp23ox@ieng6-203]:stringsearch-data:82$ less -m technical/plos/journal.pbio.0020013.txt
```
Output:
```
Inside eukaryotic cells there is a massive protein complex called the proteasome whose
        raison d'<C3><AA>tre is to remove unnecessary proteins by breaking them down into short peptides.
        The proteasome is thus responsible for an important aspect of cellular regulation because
        the timely and controlled proteolysis of key cellular factors regulates numerous biological
        processes such as cell cycle, differentiation, stress response, neuronal morphogenesis,
        cell surface receptor modulation, secretion, DNA repair, transcriptional regulation,
        long-term memory, circadian rhythms, immune response, and biogenesis of organelles
        (Glickman and Ciechanover 2002). With the multitude of substrates targeted and the myriad
        processes involved, it is not surprising that aberrations in the pathway are implicated in
        the pathogenesis of many diseases, including cancer.
        With so many proteins to target for degradation, the activity of the proteasome is
technical/plos/journal.pbio.0020013.txt 9%
```
The command outputs the % of the file shown instead of a simple colon at the end of the block. This is useful to see the extent of the length of the file content.

## 2nd Option: less -N
### Example 1:
Input:
```
[cs15lsp23ox@ieng6-203]:stringsearch-data:86$ less -N technical/government/Gen_Account_Office/June30-2000_gg00135r.txt
```
Output:
```
      1 
      2 
      3 
      4 
      5 Results in Brief
      6 All five of the regulatory agencies that we examined were using
      7 some form of IT to notify the public about opportunities to
      8 participate in rulemaking and to facilitate the receipt of public
      9 comments. All of these agencies had web sites that conveyed
     10 rulemaking information to the public and/or maintained some
     11 rulemaking records in electronic form, and all of them accepted
     12 electronic comments for at least some of their proposed rules.
     13 However, the specific features and uses of IT differed
     14 significantly between and sometimes within the agencies. For
     15 example, DOT had established an Internet web site that housed
     16 regulatory information for every agency within the department and
technical/government/Gen_Account_Office/June30-2000_gg00135r.txt
```
### Example 2:
Input: 
```
[cs15lsp23ox@ieng6-203]:stringsearch-data:87$ less -N technical/biomed/1471-2091-3-4.txt 
```
Output:
```
      1 
      2   
      3     
      4       
      5         Background
      6         The overuse of antibiotics in the clinic and for
      7         agricultural uses has resulted in a tremendous selective
      8         pressure for antibiotic resistant bacteria. These bacteria
      9         become resistant by a number of mechanisms, such as
     10         producing enzymes that hydrolyze or inactivate the
     11         antibiotics, producing efflux pumps that transport the
     12         antibiotic out of the cell, or modifying their cell wall
     13         components so they no longer bind effectively to the
     14         antibiotics [ 1 2 3 ] . The most common, least expensive,
     15         and effective antibiotics are the <CE><B2>-lactam containing
     16         antibiotics, such as the penicillins, cephalosporins, and
technical/biomed/1471-2091-3-4.txt
```
