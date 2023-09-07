# 便利コマンド

## netstat
### ネットワークの接続を確認する
https://qiita.com/takat0-h0rikosh1/items/5f8c1b08631249c5dba7<br>
9000番 port の状態を確認。<br>
$ netstat -an -p tcp | grep 9000<br>
tcp46      0      0  *.9000                 *.*                    LISTEN
## tcpdump
### ネットワーク通信の生のデータをキャプチャし、その結果を出力してくれる
https://qiita.com/tossh/items/4cd33693965ef231bd2a<br>
送信元ipアドレスを指定<br>
tcpdump src host [src_ip]<br>

hogehoge
