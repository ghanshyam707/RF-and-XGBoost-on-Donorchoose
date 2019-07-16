# RF-and-XGBoost-on-Donorchoose
Applied ensemble models random forest and XGBoost on DonorChoose Dataset

I have created 4 dataset. Each dataset contains text features encoded with different encoding techniques.<br>
**Set1** | Text features encoded with simple `Bag of words` vectorizer.<br>
**Set2** | Text Features encoded with `TFIDF` vectorizer.<br>
**Set3** | Text features encoded with `Avarage Word2Vec` vectorizer.<br>
**Set4** | Text features encoded with `TFIDF Word2Vec` vectorizer.<br>

Then `Random Forest` and `XGBoost` is applied on all 4 datasets.<br>

<b> Conclusion after applying `RF` and `XGBoost` to all datasets </b><br>

`XGBoost` has highest AUC score of 0.74 for test dataset and 0.79 for train datasets with tree depth equals to 2 and 200 estimators.
Other models are overfitting on the datasets

##### Credits : www.AppliedAICourse.com
