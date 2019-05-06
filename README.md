# Visualizing Quantum Macro Assembler for D-Wave Systems ( QMASM )
## Project: Analyzing D-Wave Quantum Macro Assembler Security

Orginal Project by [Hesham H.Alsaadi](https://www.researchgate.net/profile/Hesham_H_Alsaadi)
---
Project Hosted in GitHub Page [Quantum Security](https://github.com/5998/Quantum-Security)

This notebook covers the visualization analysis results of QMASM is a tool that computes simple heuristic computation algorithms. Developers, on the other hand, may integrate the solution into D-wave system directly or by using local simulator which poses questions about the reliability security of tool such as QMASM.  We use IBM Brunel Visualization language to visualize and analyze the results of the following selected tools for comparison due to its support in providing comprehensive security debugging analysis to the QMASM framework.

## About
This project is still maintained for the replication of our published paper <a href="https://www.researchgate.net/publication/331951665_Analyzing_D-Wave_Quantum_Macro_Assembler_Security" target="_blank">Analyzing D-Wave Quantum Macro Assembler Security</a> on Conference: 16th International Conference on Information Technology : New Generations ITNG 2019At: Las Vegas, NV. For citation use ACM Digital Library.

## Abstract
As we enter the quantum computing era, security becomes of at most importance. With the release of D-Wave One in 2011 and most recently the 2000Q, with 2,000 qubits, and with NASA and Google using D-wave Systems quantum computers, a thorough examination of quantum computer security is needed. Quantum computers underlying hardware is not compatible with classical boolean and binary-based computer systems and software. Assemblers and compliers translate modern programming languages and problems into quantum-annealing methods compatible with quantum computers. This paper presents a vulnerability assessment utilizing static source code analysis on Qmasm Python tool. More specifically, we use flow-sensitive, inter-procedural and context-sensitive data flow analysis to uncover vulnerable points in the program. We demonstrate the Qmasm security flaws that can leave D-Wave 2X system vulnerable to severe threats.

## QMASM Releases

The table below summarizes the main description of  all  QMASM releases that has been analyzed.

| Name | Version | Date | Python Files | Description | Size |
| --- | --- | --- | --- | --- | --- |
| QASM | 1.0 | August 26,2016 | 19 | The first formal release of QASM. Tested using Python 2.7.12, SAPI 2.4, and qOp 2.2, all on Ubuntu Linux 16.04 LTS (Xenial Xerus) | 216 KB |
| QMASM | 1.1 | October 27,2016 | 19 | Renamed QMASM, the code contains miscellaneous, sources, disconnected variables, and both proxied and non-proxied network access | 232 KB |
| QMASM | 1.2 | November 12,2016 | 19 | Contains new output format: the MiniZinc constraint-modeling language by using –format=minizinc on the qmasm command line | 380 KB |
