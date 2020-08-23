自動ビルド
================
編集する度にビルドして確認するのは効率が悪いので自動的にビルドしてくれるsphinx-autobuildを利用します。
sphinx-autobuildのインストールコマンドは下記になります。 ::

  pip install sphinx-autobuild

下記のコマンドで自動的にビルトとブラウザの再リロードをしてくれるようになります。 ::

  sphinx-autobuild -b html source docs/

コマンド実行後、http://127.0.0.1:8000 にアクセスするとビルドした結果を確認できます。