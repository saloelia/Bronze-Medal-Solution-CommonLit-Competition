# Bronze-Medal-Solution-CommonLit-Competition
Thie repository provides my solution for the Kaggle Competition - CommonLit - Evaluate Student Summaries. The goal of the competition was to assess the quality of summaries written by students in grades 3-12, and by that assist teachers in evaluating the quality of student work and help learning platforms provide immediate feedback to students. 

My solution was based on combining an ensemble of transformers (deberta-v3-large, XLM-roberta-large, all-mpnet-base, funnel-medium-base) which were trained on the summaries dataset, alongside training an LGBM model on a constructed dataset of NLP engineered features.  Out of 2063 participants, I achieved the 155th position with a RMSE score of 0.48121.

Notebooks descriptions:
- CommonLit - Sheet1.csv - Table results of all experiments and training I performed.
- Augmentation_CommonLit - Used for creating augmentation for the data (did not improved the results however).
- Inference_CommonLit - Used for evaluating the Transformer with the LGBM after training.
- Meassure_CV - Used for performing Cross Validation.
- commonlit_ridge_ensebmle - Used for evaluate variety of ensemble methods (the best one was the regular ensebmle).
- final-inference-ensemble - The final notebook submitted to the Kaggle competition.
- train_debertav3_CV - Used for both training Transformers and Evaluate them with the LGBM using Cross Validation.
- training_transformer_CV - Used for training Transformers only and save their results and weigths.
