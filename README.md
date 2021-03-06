# Mettel Implementation of UBiSKt Tableau-calculus
This tableau-style theorem-prover for the logic UBiSKt has been generated using the theorem-prover generator Mettel. Mettel is released under GPLv3. For more information about Mettel please see http://mettel-prover.org/demo.php. and http://www.mettel-prover.org/papers/MetTeL2SysDesc.pdf. 

In order to use the tableau-prover you will need Java Runtime Environment, Version 1.6.0 or later. 

In the following repository you will find all the files needed to use the tableau-prover, a file called Tableau_2 where the tableau rules for UBiSKt are specified, a folder called axioms with all the axioms and rules of HUBiSKt, and a folder called propositions with all the propositions of Section 3.4 of the thesis "Graph Granularity through Bi-intuitionistic Modal Logic" by G. Sindoni, (2020).
This implementation has also been published in the paper "Axiomatizing Discrete Spatial Relations", by G. Sindoni, K. Sano and J. G. Stell (2018).

To prove one of the axioms or rules with the prover download the content in one directory, and run the following command from within this directory in the terminal:

```
 java -jar BISKT.jar -i axioms/<problem> -t Tableau_2
```

To prove one of the propositions with the prover run the following command from within this directory in the terminal:
   
```
 java -jar BISKT.jar -i propositions/<problem> -t Tableau_2
```


When for an input problem of the form @i F(P) for some formula P the result given by the prover is `unsatisfiable’, that means that P is a theorem in the logic UBiSKt. 


