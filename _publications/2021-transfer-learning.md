---
title: "Transfer Learning Application for Berries Yield Forecasting using Deep Learning"
collection: publications
category: conferences
permalink: /publication/2021-transfer-learning
excerpt: "To overcome the computational complexity of retraining Deep Learning (DL) yield forecasting models for each type of Fresh Produce (FP), it is necessary to have a generalization of the models' application to similar FP. This can be done by transferring the learning among similar FP with minimal retraining. Hence, Transfer Learning (TL) is used in this work amongst berries which are similar in nature. First, the proposed DL model is trained using station-based data and satellite images as inputs mapped to the strawberry yield as output. The weights obtained from this learning are transferred to the raspberry yield forecasting model since raspberry and strawberry yields are similar and are both planted in California. The proposed model is an ensemble of two models: the station-based ensemble model (ATT-CNN-LSTM-SeriesNet_Ens) with its compound DL components, SeriesNet with Gated Recurrent Unit (GRU) and Convolutional Neural Network LSTM with Attention layer (Att-CNN-LSTM); trained and tested using station-based data as input and the corresponding strawberry yields as output. Second, the remote sensing ensemble model (SIM_CNN-LSTM_Ens), which is an ensemble of Convolutional Neural Network LSTM (CNN-LSTM) models; trained and tested using satellite images as input mapped to the same yields as output. The weights obtained are transferred to the raspberry yield forecasting ensemble model with minimal retraining. It is found that the voting ensemble improves performance by 27% compared to the best performing component model. Based on an aggregated measure, the performance obtained from TL is comparable to that obtained by training the models on the raspberry data without TL, while having around 55 % reduction in processing time."
date: 2021-07-18
venue: 'International Joint Conference on Neural Networks (IJCNN)'
paperurl: 'https://ieeexplore.ieee.org/document/9533530'
citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font.
