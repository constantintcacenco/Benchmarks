# Files Generator

This script generates a set of text files according to the cases described in "testcases.txt". 

Further purpose is to analyze and compare the Similarity Algorithms (LSH, TLSH, SDHASH).

## Parameters

Parameters are global variables declared at the begining of the script

## Run

```
python test_case_generator.py file_path_1 file_path_2
```
e.g: 
```
python test_case_generator.py files/swan.txt files/dubliners.txt
```
or
```
python test_case_generator.py files/dubliners.txt files/swan.txt 
```

This way testcases can be applied to both files (or n files).



(Python version 3.7.0)

## Performed tests

"files" directory contains 2 text files: swan.txt and dubliners.txt plus 44 generated file according to the cases below (22 for each file)

1. Exactly similar files
2. Few words cut from the beginning
3. Few lines cut from the beginning
4. Few words cut from the end
5. Few lines cut from the end
6. Few words cut from the middle
7. Few lines cut from the middle
8. Few words added to the beginning
9. Few lines added to the beginning
10. Few words added to the end
11. Few lines added to the end
12. Few words added to the middle
13. Few lines added to the middle
14. Swapping the beginning and the end ---- ?
15. Scrambling the paragraphs
16. Scrambling lines
17. Scrambling words
18. Scrambling similarly sized words/sections
19. Interleaving paragraphs with unrelated text (can be scrambling with another original text)
20. Interleaving sentences with unrelated text (can be scrambling with another original text)
21. Interleaving words with unrelated text (can be scrambling with another original text)
22. Adding sentences by percentage


