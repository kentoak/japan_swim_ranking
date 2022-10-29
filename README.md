# japan_swim_ranking

## swimrecord.ipynb
https://result.swim.or.jp/ からcurlする。
allpagesで50位ずつ取得。200位まで取得してファイルにいれる。

## concat.ipynb
curlしたjsonファイルは50位ずつで1つのファイルなのでそれを結合する。

## getTopTen.ipynb
少なくとも1回top10に入った選手の記録を集める。

## name_event.ipynb
ある選手について特定の種目をcsvで抽出する。

## names_event.ipynb
複数の選手について特定の種目をcsvで抽出する。
