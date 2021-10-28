# hisseki_test_py
筆跡鑑定のテスト・試作用のリポジトリ

Repository for handwriting certification test and prototype

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
