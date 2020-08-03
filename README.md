# citation-screening-ml
This work intended to explore the problem of automating citation screening using machine-learning to accelerate the process of generating systematic reviews. It considers citation screening as a binary classification problem whereby a searched study is either "included" for generating a systematic review or is "excluded". 

The input data used for citation screening could be found [here](https://drive.google.com/file/d/14_-NNapaA2SvAxekAAW55zSZo9jSToVN/view?usp=sharing). It is a tab separated file and the data in it is structured as follows.

Structured exercise improves physical functioning in women with stages I and II breast cancer: results of a randomized controlled trial.	11157015	Abstract PURPOSE: Self-directed and supervised exercise were compared with usual care in a clinical trial designed to evaluate the effect of structured exercise on physical functioning and other dimensions of health-related quality of life in women with stages I and II breast cancer. PATIENTS AND METHODS: One hundred twenty-three women with stages I and II breast cancer completed baseline evaluations of generic and disease- and site-specific health-related quality of life, aerobic capacity, and body weight. Participants were randomly allocated to one of three intervention groups: usual care (control group), self-directed exercise, or supervised exercise. Quality of life, aerobic capacity, and body weight measures were repeated at 26 weeks. The primary outcome was the change in the Short Form-36 physical functioning scale between baseline and 26 weeks. RESULTS: Physical functioning in the control group decreased by 4.1 points, whereas it increased by 5.7 points and 2.2 points in the self-directed and supervised exercise groups, respectively (P =.04). Post hoc analysis showed a moderately large (and clinically important) difference between the self-directed and control groups (9.8 points; P =.01) and a more modest difference between the supervised and control groups (6.3 points; P =.09). No significant differences between groups were observed for changes in quality of life scores. In a secondary analysis of participants stratified by type of adjuvant therapy, supervised exercise improved aerobic capacity (+3.5 mL/kg/min; P =.01) and reduced body weight (-4.8 kg; P <.05) compared with usual care only in participants not receiving chemotherapy. CONCLUSION: Physical exercise can blunt some of the negative side effects of breast cancer treatment, including reduced physical functioning. Self-directed exercise is an effective way to improve physical functioning compared with usual care. In participants not receiving chemotherapy, supervised exercise may increase aerobic capacity and reduce body weight compared with usual care.	include	Clinical Trial |Comparative Study |Randomized Controlled Trial |Research Support, Non-U.S. Gov't |Antineoplastic Combined Chemotherapy Protocols |Breast Neoplasms |Breast Neoplasms |Breast Neoplasms |Chemotherapy, Adjuvant |Exercise |Exercise |Female |Humans |Middle Aged |Neoplasm Staging |Quality of Life |Radiotherapy, Adjuvant


Title text \t PMID \t Abstract text \t class (_"include"_ or _"exclude"_) \t MeSH terms separated by pipe __"|"__

| Title         | PMID           | Abstract text  | Class  | MeSH terms (separated by a pipe __"|"__) |
| ------------- |:--------------:| --------------:| ------:|-----------------------------------------:|
| Structured exercise improves physical functioning in women with stages I and II breast cancer: results of a randomized controlled trial.      | 11157015 | Abstract PURPOSE: Self-directed and supervised exercise were compared with usual care in a clinical trial designed to evaluate the effect of structured exercise on physical functioning and other dimensions of health-related quality of life in women with stages I and II breast cancer. PATIENTS AND METHODS: One hundred twenty-three women with stages I and II breast cancer completed baseline evaluations of generic and disease- and site-specific health-related quality of life, aerobic capacity, and body weight. Participants were randomly allocated to one of three intervention groups: usual care (control group), self-directed exercise, or supervised exercise. Quality of life, aerobic capacity, and body weight measures were repeated at 26 weeks. The primary outcome was the change in the Short Form-36 physical functioning scale between baseline and 26 weeks. RESULTS: Physical functioning in the control group decreased by 4.1 points, whereas it increased by 5.7 points and 2.2 points in the self-directed and supervised exercise groups, respectively (P =.04)... | (_"include"_ or _"exclude"_) | xyz |
