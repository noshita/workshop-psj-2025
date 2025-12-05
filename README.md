# 日本古生物学会 第175回例会 ランチョンセミナー

日本古生物学会 第175回例会で開催されるランチョンセミナー **やってみよう！「かたち」の定量解析**のハンズオン向けノートブック．

## 構成

- notebooks
  - generalized_Procrustes_analysis.ipynb # 一般化プロクラステス解析
  - elliptic_Fourier_analysis.ipynb # 楕円フーリエ解析
  - thin_plate_spline.ipynb # おまけ：薄板スプライン法
- pyproject.toml # プロジェクト設定ファイル

## 実行環境

セミナーでは，Google Colabでの実行を想定している．

ローカルで実行したい場合は，このディレクトリ内で以下を実行すると環境構築することができる．

```sh
uv sync -U
```

Jupyter Labを立ち上げて解析をしてみてほしい．

```sh
uv run jupyter lab
```

## ライセンス

本リポジトリ内のノートブックは[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)にて公開しています．
