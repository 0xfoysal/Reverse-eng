Load without any analysis (file header at offset 0x0)
-----------------------------------------------------
analyze all : aa
show sections : is
list function : afl
list import : ii
list entrypoint: ie
seek to function : s sym.main


Project management
------------------
open Prject : PO <name>
save Project : PS <name>
Edit Project note: Pn -

inspection a function
---------------------
show basic block disassembly : pdb
show function disassembly : pdf
show function Argument : afa
show function variables: afvn
add/analyze function : af

comments
--------
add comments : cc!
Append comment: cc <text>
OverWrite comment: ccl <text>
show comment: cc
show comment in function : ccf

visual mode
--------
