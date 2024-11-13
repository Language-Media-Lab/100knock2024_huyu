# 100knock2024_huyu

# 言語処理100本ノック 2024年度 冬
言語メディア研2024年度B3向け勉強会として、言語処理100本ノックに取り組みます。  
教材URL: https://nlp100.github.io/ja/  

毎週全員1章分（10問）解いてください。(※ただし2章と10章は除く)  
勉強会のときに毎週1人1章分、自分のコードを説明してもらいます。  
11月14日から開始します  

# Githubについて
基本的にGithubを用いて， ソースコードの管理を行います．  
Githubの使い方がわからない方は以下のサイトがおすすめです．  
https://prog-8.com/courses/git  
このサイトでは1時間ほどで， Gitの基本的な概念を理解することができます．  
チュートリアルを始める前に， 一度目を通しておいてください．  

## GitHubでssh接続する手順
以下のサイトの手順通りにやるとできます．  
https://qiita.com/shizuma/items/2b2f873a0034839e47ce  
わからない点があればどんなことでもTAへ質問してください．  

# usage
初回はこのレポジトリを clone してください。  　　
```
$ git clone https://github.com/Language-Media-Lab/100knock2022_huyu.git
```
  
各Chapterのはじめでは、各Chapterのディレクトリへ移動し、ブランチを切って、自分用の作業用ブランチで作業してください。  
ブランチの名前は自分の名前にしてください(例：北大太郎の場合、hokudai_taro)
```
# 取り組むChapterへ移動
$ cd chapter1
#新規ブランチ作成
$ git branch hokudai_taro
#作成したブランチに切り替え
$ git checkout hokudai_taro
```

コードを書いたら自身のブランチの remote repository に push してください。  
- Pythonで書いた場合、ファイル名はすべて二桁の数字 & 自分の名前を入れてください（例: knock01_taro.py）
- google colab等で書いた場合、ファイル名は各Chapterの数字 & 自分の名前を入れてください。（例: chapter01_taro.ipynb）
```
$ git add ./knockXX_taro.py
$ git commit -m 'your message'
$ git push origin hokudai_taro
```
毎週1章分の担当者が書いたコードのレビューを行い、問題がなければ、mainへマージしてください．  
**毎週各章のマージまで終わらせて，その日の勉強会を終わらせてください**

# 注意事項
わからないところはdiscord等で**積極的に** TA か研究室の人に聞いてください。     
