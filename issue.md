
This repo forked from [ShengLi](https://github.com/ShengLi/edmr)

when run the ´edmr´ function, had error Error in `[.data.frame`(peaks, overlap.idx@subjectHits, ) : 
  no slot of name "subjectHits" for this object of class "SortedByQueryHits"


Ans seems this error also occur to others, see [here](https://mran.microsoft.com/snapshot/2016-04-28/web/checks/check_results_edmr.html)

It says Error in `[.data.frame`(peaks, overlap.idx@subjectHits, ) :
     no slot of name "subjectHits" for this object of class "SortedByQueryHits"
    Calls: edmr ... myDiffToDMR -> getDMR -> data.table -> cbind -> [ -> [.data.frame
    Execution halted




