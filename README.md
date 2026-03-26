ここでハッカソンの復習をします。

EC2・テーブル名・公開鍵名:MIT-rennsyuu

パブリックIPアドレス:43.206.241.191

どうやらダウンロードした秘密鍵のディレクトリの絶対パスは、/mnt/c/Users/muto4/Downloads/らしいです。

SSH接続する場合、
ssh -i ~/.ssh/MIT-rennsyuu.pem ec2-user@43.206.241.191

http://43.206.241.191:5000
でFlaskにアクセス可能！


iv-QDot+49Ch（MySQL初期パスワード）

3/24　ステップ５　base.htmlまで作成完了

3/26 view.pyの途中まで


E45: 'readonly' option is set (add ! to override)
vimを読み取り専用で開くと↑になるので、:wq!で対応（今回のアプリ開発はsudoで開くのが基本のため）