
## Overview

This data was collected by students for a sentiment analysis project in my intro to text mining course, during the 2018-2019 academic year. Each student group was asked to collect social media comments about a Tunisian "celebrity" of their choice, which could be a person, brand, sports team, political party, etc. The names of the files indicate the name of the chosen celebrity.

## Remarks about text formatting issues

- The files are quite heterogeneous in how they are formatted, unfortunately! The .csv files are mostly well-structured 
with the first line containing self-explanatory column names, and with one line per comment (including the content of the comment and metadata). Most of the .txt files contain only the text of the comment (one per line usually), with no metadata about the comment.

- In some files, comments might span multiple lines and are surrounded with quotes, e.g. Samia Abbou_Comments.txt, Orange_comments.csv

- Some files might not be read correctly due to special arabic encoding:  Manal Amara files, ShemsFM_comments.csv, Salah_Mejri

- Some files are not read correctly because they contain Arabic text written left-2-right rather than the reverse: Aicha Atia files

- The "" in the Ouled Moufida_positive_twitter file may be problematic ...

