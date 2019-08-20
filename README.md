# ConventionEngine

"ConventionEngine" is a collection of Yara rules looking for PEs with PDB paths that have unique, unusual, or overtly malicious-looking keywords, terms, or other features. For further reading on the context, please see the @FireEye blog series on the subject. 

<link>

Keywords = string words used by malware developers to organize files, folders and code projects, often describing the functionality of the malware.

Terms = string words that show up in paths as a result of operating system, software, or user behavior, often indicating that the developer is riding solo or that code project is not being developed for a "enterprise" software product.

Anomalies = Other things that are less common but are suspicious or indicative of various behaviors.
