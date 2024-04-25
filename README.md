# Ballade Tempo
Doricoの**即時テンポテキスト**と**メトロノームテキスト**用フォントの試作品です。
## インストール
**BalladeTempo-Regular.otf**と**BalladeTempo-Bold.otf**をインストールしてください。
## 設定
Doricoの**ライブラリー** > **フォントスタイル**より**即時テンポテキスト**のフォントファミリーをBallade Tempo、スタイルをBold、**メトロノームテキスト**のフォントファミリーをBallade Tempo、スタイルをRegularに設定してください。
## 収録文字
### 即時テンポテキスト (Bold)
[Old Standard TT Bold](https://github.com/akryukov/oldstand)のラテンアルファベットをベースに調整したものと、Unicode外に小文字の上付き文字（肩文字）を収録しています。その他のOld Standard TTのキャラクターも残してあります。

半角サーカムフレックス「^」に続けて小文字アルファベットを入力するとリガチャー（合字）によって上付き文字に置き換わります。たとえば「1<sup>er</sup> mouvement」は「1^e^r mouvement」と入力します。

アポストロフィー「'」（U+0027）は曲線型「’」（U+2019）に置き換わるため、「L’istesso tempo」に適切な字形が使われます。
### メトロノームテキスト (Regular)
メトロノーム記号に使われる「=」と「≒」をデザインしました。「≒」は「≈」の符号点にも収録していますので、**浄書オプション** > **テンポ**から**おおよその速度表記**を**ニアリーイコール記号**（≈）に設定すれば「≒」に置き換わります。

数字、丸括弧、波ダッシュは[しっぽり明朝](https://github.com/fontdasu/ShipporiMincho)がベースです。

波ダッシュはDoricoでデフォルトでテンポ範囲に用いられるenダッシュ「–」の符号位置にも入れてあります。

漢字の「約」も[源ノ明朝](https://source.typekit.com/source-han-serif/jp/)より収録しています。リガチャー機能により、**おおよその速度表記**を**約**（approx.）に設定すれば「約」に置き換わります。

ほか、[Old Standard TT Regular](https://github.com/akryukov/oldstand)のラテンアルファベット等も収録しています。

※メトロノーム記号に使われる音符は収録していません。
## ライセンス
SIL Open Font Licenseバージョン1.1でライセンスされています。作者：[重田](https://shigeta.info)
