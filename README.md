# COMP4030 - Buffer Overflow Exploitation Lab

## Lab Description

In this lab, you will learn how to exploit a basic binary that contains a buffer overflow vulnerability.

This lab will guide you through the process of identifying the vulnerability, understanding modern binary protections, and crafting an exploit script.

## Objectives

- Understand common binary security protections such as ASLR, PIE, and NX.
- Identify buffer overflow vulnerabilities in simple programs.
- Use GDB (GNU Debugger) to analyze and debug binaries.
- Use Python and the pwntools library to craft automated exploit scripts.

## Student Deliverables

Please submit to Canvas:

- A **single PDF report** covering **all four challenges**, containing:
  - A detailed **step-by-step explanation** of how each binary was exploited:
    - How you identified the vulnerability.
    - How you calculated the offset to overwrite the return address.
    - How you determined binary protections (ASLR, PIE, NX) and bypassed them.
    - How you crafted the payload.
    - How you used pwntools to automate the exploit.
  - Output logs or **screenshots** showing successful exploitation (e.g., flag printed).
  
- A **ZIP file** containing:
  - `pie_overflow.py`
  - `ret2shellcode.py`
  - `ret2win.py`
  - `trigger_win.py`
  - `stack_canary.py`
  - The PDF report: `report.pdf`