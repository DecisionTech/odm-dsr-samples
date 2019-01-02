# Healthcare Medical Decision Support

## Introduction

This is a standalone Decision Service project sample to demonstrate using IBM Operational Decision Manager (ODM) in the healthcare industry.

### Healthcare rules
This decision service shows how to leverage business rules for medical decision support.

### What is drug interaction?
A drug interaction is a situation in which a substance affects the activity of a drug,
i.e. the effects are increased or decreased, or they produce a new effect that neither 
produces on its own. Typically, interaction between drugs come to mind (drug-drug interaction)
Source: http://en.wikipedia.org/wiki/Drug_interaction

### Software Prerequisites

Requires access to ODM Rules. 

## Getting Started
Please follow these instructions:
### Add eGit to your Rule Designer environment
1. From Rule Designer, click Help and click Install New Software

2. Enter http://download.eclipse.org/egit/updates into the Work with field and click Enter

3. Check the box for Git integration for Eclipise and click Next

4. On the Install Remediation Page, validate the page contents and click Next

5. On the Insall Details page, validate the page contents and click Next

6. On the Review Licenses page, validate the license text, select the "I accept the terms of the license agreement" if you agree, and click Finish

### Use eGit to import into your Rule Designer workspace
1. Open the Git Repositories view
    - Click on Window, Show View, Other...
    - Find Git Repositories and click Open

2. Open a web browser and navigate to the following URL:

    https://github.com/DecisionTech/odm-dsr-samples 
    
3. On the odm-dsr-sample page
    - Click Clone or Download to obtain the repository URI which is
        
        https://github.com/DecisionTech/odm-dsr-samples.git

4. Return to Rule Designer and in the Clone Git Repository dialog
    - Enter the following (or the one you obtained in step 3) in the URI field:  
    
        https://github.com/DecisionTech/odm-dsr-samples.git

5. Click Next (This is a public repository)

6. Leave master selected and click Next

7. On the Local Destination page, change Directory to a good directory for you and click Finish
    
### Import Projects into Rule Designer
1. In Rule Desiger, Click on File and then click Import...

2. Under General select "Existing Projects into Workspace" and click Next

3. For the "Select root directory" field, use the directory selected in step 7 to define the fill path to the "healthcare-medical-base" folder

4. In the Projects section, check "Healthcare Medical Support" and "Java XOM"

5. In the Options section, check "Copy projects into workspace" 

6. Click Finish

