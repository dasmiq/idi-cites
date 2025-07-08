# IDI Cites

Citations of CTS editions in IDI books.

## cites.csv

Fields are:
* `work`: CTS work
* `book`: book ID
* `hits`: number of alignments citing this work
* `words`: whitespace-seperated wordcount of the longest version of the work
* `rate`: `hits` / `words`

## overlap.csv

Fields are:
* `id`
* `book`
* `tlen`: total length of the CTS text
* `nlocs`: number of citable chunks in the CTS text
* `cover`: size of the set intersection between CTS text and the 
* `lcslen`: length of the unweighted longest common subsequence
* `overlap`: `lcslen` / `nlocs`
* `lblcs`: best unweighted LCS weighted by length, a lower bound on the true weighted answer
* `wlcs`: LCS with pruned weights less than 0.9 times the max
* `wover`: `wlcs` / `tlen`
  
