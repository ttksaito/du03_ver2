# 英語例文学習アプリ

このアプリケーションは、英語の例文を効率的に学習するためのツールです。

## 機能

- セクションごとの例文学習
- 音声読み上げ機能
- 学習進捗の記録
- モバイル対応のUI

## 必要なファイル

- `duo3.xlsx`: 例文データを含むExcelファイル

## セットアップ方法

1. リポジトリをクローン
```bash
git clone [your-repository-url]
```

2. 依存関係のインストール
```bash
pip install -r requirements.txt
```

3. アプリケーションの実行
```bash
streamlit run app2.py
```

## 注意事項

- `duo3.xlsx`ファイルは同じディレクトリに配置する必要があります。
- モバイルからアクセスする場合は、Streamlit Cloudでホストされたバージョンを使用してください。 