Trimmomatic leverages the paired end data and the provided adapter sequences to identify the adapter ligation boundary and trim the adapter 'read-through'. 

For more information see [Trimmomatic manual](http://www.usadellab.org/cms/uploads/supplementary/Trimmomatic/TrimmomaticManual_V0.32.pdf)

Settings

2:30:15 => <seed mismatches\>:<palindrome clipthreshold\>:<simple clip threshold\> 
 
* seedMismatches: specifies the maximum mismatch count which will still allow a full match to be performed
* palindromeClipThreshold: specifies how accurate the match between the two 'adapter ligated' reads must be for PE palindrome read alignment.
* simpleClipThreshold: specifies how accurate the match between any adapter etc. sequence must be against a read..
