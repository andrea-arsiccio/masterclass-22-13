# Masterclass 22.13: SASA module - The solvent accessible surface area of proteins as a collective variable, and the application of PLUMED for implicit solvent simulations

This lesson was given as part of the PLUMED masterclass series in 2022.  It includes:

* Two videos that describe the theory. 
* A series of exercises for you to complete.

The flow chart shown below indicates the order in which you should consult the resources.  You can click on the nodes to access the various resources.  Follow the thick black lines for the best results.  The resources that are connected by dashed lines are supplementary resources that you may find useful when completing the exercise.

This lesson was the thirteenth masterclass in the 2022 series.

```mermaid
flowchart TB;
  A[syntax] -.-> H[Lecture I];
  B[metadynamics] -.-> H;
  C[Hasel algorithm] -.-> H;
  D[LCPO algorithm] -.-> H;
  E[SASA temperature] -.-> H;
  F[SASA pressure] -.-> H;
  G[SASA osmolytes] -.-> H;
  H ==> I[Instructions];
  I ==> J[Lecture II];
  click A "ref1" "A previous tutorial that introduces the basics of PLUMED syntax";
  click B "ref2" "A previous tutorial on metadynamics, which is the method that is used in this tutorial";
  click C "ref3" "A paper describing one of the algorithms that is used to calculate the ASA in the tutorial";
  click D "ref4" "A paper describing the other algorithm that is used to calculate the ASA in the tutorial";
  click E "ref5" "A paper describing how the transfer free energy change upon a change in temperature is calculated";
  click F "ref6" "A paper describing how the transfer free energy change upon a change in pressure is calculated";
  click G "ref7" "A paper describing how the transfer free energy change upon a change in osmolyte solution is calculated"; 
  click H "video1" "A lecture that was given on September 19st 2022 as part of the plumed masterclass series that introduces you to the exercises in this lesson";
  click I "INSTRUCTIONS.md" "Instructions for the exercises that you are supposed to complete";
  click J "video2" "A lecture that was given on September 26th 2022 as part of the plumed masterclass series that goes through the solutions to the exercises in the lesson";
```
