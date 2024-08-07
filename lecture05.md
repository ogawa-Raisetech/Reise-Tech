# 第五回課題

## EC2上でサンプルアプリケーションのデプロイ、動作確認

### 1.組み込みサーバー（Puma）での動作確認
  ![puma-deploy](/image/lecture05/puma-deploy.png)

### 2.組み込みサーバーとUnixSocketを使った動作確認
  ![puma-unixsocket](/image/lecture05/puma-unixsocket.png)

### 3.Nginxの単体起動確認
  ![nginx](/image/lecture05/nginx.png)

### 4.Nginxと組み込みサーバー、UnixSocketを組み合わせての動作確認
  ![puma-unixsocket-nginx](/image/lecture05/puma-unixsocket-nginx.png)

### 5.ELB（ALB）を追加して動作確認
  - ALBのDNS名で動作確認
  ![ALB-DNS](/image/lecture05/ALB-DNS.png)

### 6.S3を追加して画像の保存先として活用
  - S3に画像を保存
  ![s3-picture-save1](/image/lecture05/s3-picture-save1.png)
  - S3内のオブジェクトとして画像があることを確認
  ![s3-picture-save2](/image/lecture05/s3-picture-save2.png)

## 構成図の作成
  ![configuration-diagram](/image/lecture05/configuration-diagram.png)


## 感想

 - どのファイルを修正すべきなのか、設定ファイルの内容の意味は何かという点を理解するのに時間がかかりました。
 - エラーログから対応方法を調べる力とどの部分で問題が発生しているか原因の切り分ける力が身についたと感じました。
 - エラーを解決できた時は達成感があり学ぶことは楽しいと感じることが出来ました。