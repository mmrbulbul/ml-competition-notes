# Signate: 第2回 国土交通省 地理空間情報データチャレンジ

## 概要
このコンペティションは、国土数値情報や民間企業の地理空間データを活用し、不動産の売買価格を予測するモデルを構築することを目的としています。

## 問題概要
提供された地理空間情報データを用いて、指定された不動産の売買価格を正確に予測することが課題です。

## データセット
データセットは、[第2回 国土交通省 地理空間情報データチャレンジ](https://user.competition.signate.jp/ja/competition/detail/?competition=2b0105bc0c674f258e39cb2c7711e36f)のページからダウンロードできます。ダウンロードしたデータは、プロジェクトの`data`フォルダに配置してください。

### データディレクトリ構造
```
data
├── data_definition.xlsx       # データ定義書
├── README.pdf                 # データセットの説明
├── sample_submit.csv          # 提出用サンプルファイル
├── test.csv                   # テストデータ
└── train.csv                  # トレーニングデータ
```

## プロジェクト構成
```
competitions/signate-geospatial-2025/
├── data/                      # データセット
├── notebooks/                 # 分析用ノートブック
├── src/                       # ソースコード
│   ├── features/              # 特徴量エンジニアリング
│   ├── models/                # モデル
│   └── utils/                 # ユーティリティ
└── requirements.txt           # 必要なPythonライブラリ
```

## セットアップ
1. 必要なライブラリをインストールします:
   ```bash
   pip install -r requirements.txt
   ```
2. データセットを`data`フォルダに配置します。

## 今後の作業
- 特徴量エンジニアリングの実装
- モデルのトレーニングと評価
- 提出用ファイルの作成

## 参考文献
