# DACON-subscription
https://dacon.io/competitions/official/236179/overview/description

## 2023.12.04 - 2023.12.11


## private leaderboard 24위 (10%)
<img width="934" alt="image" src="https://github.com/kelly062001/DACON-subscription/assets/121388824/7b63eaa2-55ae-481d-a91d-5d806f822761">


## public leaderboard 34위 (10%)
<img width="904" alt="image" src="https://github.com/kelly062001/DACON-subscription/assets/121388824/7c214b3a-f727-45df-88b8-a603c7b77c0a">


## 내용

|File_name|MODEL |validation set|test set|제출(public score)
|:---:|:------:|:--------------:|:--------:|:-----------------:|
|1207|모든 feature + optuna |0.766||0.3815|
|**1208_1**|**feature 2개 + DecisionTree**|**0.6229**|**0.6169**|**0.5329**|
|1209_1|feature 2개 + RandomForest |0.6684|0.6622|0.5094|
|1209_2|data_scaling + 모든 feature + RandomForest|0.7270|0.7327|0.4606|
|1209_3|feature_importance 중요도 순으로 feature 개수 조정 + catboost|0.7599|0.7586|0.3987|
|1210_3|feature best 1st + data_scaling+catboost|0.7599|0.7357|제출 x|
|1210_1|feature best 2nd + data_scaling+catboost|0.7491|0.7473|제출 x|
|1210_2|feature best 3rd + data_scaling+catboost|0.7445|0.7357|제출 x|
|1210_4|optuna+feature best 2nd +catboost|0.6213|0.6316|0.5217|
|1210_5|data_scaling + optuna + feature best 2nd + catboost|0.6315|0.6334|0.5250|
|1210_5|optuna+feature best 3rd +catboost|0.7392|0.7434|0.4280|
|1210_6|data_scaling + optuna + feature best 3rd + catboost|0.6395|0.6298|0.5221|



