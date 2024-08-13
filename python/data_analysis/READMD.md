
# (応用)Pythonを使ってデータをみてみよう
まずどんなデータが公開されているか見てみよう！

例）データ 公開 or 【自分の好きなもの】公開データ でGoogle検索してみる...

日本の公的機関が公開してるものだと...
- [e-gov データポータル](https://data.e-gov.go.jp/info/ja)
- [統計局 統計データ](https://www.stat.go.jp/data/)
- [沖縄県 統計資料webサイト](https://www.pref.okinawa.jp/toukeika/)
等がある！

他にも，
- [kaggle](https://www.kaggle.com/)
  - データを分析して，予測モデルを競うサイト
  - いろいろなデータが橈側されている.
- [Movebank](https://datarepository.movebank.org/home)
  - 動物の追跡データバンク
  - 論文と紐づいている


## CSVデータを読み込んでみよう！
前述の公開データは大体.csvというcsvファイルの書式になっている．どんなファイルかみてみよう．

CSVデータとは？
データひとつひつつが『，』で区切られたテキストデータ．なので，どこからどこまでが一つのデータなのか人間にもプログラムにもわかりやすい．

### Pythonでcsvファイルを読んでみよう
参考：[なる先生の授業](https://ie.u-ryukyu.ac.jp/~tnal/2024/prog1/static/fileio.html)

どういうコード，操作をしたらCSVファイルを読み込めるだろうか？必要な過程を順番に考えてみよう！
1. CSVファイルをpcにダウンロードする．
1. Pythonファイルを用意する
1. ...
1. ...



### Pythonライブラリー Pandasを使ってみよう

👆でPythonの標準ライブラリーを使ってcsvファイルを読み込んだ．
実はPythonにはCSVファイルを読むことに加え，書き出したり，カラムを特別な意味を設定したり，便利にデータを扱えるライブラリーがある．

先ほどやったCSVファイルを読み込む．をpandasを使ってやってみよう！

参考：[pandasでcsvファイルを読む](https://pandas.pydata.org/docs/reference/api/pandas.read_csv.html#pandas-read-csv)
[pandas公式チュートリアル](https://pandas.pydata.org/docs/getting_started/intro_tutorials/01_table_oriented.html)

## pandasでデータをみよう
便利なやつら

describe [ドキュメント]()

max,min [ドキュメント]()

本当似合ってるか，手計算，numpyの結果と比較して確認

## データを可視化しよう

matplotlib，データをグラフ化するライブラリー

pandasと組み合わせても使える！

まずは，どんなグラフがふさわしいかデータから考えてみるよう．
作るグラフの構想は，紙に書いてみたりすると整理されておすすめ．



## トラブルシューティング

### エンコーディングエラー
https://docs.python.org/3/library/codecs.html#standard-encodings
