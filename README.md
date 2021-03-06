
# <img src="https://raw.githubusercontent.com/Charles-Wang-uni/UMTG/master/images/logo.png" width="170"> Use Case Modeling & Test Generation

UMTG is a toolset for automatically generating executable and traceable system test cases from use case specifications and domain model. In order to extract behavioral information from use case specifications and enable test automation, UMTG employs Natural Language Processing (NLP), a restricted form of use case specifications, and constraint solving.

UMTG is integrated with two tools, IBM Doors and IBM Rational Rhapsody that are widely adopted in industry to manage requirements and design systems. 

### UMTG plug-ins for IBM DOORS

UMTG plug-ins for IBM DOORS is aimed at helping engineer to write high quality Use Case Specifications by following a Restricted Use Case Modeling (RUCM) Methodology<sup>[1]</sup>.

RUCM<sup>[1]</sup> relies on a use case template and a set of restriction rules for textual Use Case Specifications (UCSs) to reduce the imprecision and incompleteness inherent to UCSs. Controlled experiment evaluation of RUCM<sup>[1]</sup> is easy to apply, has enough expressive power, helps improve the understandability and the quality of use cases and facilitates automated analysis.

UMTG extends the original RUCM<sup>[1]</sup> for test generation purpose and provides facilities help engineer to write high quality UCSs that follow the template and obey all the rules.

UMTG employs Natural Language Processing (NLP) to process the UCSs :

1. Find violations of the template or restriction rules that may course ambiguity.

2. Extract the behavioral information of the system which is used for test generation.

### UPDATE

* [4/11/2016] Add new feature: Jump to Reference Flow Step

  ##### DEMO: Specific Alternative Flow
    <img src="https://raw.githubusercontent.com/Charles-Wang-uni/UMTG/master/images/ref1.gif" width="700">

  ##### DEMO: Bounded Alternative Flow
    <img src="https://raw.githubusercontent.com/Charles-Wang-uni/UMTG/master/images/ref2.gif" width="700">
  
* [4/05/2016] Add new feature: Add Specific Alternative Flow
 
  ##### DEMO: Add a Specific Alternative Flow to a Basic Flow step
    <img src="https://raw.githubusercontent.com/Charles-Wang-uni/UMTG/master/images/alt.gif" width="700">

### REFERENCE

[1] Tao Yue , Lionel C. Briand , Yvan Labiche, Facilitating the transition from use case models to analysis models: Approach and experiments, ACM Transactions on Software Engineering and Methodology (TOSEM), v.22 n.1, p.1-38, February 2013

