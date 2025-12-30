# paypaycsv2mfchunks
PayPayからDLした明細CSVをMoneyForwardの100行制限に合わせて分割するオフラインツール

## 使い方

1. https://geerpm.github.io/paypaycsv2mfchunks/
3. paypayアプリからダウンロードした明細CSVファイルを選択
4. 処理実行
5. 自動で分割されzipファイルとしてダウンロードされるので、解凍して利用
   - スマホのファイル閲覧アプリなどでダウンロードしたzipファイルを開き、中のchunkXXXX.csvを順番に共有->MoneyForwardアプリ選択して取り込んでいく

## 注意点、免責事項

1. csv分割処理はすべて自分の端末上で行われ、csvに関する情報はネット上にアップロードされませんが、それを100%保証するものではありません
2. [index.html](/index.html) にソースコードがあるのでDLしてブラウザで開く、自己利用目的の改変は好きにしてok
