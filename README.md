# COMPILER-DESIGN-BASICS

COMPANY : CODTECH IT SOLUTIONS

NAME : VASU PATHAK 

INTERN ID : CT04DF1007

DOMAIN : C PROGRAMMING

DURATION : 4 WEEKS

MENTOR NAME : NEELA SANTHOSH KUMAR

Detailed Description:

A compiler is a system program that translates high-level programming code into machine code. It does this in several phases, starting with Lexical Analysis — the process of breaking code into smaller components called tokens.

In this task, I designed a lexical analyzer using the C programming language. The program reads an input file character by character and determines which characters form keywords, operators, and identifiers. These elements are called tokens, and identifying them is the role of the lexical analyzer (also known as a scanner).

The logic involves:

Reading characters until whitespace or delimiter

Comparing strings with a list of known keywords

Checking if a string is made up of letters (identifiers) or symbols (operators)

Printing token classifications accordingly


The code includes:

An input file reader (fopen, fgetc, etc.)

Arrays or lists of predefined keywords and operators

Conditional logic to categorize tokens

Output formatting for readability



Tools and Learning Resources Used:

YouTube: To understand the compiler phases visually and follow along with live coding examples of lexical analyzers in C

ChatGPT: Helped troubleshoot segmentation faults, improve logic for character-by-character token recognition, and clarify edge cases (e.g., <=, >=, != as multi-character operators)

Grok AI: Used for revising string operations and file handling in C




Applications of Lexical Analyzer:

Compiler Design: It is the first stage in every compiler (C, Java, Python), converting raw source code into meaningful tokens

Syntax Highlighting: In modern IDEs or code editors (like VS Code), lexical analyzers identify keywords and color-code them

Static Analysis Tools: Used in linters or tools that analyze code before execution to catch errors

Code Optimization: Tokenization helps compilers make decisions about how best to allocate memory or CPU instructions

Interpreters and Scripting Engines: Even in interpreted languages like Python, lexical analysis is the first processing step



Challenges Faced:

Handling Multi-character Operators: Initially treated each character as a separate operator. Modified logic to handle ==, !=, <=, >=, etc.

Differentiating Keywords and Identifiers: Created a dedicated list of reserved keywords and checked input words against it.

File I/O Bugs: Faced issues with reading till EOF. Debugged buffer logic using suggestions from ChatGPT.

Whitespace and Delimiters: Accurately handling spaces, tabs, and line breaks was tricky but essential for proper token separation.



Conclusion:

Building a lexical analyzer gave me a solid understanding of the front-end architecture of compilers. This task helped me get hands-on experience with file handling, string processing, and token classification in C. Using YouTube tutorials, Grok AI practice, and ChatGPT support, I was able to build an efficient program that demonstrates the basics of compiler design. This project also opened the door to further compiler concepts like parsing, syntax analysis, and code generation.
