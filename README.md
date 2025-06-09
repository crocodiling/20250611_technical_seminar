# 20250611_technical_seminar
202050611の技ゼミ用のリポジトリです．こちらをデスクトップにgit cloneしてください．

このリポジトリには，Dockerfile,requirements.txt,sample.py，docker-compose.ymlというファイルが入っています．
こちらのDockerfileをbuildしたのち，コンテナを作成することで，sample.pyを実行することができます．
また，requirements.txtについてですが，特に何も記載しなくてOKです．flask，numpyなどを記載することにより，モジュールを利用することができます．

最後に，docker-compose.ymlですが，これは，mysqlのコンテナを立ち上げるためのファイルです．
技ゼミでも説明しますが，コンテナを立ち上げる際，「docker container run -it 〇〇」「docker start 〇〇」コマンドを打つ必要があります．しかし，あらかじめ，docker-compose.ymlファイルを作成しておくことで，「docker compose up -d」コマンドを打つだけで，コンテナを立ち上げることができます．これは，複数のコンテナをまとめて立ち上げたい時に，同時に起動できるので大変便利です．つまり，複数のコンテナを立ち上げるためのコードをdocker-compose.ymlファイルに起動しておき，それを実行することで，利便性が向上するということです．今回は，docker-compose.ymlファイルの利用もみなさんに行ってもらいたいと思います．
