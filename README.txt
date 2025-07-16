Java Thread dump Analyzer
==========================
A simple tool to analyze Java thread dumps and group threads by stack trace patterns.

Name
====
I named the script snowy (Tintin’s dog).

USAGE
=====
1. Analyze a thread dump file: ./snowy threaddump.txt
2. Interactive mode (discover processes): ./snowy

Help
=========
./snowy -h

OUTPUT
======
1. Total thread count
2. Groups of threads with similar stack traces
3. Thread names and their states
4. Stack trace signatures with normalized addresses
5. Colorized output for easy reading
