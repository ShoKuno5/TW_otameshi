コードは全て `notebooks/` ディレクトリ内のノートブックで実行しました。

`data/` ディレクトリには、生のレビューデータと前処理後のレビューデータが保管されています。

```
data/
├── embeddings/
├── processed/
│   ├── android_cleaned.csv
│   ├── android_cleaned_mecab.csv
│   └── android_cleaned_mecab_with_topics.csv
├── raw/
│   ├── android.json
│   └── ios.json
```

Pythonのバージョンは3.10.2を使用しました。