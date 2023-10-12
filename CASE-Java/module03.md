# Secure Application Design and Architecture

 Secure Design Principles helps to eliminate design and architecture flaws and mitigate common security vulnerabilities within the application.
 * Fail Securely
 * Apply Defense in Depth
 * Do Not Trust User Input


## Threat Modeling Phases


* **Attack Surface Evaluation :** Application is decomposed and its entry points are reviewed from an attacker’s perspective. 
* **Threat Identification :** Each entry points are then reviewed against potential threats 
* **Impact Analysis :** Impact of potential threats is calculated in terms of risk 
* **Control Recommendations :** Security controls are recommended to meet security objectives

## Perform Application Modeling using Data Flow Diagrams (DFDs)

The collected information such as external entities, entry points, assets and trust level will help in accurately modeling the application by using Data Flow Diagrams (DFDs).

![DFD Components](https://github.com/IHackPy/EC-Council-CASE-Java-Net/blob/main/CASE-Java/DFD_Component.png)

## Rating the Threats 


The formula for calculating risk is: ***RISK = PROBABILITY * DAMAGE POTENTIAL***

### DREAD Model :
* DREAD model is used to rate the various security threats on the application by **calculating risks of each threats**




## Secure Application Architecture

* Security at one tier is not enough as attacker can breach the security of another tier to compromise the application
* Design web application architecture with defense-in-depth principle i.e. providing security at each tier of the web application


[click here](https://github.com/IHackPy/EC-Council-CASE-Java-Net/blob/main/CASE-Java/module04.md) to learn about ***module04***
