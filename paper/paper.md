---
title: 'Visualizing Quantum Macro Assembler for D-Wave Systems ( QMASM )'
tags:
  - Python
  - Quantum
  - Cyber Security
  - D-Wave
  - Vulnerability
  - Security Threats
  - Qmasm
authors:
  - name: Hesham H.Alsaad
    orcid: 0000-0003-0884-3566
    affiliation: 1
affiliations:
 - name: College of Technological Innovation, Zayed University, Abu Dhabi, UAE
   index: 1
date: 6 May 2019
bibliography: paper.bib
---

# Abstract

As we enter the quantum computing era, security becomes of at most importance. With the release of D-Wave One in 2011 and most recently the 2000Q, with 2,000 qubits, and with NASA and Google using D-wave Systems quantum computers, a thorough examination of quantum computer security is needed. Quantum computers underlying hardware is not compatible with classical boolean and binary-based computer systems and software. Assemblers and compliers translate modern programming languages and problems into quantum-annealing methods compatible with quantum computers. This paper presents a vulnerability assessment utilizing static source code analysis on Qmasm Python tool. More specifically, we use flow-sensitive, inter-procedural and context-sensitive data flow analysis to uncover vulnerable points in the program [@[@aldwairi2017flukes]]. We demonstrate the Qmasm security flaws that can leave D-Wave 2X system vulnerable to severe threats.


# About

This notebook covers the visualization analysis [@zenodo] results of ``QMASM`` is a tool that computes simple heuristic computation algorithms. Developers, on the other hand, may integrate the solution into D-wave system directly or by using local simulator which poses questions about the reliability security of tool such as ``QMASM``. We use IBM Brunel Visualization language [@brunelvisualizations] to visualize and analyze the results of the following selected tools for comparison due to its support in providing comprehensive security debugging analysis to the ``QMASM`` framework.

# Publication

This project is still maintained for the replication of our published paper Analyzing D-Wave Quantum Macro Assembler Security on Conference: 16th International Conference on Information Technology : New Generations ITNG 2019 at Las Vegas, NV. For citation use ACM Digital Library [@alsaadi2019analyzing].


# QMASM Releases

The table below summarizes the main description of  all  QMASM releases that has been analyzed.

| Name | Version | Date | Python Files | Description | Size |
| --- | --- | --- | --- | --- | --- |
| QASM | 1.0 | August 26,2016 | 19 | The first formal release of QASM. Tested using Python 2.7.12, SAPI 2.4, and qOp 2.2, all on Ubuntu Linux 16.04 LTS (Xenial Xerus) | 216 KB |
| QMASM | 1.1 | October 27,2016 | 19 | Renamed QMASM, the code contains miscellaneous, sources, disconnected variables, and both proxied and non-proxied network access | 232 KB |
| QMASM | 1.2 | November 12,2016 | 19 | Contains new output format: the MiniZinc constraint-modeling language by using –format=minizinc on the qmasm command line | 380 KB |


## How QMASM works

#### Step 1:
Users and developers access the environments to program and give instructions  via the tool using a set of libraries that may have inject malicious code.
Python , C, C++ , MATLAB

#### Step 2:
D-Wave system acts as a front-ended system on a network by just like a local server. Instructions sent to the quantum processor (QP) for resolves. 

#### Step 3:
Formulates problem resolvents with a set of series, sampling the information and processing to retain for the user over the GUI or CLI.

![Image of Yaktocat](https://raw.githubusercontent.com/5998/Quantum-Security/master/how.jpg)


# Python Source Code Analysis Tools

### Mypy

Is an experimental optional static type checker for Python that aims to combine the benefits of dynamic (or ”duck”) typing and static typing [@lehtosalo2017mypy]. Mypy combines the expressive power and convenience of Python with a powerful type system and compile-time type checking. Mypy type checks standard Python programs developed in Python 2 and 3 (PEP484); run them using any Python VM with basically no runtime overhead.

### Vulture

Python static analysis tool that finds unused classes, functions, and variables in Python programs [@seipp2017downward] [@yang2016improving]. Vulture compatible with Python 2.6, 2.7 and 3.x it helps to clean up errors in high-level Python scripts [@niu2019deep], vulture can be used together with pyflakes, however, in this research will be examined independently.

### Xenon

Python tool a complexity monitoring tool based on Radon [@lacchia2017radon] . Xenon is programmed using given command with various sets of thresholds for code complexity analysis. This tool will be utilized in the research to accurately investigate the threat level complexity found in Python blocks and modules [@subedi2018forensic] [@alsaadi2018penetration].


# Environment Setup

- Python 3.5 + Spark.

We use different visual representation to show the number of threat levels found in QMASM released on Jul 19, 2018. We also show the relationships between various properties, for example Line-Of-Code (LOC) & threat level range (High, Medium & Low). The use of Different tools provides different execution techniques, which is necessary to segregate the files for precise analysis.


# Acknowledgements

This work was supported by Zayed University Research Office, Research Incentive Fund #R18054.

# References

