# Portfolio
最終更新日: 2024/5/8  

## スキル
①言語  
* Python  
データ分析、機械学習、深層学習、ファイルやフォルダの操作、簡単なアプリ開発  
【使用経験のあるフレームワークやライブラリ】  
os, glob, shutil, re, pandas, numpy, matplotlib, seaborn, plotly, scipy, scikit-learn, Pytorch, prophet, YOLOv8, OpenCV, Transformers, Streamlit, shap

* SQL  
Googleデータアナリティクスプロフェッショナル認定で基礎を学習  
BigqueryからSQLを用いてデータの抽出し、GoogleColab上でPythonを用いて分析した経験有  
  
* R  
Googleデータアナリティクスプロフェッショナル認定で基礎を学習  
【使用経験のあるパッケージ】  
tidyverse, gglot2  

②開発ツール  
* Git, GitHub  
アプリ開発はGitの環境下で行い、ブランチを切って、アプリに機能を追加しています。  

* Linux  
基本コマンド  
アクセス権限の変更  
ファイルのバッシュ化  
シェルスクリプト（学習中）  
  
* AWS（学習中）

## 資格
* SolidWorks認定試験（CSWA）(2019年11月取得)  
* 日商簿記2級(2022年5月取得)  
* GoogleDataAnalyticsProfessional認定(2024年4月取得)  
<a href="https://www.credly.com/earner/earned/badge/a39e18db-7d5b-49a8-b266-4d47a473af6c">
  <img src="./badge.png" alt="認定バッジ">
</a>
   
* GoogleCyberSecurityProfessional認定（2024年5月取得）
<a href="https://www.credly.com/earner/earned/badge/8a26f25a-b826-4a1b-94b5-71bab22736f7">
  <img src="./budge2.png" alt="認定バッジ">
</a>



## 取り組んだ分析課題
### 機械学習を用いた分類
ROC AUCスコアが0.81で、再現率と適合率が比較的高いCatboostモデルを構築しました。また、特徴量の重要度をSHAP分析を用いて可視化しました。 そして、分析結果をStreamlitを用いてアプリ化しました。  
  
<a href="https://portfoliotitanic-gj5ulajyurszafogejxgzl.streamlit.app/" target="_blank">機械学習を用いたタイタニック号乗客の生存確率分析</a>  
  
<a href="https://www.kaggle.com/code/yuukiiwakura/classifier-by-catboost" target="_blank">Kaggle分析ノートブック</a>  
  
<a href="https://www.kaggle.com/competitions/titanic" target="_blank">データの出典元</a> 



### 機械学習を用いた回帰
RSMEスコアが0.055で比較的精度が高いLightgbmモデルを構築しました。また、特徴量の重要度をSHAP分析を用いて可視化しました。そして、分析結果をStreamlitを用いてアプリ化しました。  
  
<a href="https://portfoliohouseprice-fo9ulyssetjkjiappnpywxw.streamlit.app/" target="_blank">機械学習による米国住宅価格の予測</a>  
  
<a href="https://www.kaggle.com/code/yuukiiwakura/regressoin-by-lightgbm" target="_blank">Kaggle分析ノートブック</a>  
  
<a href="https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques" target="_blank">データの出典元</a> 



### 深層学習を用いた画像分類
PyTorchを使用してオリジナルの畳み込みニューラルネットワークを構築し、画像分類を行いました。モデルの精度は77.5%で、結果をStreamlitで可視化しました。  
  
<a href="https://portfoliodogscats-hbvehhzihycnxdplnrxzu4.streamlit.app/" target="_blank">オリジナルニューラルネットワークによる猫と犬の画像分類</a>  
  
<a href="https://www.kaggle.com/code/yuukiiwakura/2-class-classification-using-pytorch-original-cnn" target="_blank">Kaggle分析ノートブック</a>  
  
<a href="https://www.kaggle.com/competitions/dog-vs-cat-classification" target="_blank">データの出典元</a> 


  
### 転移学習を用いた画像分類
PyTorchのDenseNetを用いた転移学習による画像分類を行い、精度は89.8%でした。結果はStreamlitで可視化しました。  
  
<a href="https://flowerclassification-mudkpi47dcealenst7iynq.streamlit.app/" target="_blank">転移学習による花の画像の分類</a>  
  
<a href="https://www.kaggle.com/code/yuukiiwakura/5-class-classification-using-pytorch-densenet" target="_blank">Kaggle分析ノートブック</a>  
  
<a href="https://www.kaggle.com/datasets/alxmamaev/flowers-recognition" target="_blank">データの出典元</a> 



### YOLOv8を用いた物体検出
・YOLOv8を用いて画像と映像から物体検出を行うアプリを開発しました。  
・検出対象は3つで、2つの検出でmAP=約0.9という高い精度を実現しました。  
・結果をStreamlitでアプリ化し、ブラウザ上で簡単に操作できます。  
  
<a href="https://helmetv2-jipzd9znb5yip8xmza8wfu.streamlit.app/" target="_blank">ヘルメット着用促進システム</a>  
  
下記のリンクから動画検出も含めたアプリに飛べますが、環境によっては動画が再生されない可能性があります。  
因みに、windowsのブラウザでは動画を再生できませんでした。一方で、iphone環境では動画を再生することができました。  
アプリで動画を確認できない方は分析結果報告スライドのfig06を確認ください。  
  
<a href="https://helmetv2-kppnytbjth5qe8udrcjohh.streamlit.app/" target="_blank">ヘルメット着用促進システム(映像検出結果付)</a>  
  
<a href="https://docs.google.com/presentation/d/1tLZ4_f5EMZsqNUVD2tdCjxSMs35r3YLRnNA95BSTrb0/edit#slide=id.p" target="_blank">分析結果報告スライド</a>  
  
<a href="https://public.roboflow.com/object-detection/hard-hat-workers" target="_blank">データの出典元①</a>  
  
<a href="https://pixabay.com/ja/videos" target="_blank">データの出典元②</a>  



### 自然言語処理
BERTをPeftでファインチューニングを行い、自然言語分類モデルを構築しました。モデルはF1スコア0.91を達成し、再現率と適合率のバランスが良い結果となりました。  
  
<a href="https://www.kaggle.com/code/yuukiiwakura/fine-tuning-bert-with-peft-for-text-classification/edit" target="_blank">Kaggle分析ノートブック</a>  

<a href="https://www.kaggle.com/datasets/eswarchandt/amazon-music-reviews" target="_blank">データの出典元</a>  



### GoogleDataAnalyticsProfessional認定最終課題（ケーススタディ）
<a href="https://docs.google.com/presentation/d/1yJ9RSdGBTQlT9GvQKLMHq5cAHBwVKtG39ImytjGriBU/edit#slide=id.p" target="_blank">分析結果報告スライド</a>  

<a href="https://www.kaggle.com/code/yuukiiwakura/casestudy" target="_blank">Kaggle分析ノートブック</a>  

<a href="https://www.kaggle.com/datasets/arashnic/fitbit" target="_blank">データの出典元</a>  
