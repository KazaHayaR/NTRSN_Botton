# NTRSN_Botton
せんせえのための点滴
10分おきに、名取さなのせんせえ応援ボイスがさいせいされるぞ！

## 要件
- ruby 2.5.1

## 制作意図
つよつよRubyつかいになるために、バーチャルサナトリウムの力を借りる

## ブランチの指針
`master:` 何であれ動作する状態のものを格納します。
`feature/FOOBAR:` FOOBAR にあたる機能の開発をするブランチとして使います。
基本的にはフィーチャーブランチ(feature/FOOBAR)で開発して、 Pull Request を作成し、田中によってレビューした上で、 `master` にマージがされるという流れにします。


## 実装の指針
- `ntrsn.rb` メインプログラム


## 第一段階
ローカルファイル上で動作する名取タイマーの作成。
10分おきに、名取さなのせんせえ応援ボイスがさいせいされるぞ！
ruby上、CUIでの動作

##第二段階
GUIの実装と何分おきに応援してもらうか設定できる

##第三段階
Ruby on Railsによるサーバーを設置し、Webアプリケーションとして動作させる。

##第n段階

##最終段階
名取さなに認知される。
