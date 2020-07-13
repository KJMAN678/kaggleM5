参加したkaggleのコンペ　M5 Forecasting - Accuracy
　https://www.kaggle.com/c/m5-forecasting-accuracy  

分析系のコミュニティ、データラーニングギルドのメンバー3名とともに参加  
　https://data-learning.com/guild  
  https://www.kaggle.com/c/m5-forecasting-accuracy/team  

工夫したこと
　・学習用のデータが3つ合計で約400MBと重いため、データのbit数を下げる、メモリ解放を行う等のメモリーエラー対策を行った  
　・加工した学習用データをpickle に保存。機械学習モデルを回しなおすときは保存したpickleを読み込むことで学習データの再加工する手間を省略した  
  ・lightGBM、XGBoost、CatBoostのアンサンブルを実施  
