# BetterOutline
uGUIのTextのアウトラインをより綺麗に表示するクラスです。
頂点メッシュを文字の円周上に配置して、なめらかなアウトラインを実現しています。
（Unity4.6/5.0/5.1/5.3で動作確認済み）

## Usage
uGUIのTextやImageコンポーネントにアタッチして使います。
'Divide Amount'は、増やせば増やすほど頂点メッシュが円周上に追加され
クオリティが高くなりますが、その分描画負荷も上がります。
クオリティが維持できるぎりぎりの少ない値での設定をお勧めします。
