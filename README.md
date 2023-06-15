stl2dm0
==============================

Predicting Dark Matter Distribution from Stellar Phase Space

Project Organization
------------

    ├── LICENSE
    ├── README.md          <- 開発者がこのプロジェクトを使用するためのトップレベルのREADME。
    ├── data
    │   ├── external       <- サードパーティのソースからのデータ。
    │   ├── interim        <- 変換された中間データ。
    │   ├── processed      <- モデリングに使用される最終的な正規データセット。
    │   └── raw            <- オリジナルの不変のデータダンプ。
    │
    ├── docs               <- 詳細については、sphinx-doc.orgを参照してください。
    │
    ├── models             <- トレーニングされたシリアル化されたモデル、モデルの予測、またはモデルの要約
    │
    ├── notebooks          <- Jupyterノートブック。命名規則は、番号（順序）、作成者のイニシャル、および短い`-`区切りの説明です。例えば、`1.0-jqp-initial-data-exploration`。
    │
    ├── references         <- データ辞書、マニュアル、およびその他の説明資料。
    │
    ├── reports            <- HTML、PDF、LaTeXなどの形式で生成された分析
    │   └── figures        <- 報告に使用される生成されたグラフィックと図
    │
    ├── requirements.txt   <- 分析環境を再現するための要件ファイル。例えば、`pip freeze > requirements.txt`で生成されます。
    │
    ├── setup.py           <- プロジェクトをpip install可能にするためのファイル（`pip install -e .`でsrcをインポートできるようにします）
    ├── src                <- このプロジェクトで使用するソースコード。
    │   ├── __init__.py    <- srcをPythonモジュールにする
    │   │
    │   ├── data           <- データをダウンロードまたは生成するスクリプト
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- 生データをモデリングのための特徴に変換するスクリプト
    │   │   └── build_features.py
    │   │
    │   ├── models         <- モデルをトレーニングし、トレーニングされたモデルを使用して予測を行うスクリプト
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- 探索的および結果指向の視覚化を作成するスクリプト
    │       └── visualize.py
    │
    └── tox.ini            <- toxファイル。tox.readthedocs.ioを参照してください。


--------

<p><small>このプロジェクトは、<a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>をベースにしています。#cookiecutterdatascience</small></p>
