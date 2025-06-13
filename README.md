## DNSObelisk: Kernel Enforced Endpoint Security for Distributed Environments 
### WhitePaper

* This repository contains comprehensive documentation for the complete Security framework to disrupt advanced DNS C2 attacks and APT implants.
* This research and implementation is neither sponsored from Univeristy of Washington nor affiliated to any university graduate research group.
* This implementation and architecture is completely done by me as an independent research student from University of Washington.
* The core framework codebase is licensed under AGPLv3, and is open for collaboration and enhancements, howerver the corresponding architecture, algorithms, and core implementations explained in the report, and any further changes added by me are subject to copyright under the ownership of the original author.
* The entire framework builds upon primary  goal to make DNS a safe protocol, moving DNS security inside Linux kernel to safeguard massive data planes and production cloud environments from  evolving DNS attack vectors. In addition, the framework focuses on wider goal of enhancing endpoint security to acheive unprecendented security strength to disrupt emerging attack vectors causing to significant damages to enterprises.

### Structure
```
    ├── detailed/
    │   ├── UWThesis__1_-3.pdf
    │   └── uwthesis.tex
    ├── images/
    ├── Presentations/
    ├── kernel_dns_sec_report.tex
    ├── LICENSE
    ├── README.md
    ├── unsrtnatet.bst
    ├── uwthesis.bib
    ├── uwthesis.cls
    └── Vedang_Final_Report.pdf
```
* ```detailed/```: Covers Latex for the much detailed implemntation of the security freamework.
* ```images/```: Results, Evaluation of the security freamework.
* ```Presentations/```: Covers all the presentations for all conference talks and final defense at university.
* ```kernel_dns_sec_report.tex```: Final shortened Latex for the same report
* ```Vedang_Final_Report.pdf```: Final submitted project report for the complete framework
* Rest of files covers supporting Latex files for University of Washington Latex format.


### Disclamer
* The entire security framework documented in the report follows University of Washington Project report template (considering the framework implementation for my final graduation was defended in project track and not in thesis track). However, the work was presented and will be presented in referred talks at major kernel and security conferences (LSS, Netdev, Black Hat breifings).
* The report is in progress to be published formally at research conferences (USENIX, NDSS).
