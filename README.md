#gota2-observatory
## stockb.py
某掲示板の某板のスクレイピング実験用のスクリプトです。
0 起動すると、カレントディレクトリの下に"MyOutputs"ディレクトリ（フォルダ）が生成されます。
1 最初にスレッド一覧の所在を聞かれます（"Thread list URLs?"）ので、"https://example.com/foo/bar.html"のような形式で入力してください。全スレッドhtmlのURL一覧が表示されるので、状況を確認してください。
2 次に、各スレッドのhtmlが格納されていディレクトリを聞かれます（"Base URL?"）ので、これも"http://example.com/baz/qux/"のような感じで入力してください（最後は"/"。ここはわざと曖昧に描いてあるので、実際のサイトをみて工夫してください）。
3 スレッドの所在一覧が表示されますので、良さそうだったら"y"を入力してください。
4 ADSL環境で、300スレッド程度（全部で大体60 MBぐらい）のダウンロードが約30分で完了します。
5 後は煮るなり焼くなり。なお、htmlのencodingはUTF-8です。ブラウザによっては自動判別だと文字化けするので、その場合は手動でUTF-8に設定してください。
6 設定をいじるとダウンロード速度を上げることができますが、相手のサーバに負担を掛けてしまうので自粛してください。うっかりすると新聞沙汰になって一躍有名人になれるかもしれないので、くれぐれも良識ある行動をお願いします。
