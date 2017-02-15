# PaperReading

## Ref
- [AAAI 2017 accepted-papers](http://www.aaai.org/Conferences/AAAI/2017/aaai17accepted-papers.pdf)
- [http://nlp.stanford.edu/read/](http://nlp.stanford.edu/read/)
- [https://arxiv.org/list/cs.CL/recent](https://arxiv.org/list/cs.CL/recent)
- [http://aclweb.org/anthology/](http://aclweb.org/anthology/)  
## Question Answering

### [Question Answering](https://github.com/ECNUICA/PaperReading/tree/master/Question%20Answering)
- Siamese Recurrent Architectures
  - [AAAI16][Siamese Recurrent Architectures for Learning Sentence Similarity.pdf](https://github.com/ECNUICA/PaperReading/blob/master/Question%20Answering/1-AAAI16-Mueller-Siamese%20Recurrent%20Architectures%20for%20Learning%20Sentence%20Similarity.pdf)  
  1)Using a simple adaptation of the LSTM to learn a highly struc-tured space of sentence-representations.  
  2)Using a simple Manhattan metric to measure the similarity.
- Attention Mechanism
  - [ACL16] [Inner Attention based Recurrent Neural Networks for Answer Selection.pdf](https://github.com/ECNUICA/PaperReading/blob/master/Question%20Answering/3-ACL16-CAS-Inner%20Attention%20based%20Recurrent%20Neural%20Networks%20for%20Answer%20Selection.pdf)  
  1) In the RNN architecture, those hidden states near the end of the sentence are expected to capture more information.  
  2) The near-the-end hidden variables will be more attended, which may result in a biased attentive weight.  
  - [ACL16] [Deep Fusion LSTMs for Text Semantic Matching.pdf](https://github.com/ECNUICA/PaperReading/blob/master/Question%20Answering/4-ACL16-FDU-Deep%20Fusion%20LSTMs%20for%20Text%20Semantic%20Matching.pdf)  
  1) Use soft attention mechanism to obtain the representation of one sentence by depending on representation of another sentence  
  2) Build the interaction at different granularity (word, phrase and sentence level)  
- Reading Comprehension
  - [ICLR17UnderReview] [LEARNING RECURRENT SPAN REPRESENTATIONS FOR EQA.pdf](https://github.com/ECNUICA/PaperReading/blob/master/Question%20Answering/5-ICLR17UnderReview-LEARNING%20RECURRENT%20SPAN%20REPRESENTATIONS%20FOR%20EQA.pdf)  
  Effciently builds fixed length representations of all spans in the evidence document with a recurrent network.  
  - [ICLR17UnderReview] [DYNAMIC COATTENTION NETWORKS.pdf](https://github.com/ECNUICA/PaperReading/blob/master/Question%20Answering/6-ICLR17UnderReview-DYNAMIC%20COATTENTION%20NETWORKS.pdf)  
  The DCN first fuses co-dependent representations of the question and the document in order to focus on relevant parts of both. Then a dynamic pointing decoder iterates over potential answer spans.  
  - [arXiv16] [End-to-End Answer Chunk Extraction and Ranking for Reading Comprehension.pdf](https://github.com/ECNUICA/PaperReading/blob/master/Question%20Answering/7-arXiv16-IBM-Waston-End-to-End%20Answer%20Chunk%20Extraction%20and%20Ranking%20for%20Reading%20Comprehension.pdf)  
  Extract and Rank a set of answer candidates from a given document to answer questions.
