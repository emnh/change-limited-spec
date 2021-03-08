# change-limited-spec
Change limited programs: How to remember a program

 - Programs grow from small to large.
 - The evolution of a program can be made explicit.
 - We restrict our attention to simple input/output programs.
 - Basically we are going to do TDD: test-driven development, but limit the amount of change for each patch.
 - In this way, every programmer, including the author, can read the patches from start to finish along with example input/output.
 - This is to combat loss of memory regarding the structure of the program.

 - Granted, textual patches are general, but do I really want to read patches?
 - And what if the second time I read the program I don't want to follow along with the previous evolution, but rather rewrite it?
 - Then is all information from the point the branches diverge on lost?
 - Or can we merge somehow?

 - Does it help if all changes are changes to the AST instead of textual changes?
 - Maybe the sequence of patches is more easily reapplied with changes in between if the changes are AST-based?
