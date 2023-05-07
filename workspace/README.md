パッケージはopamを使ってインストール．

パッケージの変更などの後は`satyrographos install`を実行．

システム内のフォントを取り入れたい場合は`satyrographos install --system-font-prefix 'system:'`とすると，ドキュメント内で`system:${font-name}`という形でシステムフォントを参照できる．