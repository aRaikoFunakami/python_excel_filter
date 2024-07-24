# python_excel_filter

毎回 Excel で処理していたフィルタ処理を自動化する
個人的なプログラムなのであくまで備忘録

# usage

環境設定を行う

```
poetry install
```

コンフィグファイルを設定する
```
cp config.py.sample config.py
vi config.py
```

フィルタを実行してフィルタを適用した config.py で指定した csv ファイルに出力する
```
poetry run python ./filter.py
```

csvファイルの内容から売上状況を確認する
```
poetry run python ./calculate_totals.py <csv ファイル名>
```