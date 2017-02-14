# PaperReading
## Question Answering

### [Question Answering](https://github.com/ECNUICA/PaperReading/tree/master/Question%20Answering)
- Siamese Recurrent Architectures
  - [AAAI16]Siamese Recurrent Architectures for Learning Sentence Similarity.pdf  
  1)Using a simple adaptation of the LSTM to learn a highly struc-tured space of sentence-representations.  
  2)Using a simple Manhattan metric to measure the similarity.
- Attention Mechanism
  - [ACL16] Inner Attention based Recurrent Neural Networks for Answer Selection.pdf  
  1) In the RNN architecture, those hidden states near the end of the sentence are expected to capture more information.  
  2) The near-the-end hidden variables will be more attended, which may result in a biased attentive weight.  
  - [ACL16] Deep Fusion LSTMs for Text Semantic Matching.pdf  
  1) Use soft attention mechanism to obtain the representation of one sentence by depending on representation of another sentence  
  2) Build the interaction at different granularity (word, phrase and sentence level)  
- Reading Comprehension
  - [ICLR17UnderReview] LEARNING RECURRENT SPAN REPRESENTATIONS FOR EQA.pdf  
  Effciently builds fixed length representations of all spans in the evidence document with a recurrent network.  
  - [ICLR17UnderReview] DYNAMIC COATTENTION NETWORKS.pdf
  The DCN first fuses co-dependent representations of the question and the document in order to focus on relevant parts of both. Then a dynamic pointing decoder iterates over potential answer spans.  
  - [arXiv16] End-to-End Answer Chunk Extraction and Ranking for Reading Comprehension.pdf  
  Extract and Rank a set of answer candidates from a given document to answer questions.
