# singleT-CPU-logisim
使用logisim搭建单周期CPU，实现几乎所有常用Mips指令，基本算数类（add, sub, slt, addiu等）、逻辑运算类（and, or, xor等）、移位类（sll, sllv等）、存储访问类（lw, sw）和分支跳转类（bne, beq, j, jal, jr等）。

cpu_own实现几乎所有指令，包括但不限于j, jal, jr, jalr, bne, beq, blez, sub, add, addiu, subu, xori, lui, sll, sllv, slt, slti, lw, sw等，几乎所有常用Mips指令都已经实现。需要注意的是，没有实现lb, lh, sb, sh指令，这些指令的实现需要更改DM模块，或在main中进行响应的修改。

cpu_simple实现常用指令lw, sw, beq, j, ori, addiu, addu和subu，初学者可以先通过cpu_simple理解各模块之间的关系和基础指令的实现逻辑，在此基础上尝试搭建其他复杂指令。

同时，附带传统logisim运行平台，可以在各种操作系统上选择.jar版或.exe版

致谢：https://kamonto.github.io/Kamonto_blog

如果你也是北航的学生并深受机组的折磨，不要错过
