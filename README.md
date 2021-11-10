[![View Electrophysiology-Tutorial-for-Neuroscience_jp on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://jp.mathworks.com/matlabcentral/fileexchange/93365-electrophysiology-tutorial-for-neuroscience_jp)
# Electrophysiology-Tutorial-for-Neuroscience_jp
This repository contains a Japanese version of a published repository "Electrophysiology tutorial for neuroscience" by Shubo Chakrabarti https://github.com/MathWorks-Teaching-Resources/Electrophysiology-Tutorial-for-Neuroscience

# Livescriptの内容はこちら
Electrophysiology_Tutorial_for_Neuroscience_jp.mlxの内容をマークダウン形式に変換したものはこちらです。  
https://github.com/mathworks/Electrophysiology-Tutorial-for-Neuroscience_jp/blob/main/Electrophysiology_Tutorial_for_Neuroscience_jp.md

# 神経科学分野における電気生理学チュートリアル
ELECTROPHYSIOLOGY TUTORIAL FOR NEUROSCIENCE

このファイルは、電気生理学実験で記録された神経活動を解析する神経科学者に向けたMATLABのチュートリアルです。脳に挿入した電極から記録された信号だけではなく、EEGやECoGも当てはまります。

このチュートリアルでは、すでに記録されたデータの一部を利用し、神経活動解析についての基本的な概念についてひとつづつ学んでいきます。タイムテーブルの使い方、フィルタリング、ガウス混合モデルによるPCA, パワースペクトルと時間周波数解析（スペクトグラム）を扱います。

解析のステップをプログラミングで行うほか、信号アナライザーアプリも紹介しています。  

このチュートリアルを走らせるにあたって、neural_data.matというファイルが必要です。（訳者注：リポジトリに含まれています。）

このチュートリアルには以下のものが必要です。
1. MATLAB, the Signal Processing and the Statistics and Machine Learning Toolboxes. 大学や研究機関のライセンスがあればアクセスできますが、無料の評価版はこちらからダウンロードできます。https://www.mathworks.com/campaigns/products/trials.html
2. neural_data.mat ライブスクリプトのフォルダに同梱されています。

手持ちのデータでこのチュートリアルをやってみる場合、以下の手順を行ってください。
1. neural_data.matをコピーして別の名前で保存する
2. 以下2つの変数を持つneural_data.matを、自分のデータで作成する
    a. data: 記録された電圧値である数値型 (numeric array) 
    b. fs: Hz単位のサンプリング周波数を表すスカラー

このチュートリアルは、Shubo Chakrabartiによって作成されたものであり、Megumi Fukuda(megumif@mathworks.com)が日本語に翻訳しました。基本的には逐語訳ですが、一部言葉を補ったり、原文の意を損なわない程度に意訳している部分もあります。参考情報、MATLABスクリプト内の変数名やコメントなどは、基本的には原文のまま残してあります。
英語版のリポジトリはこちらです。
https://github.com/MathWorks-Teaching-Resources/Electrophysiology-Tutorial-for-Neuroscience
