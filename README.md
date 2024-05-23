# Portfolio
最終更新日: 2024/5/24 

# スキル
①言語  
* Python  
データ分析、機械学習、深層学習、ファイルやフォルダの操作、簡単なアプリ開発  
【使用経験のあるフレームワークやライブラリ】  
os, glob, shutil, re, Pandas, Numpy, scipy, matplotlib, seaborn, plotly, scikit-learn, LightGBM, Catboost, Pytorch, Prophet, YOLOv8, OpenCV, Transformers, Peft, Streamlit, SHAP, LangChain  
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

# 資格
* SolidWorks認定試験（CSWA）(2019年11月取得)
* 日本情報処理検定 表計算2級(2022年2月取得)  
* 日商簿記2級(2022年5月取得)  
* GoogleDataAnalyticsProfessional認定(2024年4月取得)  
<a href="https://www.credly.com/earner/earned/badge/a39e18db-7d5b-49a8-b266-4d47a473af6c">
  <img src="google1.png" alt="認定バッジ">
</a>
   
* GoogleCyberSecurityProfessional認定（2024年5月取得）
<a href="https://www.credly.com/earner/earned/badge/8a26f25a-b826-4a1b-94b5-71bab22736f7">
  <img src="google2.png" alt="認定バッジ">
</a>



# 取り組んだ課題

## 構造化データの分析
### 機械学習を用いた分類
ROC AUCスコアが0.81で、再現率と適合率が比較的高いCatboostモデルを構築しました。また、特徴量の重要度をSHAP分析を用いて可視化しました。 そして、分析結果をStreamlitを用いてアプリ化しました。  
  
