# Fuzzy Intrusion Detection System

Introduction:
In today’s highly connected digital world, protecting computer networks from malicious activities is more critical than ever. Intrusion Detection Systems (IDS) act as the first line of defense by identifying suspicious activities in network traffic. Traditional IDS approaches—especially signature-based systems—struggle to detect unknown attacks and often suffer from high false alarm rates.

To overcome these limitations, this project applies Fuzzy Logic, an intelligent decision-making system inspired by human reasoning, to build a more adaptable and robust IDS. Fuzzy logic allows the system to handle imprecise, uncertain, or vague inputs—a common scenario in network behavior.

Dataset used:

| Limitation                                   | Found in Paper | My Improvement                                        |
| -------------------------------------------- | -------------- | ----------------------------------------------------- |
| No fuzzy rule matrix                         | Both papers    | Created 9–27 rules based on expert logic              |
| No membership function parameters or shapes  | Both           | Defined `trimf` and `gaussmf` MFs in MATLAB           |
| No implementation or source code             | Both           | Full MATLAB `.fis` and `.m` files provided            |
| Only conceptual or outdated dataset (KDD 99) | Both           | Used **NSL-KDD** for better generalization            |
| No performance metric graphs                 | Both           | Evaluated using Accuracy, Precision, Recall, F1-score |
| No GUI or surface visualizations             | Both           | Added Rule Viewer, Surface Viewer, MF plots           |


| Reason                       | Benefit                                                                  |
| -----------------------------| ------------------------------------------------------------------------ |
|   Stronger Literature Review | Shows you've surveyed multiple sources                                   |
|   Builds Credibility         | Recruiters and reviewers see you're improving upon peer-reviewed work    |
|   Highlights Research Depth  | You show understanding of previous limitations and add value             |
|    Justifies Your Design     | You’re not making design decisions arbitrarily — they’re evidence-backed |

References
This project is inspired by two academic papers that propose fuzzy logic-based models for intrusion detection:

JETIR Paper:
Muhamed Jamshir M, Ajeesha M I.
“Fuzzy Logic for Intrusion Detection System”, JETIR, Vol. 7, Issue 12, Dec 2020.
https://www.jetir.org/papers/JETIR2012322.pdf

ResearchGate Paper:
Mukkamala S., Sung A. H., Abraham A.
"Network Intrusion Detection System using Fuzzy Logic", 2011.
https://www.researchgate.net/publication/50417996_Network_Intrusion_Detection_System_using_Fuzzy_Logic/link/0e5f77a2f0c4c08778ffbf59/download?_tp=eyJjb250ZXh0Ijp7InBhZ2UiOiJwdWJsaWNhdGlvbiIsInByZXZpb3VzUGFnZSI6bnVsbH19
