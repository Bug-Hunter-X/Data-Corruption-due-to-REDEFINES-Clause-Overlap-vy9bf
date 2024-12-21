# COBOL Redefines Clause Bug
This example demonstrates a potential issue with the REDEFINES clause in COBOL.  Improper use can lead to data corruption or unexpected program behavior. The bug arises from overlapping data areas defined using REDEFINES, which can lead to unintended modification of data.

The `bug.cob` file contains the erroneous code, while `bugSolution.cob` offers a corrected version.  Review the code and documentation to understand the problem and learn how to avoid it in your own COBOL programs.