[機械学習を用いたタイタニック号乗客の生存確率分析](https://portfoliotitanic-gj5ulajyurszafogejxgzl.streamlit.app/)  

[Kaggle分析ノートブック](https://www.kaggle.com/code/yuukiiwakura/classifier-by-catboost)  

[データの出典元](https://www.kaggle.com/competitions/titanic)  

### 機械学習を用いた回帰
RSMEスコアが0.055で比較的精度が高いLightgbmモデルを構築しました。また、特徴量の重要度をSHAP分析を用いて可視化しました。そして、分析結果をStreamlitを用いてアプリ化しました。  
  
[機械学習による米国住宅価格の予測](https://portfoliohouseprice-fo9ulyssetjkjiappnpywxw.streamlit.app/)  
  
[Kaggle分析ノートブック](https://www.kaggle.com/code/yuukiiwakura/regressoin-by-lightgbm)  
  
[データの出典元](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)  


  
## 非構造化データの分析(画像分類)
### 深層学習を用いた画像分類
PyTorchを使用してオリジナルの畳み込みニューラルネットワークを構築し、画像分類を行いました。モデルの精度は77.5%で、結果をStreamlitで可視化しました。  
  
[オリジナルニューラルネットワークによる猫と犬の画像分類](https://portfoliodogscats-hbvehhzihycnxdplnrxzu4.streamlit.app/)  

[Kaggle分析ノートブック](https://www.kaggle.com/code/yuukiiwakura/2-class-classification-using-pytorch-original-cnn)  

[データの出典元](https://www.kaggle.com/competitions/dog-vs-cat-classification)  
  
### 転移学習を用いた画像分類
PyTorchのDenseNetを用いた転移学習による画像分類を行い、精度は89.8%でした。結果はStreamlitで可視化しました。  
  
[転移学習による花の画像の分類](https://flowerclassification-mudkpi47dcealenst7iynq.streamlit.app/)  

[Kaggle分析ノートブック](https://www.kaggle.com/code/yuukiiwakura/5-class-classification-using-pytorch-densenet)  

[データの出典元](https://www.kaggle.com/datasets/alxmamaev/flowers-recognition)  
  
## 非構造化データの分析(物体検出)
### ヘルメット着用促進システム
・YOLOv8を用いて画像と映像から物体検出を行うアプリを開発しました。  
・検出対象は3つで、2つの検出でmAP=約0.9という高い精度を実現しました。  
・結果をStreamlitでアプリ化し、ブラウザ上で簡単に操作できます。  
  
[ヘルメット着用促進システム](https://helmetv2-jipzd9znb5yip8xmza8wfu.streamlit.app/)  
  
下記のリンクから動画検出も含めたアプリにアクセスできますが、環境によっては動画が再生されない可能性があります。  
因みに、Windowsのブラウザでは動画を再生できませんでした。一方で、iphone環境では動画を再生することができました。  
アプリで動画を確認できない方は分析結果報告スライドのfig07をご確認ください。  
  
[ヘルメット着用促進システム(映像検出結果付)](https://helmetv2-kppnytbjth5qe8udrcjohh.streamlit.app/)  

[分析結果報告スライド](https://docs.google.com/presentation/d/1tLZ4_f5EMZsqNUVD2tdCjxSMs35r3YLRnNA95BSTrb0/edit#slide=id.p)  

[データの出典元①](https://public.roboflow.com/object-detection/hard-hat-workers)  

[データの出典元②](https://pixabay.com/ja/videos)  
  
### XML形式からYOLOv8形式への変換アルゴリズムの習得  
* この分析はxmlファイルで提供されたannotation情報をYOLOv8モデルに入力できる形式に変更することを目的に行いました。  
* ファイルの形式を変更してYOLOv8モデルに入力してモデルを学習させることができました。  
* 精度はあまりよくなく、mAP=0.49という結果でした。  
* mAPが学習の途中から上昇しなくなったので過学習を起こしている可能性があると考察しました。  
* 過学習を起こさないためのモデルの詳細な設定などはまだ習得できていないのでこれから勉強していきたいです。  

[Kaggle分析ノートブック](https://www.kaggle.com/code/yuukiiwakura/objectdetection-using-yolov8)  

[データの出典元](https://www.kaggle.com/datasets/anamibnjafar0/flamevision)  
  
### COCO形式からYOLOv8形式への変換アルゴリズムの習得  
* annotation情報をCOCO形式からyolo形式に変更してYOLOv8に学習させる課題

[GitHubリポジトリ](https://github.com/gan0606/shellfish_v2)  

[データの出典元](https://public.roboflow.com/object-detection/shellfish-openimages)  
  
### CSV形式からYOLOv8形式への変換アルゴリズムの習得
* annotation情報をcsv形式からyolo形式に変更してYOLOv8で学習させる課題

[GitHubリポジトリ](https://github.com/gan0606/car)  

[データの出典元](https://www.kaggle.com/datasets/sshikamaru/car-object-detection)  
  
## 非構造化データの分析(自然言語処理)
### Transformersを用いたテキスト分類
BERTをPeftでファインチューニングを行い、自然言語分類モデルを構築しました。モデルはF1スコア0.91を達成し、再現率と適合率のバランスが良い結果となりました。  

[Kaggle分析ノートブック](https://www.kaggle.com/code/yuukiiwakura/fine-tuning-bert-with-peft-for-text-classification)  

[データの出典元](https://www.kaggle.com/datasets/eswarchandt/amazon-music-reviews)  
  
### LangChainを用いたAI心理カウンセラーの開発
LangChainとStreamlitを用いて、ChatBot形式のAI心理カウンセラーを開発ました。  
このアプリケーションは、2つの目的で開発しました。  
1つ目は、プロンプトエンジニアリングを学習することです。  
2つ目は、就労移行支援事業所の支援員の方たちのAIアシスタントを作ることです。  
支援員の方たちは「面白くて、実用的です。」と言ってくださいました。
  
[AI心理カウンセラー](https://langchainaicounselor-mfxzfyjblqvj2xpd5cpzzu.streamlit.app/)


## GoogleProfessional認定ケーススタディー
### GoogleDataAnalyticsProfessional認定最終課題
[分析結果報告スライド](https://docs.google.com/presentation/d/1yJ9RSdGBTQlT9GvQKLMHq5cAHBwVKtG39ImytjGriBU/edit#slide=id.p)  

[分析ノートブック](https://www.kaggle.com/code/yuukiiwakura/casestudy)  

[データの出典元](https://www.kaggle.com/datasets/arashnic/fitbit)  
