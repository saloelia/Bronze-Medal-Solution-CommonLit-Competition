# Bronze-Medal-Solution-CommonLit-Competition
Thie repository provides my solution for the Kaggle Competition - CommonLit - Evaluate Student Summaries. The goal of the competition was to assess the quality of summaries written by students in grades 3-12, and by that assist teachers in evaluating the quality of student work and help learning platforms provide immediate feedback to students. 

My solution was based on combining an ensemble of transformers (deberta-v3-large, XLM-roberta-large, all-mpnet-base, funnel-medium-base) which were trained on the summaries dataset, alongside training an LGBM model on a constructed dataset of NLP engineered features.  Out of 2063 participants, I achieved the 155th position with a RMSE score of 0.48121.
