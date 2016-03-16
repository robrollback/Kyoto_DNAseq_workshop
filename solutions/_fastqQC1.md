sequenceQualityChart
* Quality drops towards the end of the reads
* There seem to be spikes quality at specific lengths which is also seen in the sequence length distribution images

Why is this?

The reasons for the spikes and jumps in quality and length is because there are actually different libraries pooled together in the 2 fastq files. 

The sequencing lengths vary between 36,50,76 bp read lengths. The Graph goes > 100 because both ends are appended one after the other.                      

KnownSequences: The SRR data set has a small % of short or partial adapters in it.  These will need to be removed.                      
                      


