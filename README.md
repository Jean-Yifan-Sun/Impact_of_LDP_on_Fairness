# Impact-of-KRR-on-Fairness
Repository for the paper: Impact of Local Differential Privacy on Fairness. (Here the link to the arxiv needs to be added and the bibtex for citation).

# Codes & Datasets
All the experiments are implemented in Python 3. We use Random Forest model for classification with its default hyper-parameters and we use the
ten-fold cross-validation technique. For k-RR mechanism, we use the implementation in [Multi-Freq-LDPy Python library](https://github.com/hharcolezi/multi-freq-ldpy). Since LDP protocols and ML algorithms are randomized, we report average results over 20 runs. 
* The [datasets](https://github.com/KarimaMakhlouf/Impact_of_LDP_on_Fairness/tree/main/Datasets) folder includes all the used and generated datasets
* The [Results](https://github.com/KarimaMakhlouf/Impact_of_LDP_on_Fairness/tree/main/Results) folder contains all the results (as csv files) of fairness metrics before and after applying the KRR mechanism settings for all the datasets. The settings applied in this study are:
    - sLDP: only the protected attribute is obfuscated.
    - allsLDP: all sensitive attributes (including the protected attribute) are obfuscated.
    - alloLDP: all the attributes except the target are obfuscated.
    - ayLDP: only the protected attribute and the target are obfuscated. 

# Environment

# Contact
For any question, please contact:

Karima Makhouf: karima.malhlouf [at]inria.fr

Héber H. Arcolezi: heber.hwang-arcolezi [at] inria.fr

