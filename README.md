# hisseki_test_py
筆跡鑑定のテスト・試作用のリポジトリ

Repository for handwriting certification test and prototype

Google Colabratory用

For Google Colabratory

マイドライブ/colabの中にhisseki_test_pyとしてリポジトリを保存してください

Please save the repository in MyDrive/colab as hisseki_test_py.

## Directory structure

```
├── README.md
├── hisseki.ipynb
└── tf_datas
    ├── hisseki0.png # 筆跡画像本体 handwriting image
    ├── hisseki1.png # hisseki(number).png
    ├── hisseki2.png .....
    └── labels.txt # 学習用ラベル labels for train
```

## labels.txt

```
1 # label for hisseki0.png
3 # label for hisseki1.png
14 #label for hisseki2.png .....
12
12
4
.....
```

## What's the dataset?
[筆跡鑑定アプリ](https://github.com/takuminmin-m/hisseki_server)を用いて収集した128*128pxの筆跡画像です。ラベルは書いた人を示します。一部誤操作などによりノイズデータが含まれています。

It's 128*128px images of handwriting made by [hisseki_server](https://github.com/takuminmin-m/hisseki_server). The labels mean writer of the image. This dataset includes a little noise data.
