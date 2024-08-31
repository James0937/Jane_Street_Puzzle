# Jane_Street_Puzzle
The history of my puzzle-solving journey. Started in January 2024.

# History
## January 2024: Some F Squares
Solved and passed
## February 2024: Some Off Square
Solved (with trick) and passed
## March 2024: Hooks 10
Solved and passed
## April 2024: Robot Capture-the-Flag
Solved and passed
## May 2024: Number Cross 4
Gave up. This problem cannot be solved manually since there are too many possibilities (cut or not, length of number) and it must use some huge number to complete this puzzle.
The figure shows my initial process when trying to solve it manually.
## June 2024: Altered States 2
Solved and passed.
## July 2024: Many Happy Returns
Gave up. I'm not a native English speaker, and this wordplay problem is quite tricky to me.
The txt file shows some idea of matching.
## August 2024: Tree-edge Triage
Too busy to work on this puzzle this month. Just have an initial idea of it:

Think of it layer by layer. For example, let's assume the probability of Aaron win is "A". Obviously we have A=f(p). If the binary tree is not infinite but only have height of 1, we get $A=f_1(p)=1-(1-p)^2$ . If its height is 3 (even height is not meaningful for this question) instead, we have another answer $A=f_3(p)$ . Noticed that every whole tree can be divided into the pieces of the same-structured subtrees, we can assume there are some relationships between f_1(p) and f_3(p), and it can be extend to the situation of height of 5, 7, 9... 2n+1. Show it by induction, and then we get A_n=f(n,p).

And finally, when n approaches infinite, we get the A for infinite height binary tree as A=f(p). By intuition, A becomes bigger when p goes larger. Then the p value of the equation f(p)=0 is just the answer we want.