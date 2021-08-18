# Click-BERT
Click-BERT: Clickbait Detector with Bidirectional Encoder Representations from Transformers

Course Project for [EECS 498 NLP, Winter 2021](https://web.eecs.umich.edu/~wangluxy/courses/eecs498_wn2021/eecs498_wn2021.html)

Team Members: Changyuan Qiu ([@PeterQiu0516](https://github.com/PeterQiu0516)), Chenshu Zhu ([@Jupiter](https://github.com/jupiterepoch)), Haoxuan Shan ([@shanhx2000](https://github.com/shanhx2000))

## Abstract
Clickbait is a rampant problem haunting online readers.
Nowadays, clickbait detection in tweets remains an
elusive challenge. In this paper, we propose Clickbait
Detector with Bidirectional Encoder Representations from
Transformers (Click-BERT), which could effectively identify
clickbaits utilizing recent advances in pre-training methods
(BERT and Longformer) and recurrent neural networks (Bi-
LSTM and Bi-GRU) with a parallel model structure. Our
model supports end-to-end training without involving any
hand-crafted features and achieved new state-of-the-art results
on the [Webis 17 Dataset](https://webis.de/data/webis-clickbait-17.html).


## Highlights
* Click-BERT won the best presentation award among 17 teams!
![](Presentation/best_presentation_award.png)

* [Final Report](Final-Report/EECS498NLP_Project_Final_Report.pdf) released.

* [Presentation Slides](Presentation/15_Click-BERT%20-%20Clickbait%20Detector%20with%20Bidirectional%20Encoder%20Representations%20from%20Transformers.pdf) released.

  
* Our baseline2: *headline Bi-LSTM with BERT* achieved new SOTA on accuracy and MSE on Webis 17! Get more details in our [progress report](https://github.com/PeterQiu0516/CARE-BERT/blob/main/Progress-Report/EECS498NLP-Project-Progress-Report.pdf).
