# VirtualBowling
学科展VirtualBowlingの作業データが散逸していてわかりにくい上、各個人作業の共有が難しい体勢にあったため作りました。
ただしVB2016ディレクトリ内は依然として混沌としていますので整理したほうが良いかもしれません(ぼくはいや(というかわからない

# 構成
ルートディレクトリにおけるVB2016ディレクトリ以下は先輩方に頂いたデータそのままです。(一部ライトを焼き付けたりしてありますが結局1から2017として作り直したためそんなに変更してないです)

VB2017ディレクトリ以下はVB2016の中身を覗いて雑に僕が作ってみたものです。
VB2016はUnity 4.x ですがVB2017はUnity 2017.x 環境で構築してありますので互換性はありません。

# Unity上のAssetを弄る時の注意
重くなるのでライトはbakeしたほうがいいです。焼かないで光源増えるとメモリが死にます。マテリアルとテクスチャはUnity単体だと限界がありますので外部のモデリングソフトウェア(blender等)でUVマップを出力し、画像編集ソフトウェアで詰めるとリアルになります。質感を出すときはノーマルマップも作成して重ねると良いです。

#### マークダウン書いたこと無いし書けない
