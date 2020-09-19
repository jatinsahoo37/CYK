# CYK
# INPUT SPECIFICATIONS
Our program takes a text file containing the desired Grammar in CNF.
The text file format should be as follows:
From Line 1 to Line N the file must contain Production rules.
If the user wants to input a Grammar text file,
The usage will be as follows:
1.	If only file to be entered(in this case the program will prompt the user for another input a word which is to be checked).
		Command: - java Main <filename>
2.	If the user wants to enter both Grammar file and string to be checked simultaneously
Command: -java Main <filename> <word>
If the user doesn’t input any grammar our code works with a default grammar also.
CONDITION OR CONSTRAINTS
CYK Algorithm is a membership algorithm of context free grammar. It is used to decide whether a given string belongs to the language of grammar or not.

CYK Algorithm operates only on Context Free Grammars given in Chomsky Normal Form.
              
The CKY algorithm as we present it here can only handle rules that are at most binary.
This restriction is not a problem theoretically, but requires pre-processing (binarization) and postprocessing (debinarization).

# GOAL/OBJECTIVE/DESIRED OUTPUT
As we can see the program accepts a string whenever it belongs to the Grammar and rejects it otherwise.
Our program is quite efficient but still it has some flaws as it can’t accept any grammar and only accepts a grammar when its in CNF. 
