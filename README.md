# comp410.Assignment4
# Step-by-Step Instructions

## Step 1: Implement a Boolean Expression Evaluator in Prolog

#### Download boolean_evaluator.pl. You will need to implement a recursive evaluator of Boolean expressions in this file, much like the evaluator you implemented for Assignment 1. This will be implemented via a procedure (that is, a combination of facts and rules which have the same name) named eval. Note that the representation of the AST has been slightly changed, corresponding to a more idiomatic Prolog representation. The comments in the file provide more details.

## Step 2: Implement a SAT Solver in Prolog

#### Download sat_solver.pl. You will need to write a procedure (that is, a combination of facts and rules which have the same name) named isTrue which determines if a given Boolean formula is true. This formula has a very similar AST as the one from the SAT solver you implemented for Assignment 1, with mostly just changes to make the representation a little more idiomatic to Prolog. However, there is one key difference: instead of variables in the formula being represented by atoms (or symbols for Racket), here we represent the variables using Prolog variables (i.e., logical variables). This effectively allows us to “modify” the formula in-place as we learn information about it (i.e., which variables need to be true or false.

#### Relevant to the aforementioned representation of literals, this means the following:

#### If we have a positive literal, the Prolog variable in the literal must be equal to the atom true. That is, for a positive literal to be true, its variable must hold the value true.
 
#### The comments in the file provide further details.

#### (OPTIONAL BONUS WORTH +15%) Step 3: Answer Reflection Questions

#### This may come as a bit of a surprise, but you implemented a full tableau-based SAT solver in the previous step. However, the code is (hopefully!) a lot simpler than the code you wrote for Assignment 1.

#### Download assign4_questions.txt. There are questions in this file which ask you to reflect on your implementation, in particular with how it compares and contrasts with the implementation you wrote for Assignment 1.

## Step 4: Turn in Your Solution Using Canvas

#### Log into Canvas, and go to the COMP 410 class. Click “Assignments” on the left pane, then click “Assignment 4”. From here, you need to upload the following files:

* boolean_evaluator.pl
* sat_solver.pl
#### assign4_questions.txt (only if you attempted the bonus)
#### In addition, if you collaborated with anyone else, be sure to download collaborators.txt and write the names of the people you collaborated with in the file, one per line. Please submit this file along with the other files.

##### You can turn in the assignment multiple times, but only the last version you submitted will be graded.