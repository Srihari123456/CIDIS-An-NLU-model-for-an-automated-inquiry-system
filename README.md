# A Concurrent Intelligent Natural Language Understanding Model for an Automated Inquiry System

- The work is intended to tackle a vital field that lies at the intersection of speech processing and natural language processing: Spoken Language Understanding (SLU).
- Its idea is to understand the essence of machine-directed human speech to facilitate its further processing and take on board its cognitive impact.
- The proposed system is <b><i>CIDIS - Concurrent Intelligent Model for Dialogue Act Classification, Intent Detection, and Slot Filling</b></i>, which uses a deep concurrent multi-task paradigm to perform the three fundamental tasks of the SLU domain: Dialogue Act Classification, Intent Detection and Slot Filling.
- Since the model is orchestrated in a multi-task fashion, every task interacts with the other to have a global understanding of the input query.
- It follows an intelligent encoding strategy involving concatenation of the query’s BERT and CharCNN embedding to handle all possible edge cases and ambiguities involved in human speech queries.
- This intelligent encoding is passed through a Stacked Bi-LSTM architecture followed by task-specific attention layers.
- The three supplementary outputs are in turn fed to the final module that generates the expected query response in real-time based on the dialogue act, intent, and slot.
- The developed models are evaluated against standard benchmark datasets like ATIS, TRAINS, and FRAMES and the achieved state-of-the-art performances are eventually tabulated.

- This work has been presented at the 2022 IEEE World Conference on Applied Intelligence and Computing and is accessible at <a href="https://ieeexplore.ieee.org/abstract/document/9848883"> [Link to Paper] </a> 
  
![image](https://github.com/Srihari123456/CIDIS-An-NLU-model-for-an-automated-inquiry-system/assets/43612273/a314e4ad-8282-4181-b4ae-8bffcb640afe)
