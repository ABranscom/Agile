# AGILE

AGILE is an AGI engine written in C#. AGI was the name of the adventure game interpreter used by Sierra On-Line to run the 3D animated adventure games that they released in the 1980s, which included games such as King's Quest 1/2/3/4, Space Quest 1/2, Police Quest, Leisure Suit Larry, Manhunter 1/2, Gold Rush, Donald Duck's Playground, Black Cauldron, and Mixed-Up Mother Goose.

AGILE is an almost complete implementation that has attempted to align as close as possible to the original interpreter's behaviour. Back in the late 1990s, I wrote an AGI interpreter in C called MEKA. This interpreter was nearly complete but was a bit buggy. The functionality of MEKA was based primarily on the AGI specifications that I had helped create, which were based on reverse engineered info. Since then some fragments of original AGI interpreter source code has emerged (apparently from the slack space of original game disks) that has shed some light on the inner workings of the interpreter. AGILE has made use of the MEKA source, the AGI specifications, and the original AGI interpreter source code fragments to create something close to accurate.

AGILE makes use of an AGILibrary written by various authors, including me, but as the original repo for that is private and not mine, the AGILE repo here includes only the compiled DLL for that library.
