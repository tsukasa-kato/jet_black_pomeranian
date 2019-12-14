# 概要
ポメラニアンbot
- 「ルシ募集」と言えば、テンプレートを置いてくれる
- 古戦場時、色々言ってくれる
- 「ヒヒイロチャレンジ」と言えば、ヒヒイロチャレンジができる

# 実行方法
各環境変数を設定する
```
pip install pyyaml
python3 jet_black_pomeranian.py
```

# TODO
- Docker化(環境変数のため)
- テストコードの追加?
- アルバハ募集 6人がリアクションしたらポメラニアンが教えてくれる
- ルシ属性
    - ルシ募集の属性リアクションから「ルシ属性」でポメラニアンが担当の属性を考えてくれる
- ルシの行動を教えてくれるbotの作成
- 古戦場の定期発言
    - loop だと1分ごとに余計な処理が走るのでより良い方法を検討
    - 古戦場の日程を別ファイルに置いておく->よりよくする
    - 日程から発言する日を判別するようにする

