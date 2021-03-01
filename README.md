# programming-language

Purpose of beginning this project: 
I began this project because I want to develop a deeper understanding
of how programming languages work. Currently I am in the testing and 
researching phase. I will document my progress.

Resources and Documentation:
https://llvm.org/docs/GettingStarted.html
https://llvm.org/devmtg/2013-04/

Understanding the Architecture of a Programming Language:

1. Begin with code. 
2. Use a PARSER in order to take the code and build...
3. Abstract Syntax Tree (aka. AST)
4. Generate machine code for the processor to interpret.
5. The step before 4 would be LLVM phases to assist generation of Machine Code.
6. We are responsible for writing the front-end. 

AST Information:
Clang is used for this.

