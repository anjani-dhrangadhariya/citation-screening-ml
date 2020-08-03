# citation-screening-ml
This work intended to explore the problem of automating citation screening using machine-learning thereby accelerating the process of generating [systematic reviews](https://en.wikipedia.org/wiki/Systematic_review#:~:text=Systematic%20reviews%20are%20a%20type,synthesize%20findings%20qualitatively%20or%20quantitatively.). Manual process of citation screening involves two reviewers manually screening the searched studies using some "inclusion" and "exclusion" criteria. If the study passes the "inclusion" criteria, it is included for further analysis or is excluded. As apparant through manual screening process, we consider citation screening as a binary classification problem whereby any ML (machine learning) classifier could be trained to separate the searched studies into these two classes (__include__ and __exclude__).

The input data used for citation screening could be found [here](https://drive.google.com/file/d/14_-NNapaA2SvAxekAAW55zSZo9jSToVN/view?usp=sharing). This dataset was manually labelled into __include__ and __exclude__ by Hilfiker _et al._. The file consists of 25,540 data samples, with each data sample separated by a new line. It is a tab separated file and the data in it is structured as follows. 


| Title         | PMID          | Abstract text  | Class  | MeSH terms (separated by a pipe __"&#124;"__) |
| ------------- |--------------:| :-------------:| ------:|----------------------------------------------:|
| Structured exercise improves physical functioning in women with stages I and II breast cancer: results of a randomized controlled trial.      | 11157015 | Abstract PURPOSE: Self-directed and supervised exercise were compared with usual care in a clinical trial designed to evaluate the effect of structured exercise on physical functioning and other dimensions of health-related quality of life in women with stages I and II breast cancer. PATIENTS AND METHODS: One hundred twenty-three women with stages I and II breast cancer completed baseline evaluations of generic and disease- and site-specific health-related quality of life, aerobic capacity, and body weight. Participants were randomly allocated to one of three intervention groups: usual care (control group), self-directed exercise, or supervised exercise. Quality of life, aerobic capacity, and body weight measures were repeated at 26 weeks... | _"include"_ or _"exclude"_ | Clinical Trial &#124;Comparative Study &#124;Randomized Controlled Trial &#124;Research Support, Non-U.S. Gov't &#124;Antineoplastic Combined Chemotherapy Protocols &#124;Breast Neoplasms &#124;Breast Neoplasms &#124;Breast Neoplasms &#124;Chemotherapy, Adjuvant &#124;Exercise &#124;Female &#124;Humans &#124;Middle Aged &#124;Neoplasm Staging &#124;Quality of Life &#124;Radiotherapy, Adjuvant |

If you use this dataset in your research, please cite our papers,

```
% 32570395 
@Article{pmid32570395,
   Author="Dhrangadhariya, A.  and Hilfiker, R.  and Schaer, R.  and M?ller, H. ",
   Title="{{M}achine {L}earning {A}ssisted {C}itation {S}creening for {S}ystematic {R}eviews}",
   Journal="Stud Health Technol Inform",
   Year="2020",
   Volume="270",
   Pages="302--306",
   Month="Jun"
}
% 28501804 
@Article{pmid28501804,
   Author="Hilfiker, R.  and Meichtry, A.  and Eicher, M.  and Nilsson Balfe, L.  and Knols, R. H.  and Verra, M. L.  and Taeymans, J. ",
   Title="{{E}xercise and other non-pharmaceutical interventions for cancer-related fatigue in patients during or after cancer treatment: a systematic review incorporating an indirect-comparisons meta-analysis}",
   Journal="Br J Sports Med",
   Year="2018",
   Volume="52",
   Number="10",
   Pages="651--658",
   Month="May"
}

```
