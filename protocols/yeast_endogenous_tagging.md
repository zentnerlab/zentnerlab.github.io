# Endogenous tagging of yeast genes

[Back to index](https://zentnerlab.github.io/)

##### Notes
-This protocol can be used with any pFA6a-based tagging vector and the [F2/R1 primer pairs](http://yeastgfp.yeastgenome.org/yeastGFPOligoSequence.txt) used to construct the yeast GFP collection. 
-For small epitope tags (i.e. 3xFLAG, 3xHA), a 45” extension time works well. For large tags (i.e. AID, 3xFLAG-MNase), a 1’15” extension time is needed.

##### Protocol
1. For each PCR, prepare the following reaction mix:
    
    | Component | Volume |
    |-----------|--------|
    | 5X Q5 buffer | 10 μL |
    | 10 mM dNTPs (2.5 mM each) | 1 μL |
    | 10 μM F2 primer | 2.5 μL |
    | 10 μM R1 primer | 2.5 μL |
    | 1-5 ng DNA | X μL |
    | Q5 polymerase | 0.5 μL |
    | H&#8322;O | to 50 μL |

2. Cycle using the following parameters:

    | Step                      | Temperature  | Time     |
    |---------------------------|--------------|----------|
    | Initial denaturation      | 98C          | 30"      |
    | Amplification (25 cycles) | 98C          | 10"      |
    |                           | 55C          | 30"      |
    |                           | 72C          | 45" or 1'15"    |
    | Final extension           | 72C          | 2'       |
    | Hold                      | 10C          | &#8734;  |
    
6. Analyze 5 μL of the reaction on an agarose gel.
