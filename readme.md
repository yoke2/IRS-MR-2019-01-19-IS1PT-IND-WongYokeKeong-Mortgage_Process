# Machine Reasoning Course Report - Individual

## SECTION 1 : PROJECT TITLE
## Mortgage Business Process Enhancement

---
## SECTION 2 : EXECUTIVE SUMMARY
The current Mortgage Process discussed during the class workshops demonstrates that how Machine Reasoning can simplify the mortgage application process by taking an automated rule-based approach and assist the final approver in assessing a mortgage application.

The discussed process can be further enhanced by enabling the rules engine to take into account the credit rating level of the applicant. Based on the Credit Score description by the [Credit Bureau of Singapore](https://www.creditbureau.com.sg/credit-score.html), we can additionally consider the Risk Grade of the application. In this report, we shall define an applicant to be more credible if the applicant has a Risk Grade of "CC" or higher (rating of 1825 to 2000).

The aforementioned rule shall be enhanced in the Guided Decision Table "MortgageMachineReasoningDT" with the corresponding validation (valid values of credit rating is between 1000 and 2000) added in the Guided Rule "Validate Credit Rating".


---
## SECTION 3 : CREDITS / PROJECT CONTRIBUTION

| Official Full Name  | Student ID (MTech Applicable)  |
| :------------ |:---------------:|
| Wong Yoke Keong | A1234567A |

---

## SECTION 4 : USER GUIDE

### [ 1 ] To run the system using iss-vm

> download pre-built virtual machine from http://bit.ly/iss-vm

> start iss-vm

> Launch KIE 7.12 via the "Tool KIE shortcut"

> After startup is complete, launch Google Chrome and click on the KIE shortcut

> Login as wbadmin

> Create New Space

> Import Project from Github

> Deploy Project

> Initiate Process Instance as wbadmin

> Approve process using iss-mk

### [ 2 ] To run the system in other/local machine:

> Download jBPM Server 7.12.0 from https://download.jboss.org/jbpm/release/7.12.0.Final/jbpm-server-7.12.0.Final-dist.zip

> 
    Download and unzip it.
    On Linux/Mac, run jbpm-server-7.12.0.Final-dist/bin/standalone.sh
    On Windows, run jbpm-server-7.12.0.Final-dist/bin/standalone.bat
    Open browser and go to http://localhost:8080/jbpm-console/kie-wb.jsp


---
## SECTION 5 : Appendix

### Enhancement Test Results Demonstration.pdf
* This file contains the test results before and after the implementation of the enhancements to Credit Rating Risk Grade and Credit Rating validation

---

**This [Machine Reasoning (MR)](https://www.iss.nus.edu.sg/executive-education/course/detail/machine-reasoning "Machine Reasoning") course is part of the Analytics and Intelligent Systems and Graduate Certificate in [Intelligent Reasoning Systems (IRS)](https://www.iss.nus.edu.sg/stackable-certificate-programmes/intelligent-systems "Intelligent Reasoning Systems") series offered by [NUS-ISS](https://www.iss.nus.edu.sg "Institute of Systems Science, National University of Singapore").**
