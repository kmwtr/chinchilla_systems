## BrushKnob: デジタルペインティングのための外付けデバイス

[[ キャンペーンサイト / Campaign Site ]](https://igg.me/at/brushknob/)

[[ ピッチビデオ（字幕ボタン"CC"が右下にあります） / Pitch Video ]](https://vimeo.com/163763962)

![BK mini logo](https://c1.iggcdn.com/indiegogo-media-prod-cld/image/upload/c_limit,w_620/v1461627039/hr_s9kmh6.png)

## BrushKnob のコンセプト

![photo 1](https://c1.iggcdn.com/indiegogo-media-prod-cld/image/upload/c_limit,w_620/v1461469545/_DSC0477s_bzmewx.png)

私の名前は上航です。日本・東京のプロダクションでコンセプトアーティストとして働いています。その一方で、私は家に帰るとキーボードと半田ごてを握り、もっと広い意味でのクリエイターになります。

![photo 2](https://c1.iggcdn.com/indiegogo-media-prod-cld/image/upload/c_limit,w_620/v1461864946/prototypes_dch0bm.png)

1年ほど前から私は仕事の合間にスケッチを描き始め、プロトタイプを実際の仕事の中で使い、そしてついにこのデバイスが完成しました。BrushKnobです。

![photo 3](https://c1.iggcdn.com/indiegogo-media-prod-cld/image/upload/c_limit,w_620/v1461870471/_DSC0493s2_dvm7rk.png)

BrushKnobはPhotoshopの操作を直感的にする、とてもシンプルなデバイスです。機能は2つだけに絞ってあり、ノブはブラシサイズのコントロールを、スイッチはブラシとイレーサーの切り替えを行います。

![gif 1](https://raw.githubusercontent.com/kmwtr/chinchilla_systems/master/brushknob/assets/BKIsWorking_min.gif)

コンピュータとの通信には一般的なキーボード信号を使っているので、特別なドライバーをインストールする必要はありません。コンピュータにケーブルでつなげば、すぐに使う事ができます。

![gif 2](https://raw.githubusercontent.com/kmwtr/chinchilla_systems/master/brushknob/assets/HowItWorksPicto_min.gif)

コンピュータはBrushKnobを外付けキーボードだと認識しており、あなたがノブを回したりボタンを押した時、キーボードショートカットが押されたのと同じ状況が作り出されます。そのため、BrushKnobはPhotoshopと同じキーボードショートカットを持つアプリケーションであれば同様に使う事ができます。

![gif 3](https://raw.githubusercontent.com/kmwtr/chinchilla_systems/b08b51f2d9c32e93adbd8aa41f9c370275fd71a5/brushknob/assets/BKWithBlender.gif)

もちろん、アプリケーション側のショートカット設定を変える事によって、BrushKnobに様々な役割を与える事も可能です。

![photo 4](https://c1.iggcdn.com/indiegogo-media-prod-cld/image/upload/c_limit,w_620/v1461627096/box_akgtwv.png)

私は、このデバイスが世界中のアーティストやクリエイターにとって有用であると確信しています。BrushKnobをちゃんとしたパッケージに入れて皆さんに届けられる日を、私は夢見ています。

![BK mini logo](https://c1.iggcdn.com/indiegogo-media-prod-cld/image/upload/c_limit,w_620/v1461627039/hr_s9kmh6.png)

## 特徴

![photo 5](https://c1.iggcdn.com/indiegogo-media-prod-cld/image/upload/c_limit,w_620/v1461627117/pitchTexPicto_jh6vcr.png)

- シンプルな操作性
- 高い移植性と安定性
- 実用的かつ特徴的なハードウェアデザイン
- オープンソース(GPL.v3)のコードと回路

![photo 5.5](https://c1.iggcdn.com/indiegogo-media-prod-cld/image/upload/c_limit,w_620/v1465348635/_DSC0675_1200x600_nfsgxa.jpg)

BrushKnobは単にGPL.v3なだけではありません。ボディの裏にスルーホールがあり、簡単にAVRの全ピンにアクセスできます。

同じくAVRでデバイスを作っていらっしゃる[D.F.Mac](https://twitter.com/tadfmac)さんが、[VUSBMidiAttiny](https://github.com/tadfmac/mi-muz/tree/master/arduino/libraries/VUSBMidiATtiny)というMIDIライブラリをBrushKnobにも対応してくださいました！
このように、BrushKnobはAVRやArduinoの知識があれば、だれでも自分の好きなようにカスタムすることができます！

![BK mini logo](https://c1.iggcdn.com/indiegogo-media-prod-cld/image/upload/c_limit,w_620/v1461627039/hr_s9kmh6.png)

## 技術情報

![photo 6](https://c1.iggcdn.com/indiegogo-media-prod-cld/image/upload/c_limit,w_620/v1461854222/_DSC0436sxs_bvssl4.png)

### 信号

- HID US Keyboard (USB1.0)
- Knob: ‘[‘ ‘]’
- Switch： ‘b’ ‘e’

### OS

- Windows
- OSX

### 筐体素材

- ノブ：アルミニウム
- ボディ：アクリル
- ボルト・ナット：ステンレス
- コネクタ：ステンレス

### 付属品
- USB Cable (A to B)

### マイコン

- Atmel ATtiny85

### コード

[https://github.com/kmwtr/BrushKnob](https://github.com/kmwtr/BrushKnob)

### 寸法

- Knob: ⌀20mm
- Length: 75mm
- Width: 30mm
- Height: 35mm

BrushKnobの挙動はPCのキーボード設定に依存します。BrushKnob(Standard)は、**英語キーボードが接続されているPC**で正しく機能するようにプログラムされています。（日本語キーボードが接続された環境の多くでは、 '[' ではなく '@' が入力されます。）**日本語キーボード環境で使用する予定の方は、「BrushKnob JP Ver.」を選んでください。このキャンペーン限定の、日本語キーボード信号を送るモデルです！**</p>

![BK mini logo](https://c1.iggcdn.com/indiegogo-media-prod-cld/image/upload/c_limit,w_620/v1461627039/hr_s9kmh6.png)

## ファンディングの計画とタイムライン

BrushKnobの設計は、量産する量に合わせてより良く修正する予定ですが、現時点で可能な作業の多くはすでに完了しています。より多くのご支援を心からお待ちしております！

![photo 7](https://c1.iggcdn.com/indiegogo-media-prod-cld/image/upload/c_limit,w_620/v1464098147/timeline2_qo9yn4.png)

もし余力があれば、ロゴを印刷したステッカーも作って同梱したいと考えています。**ステッカー万歳！**

![BK mini logo](https://c1.iggcdn.com/indiegogo-media-prod-cld/image/upload/c_limit,w_620/v1461627039/hr_s9kmh6.png)

## リスクと挑戦

![photo 8](https://c1.iggcdn.com/indiegogo-media-prod-cld/image/upload/c_limit,w_620/v1461630809/_DSC0424s_szww8e.png)

BrushKnobはとてもシンプルなプロダクトですが、それを大量生産して皆さんに届けるには、とても複雑なプロセスを乗り越えなければいけません。自分はプロのデザイナーで、このキャンペーンを始めるために慎重に計画を進めてきました。それは今後も変わりません。しかし、ここから先は私にとって初めての経験であり、それが支援者の方にとってリスクである事も事実です。私は支援してくださる皆さんに感謝し、最善を尽くします。BrushKnobのリリースに手を貸してください！

![BK mini logo](https://c1.iggcdn.com/indiegogo-media-prod-cld/image/upload/c_limit,w_620/v1461627039/hr_s9kmh6.png)

## おわりに

![photo 9](https://c1.iggcdn.com/indiegogo-media-prod-cld/image/upload/c_limit,w_620/v1462580857/videoCapture_me_y7tiij.png)

私のデバイスと相性が合わなかった方も、よかったら<a href="http://kmwtr.xyz" target="_blank" rel="noopener">私のサイト</a>を覗いてみてください。私が関わったアニメやゲーム、或いは個人的な作品に興味を持ってもらえると、とても嬉しく思います！

最後に…もしあなたの周りにBrushKnobに興味を持ちそうな友達がいたら、ぜひ教えてあげてください。

上　航

[[ キャンペーンサイト / Campaign Site ]](https://igg.me/at/brushknob/)

[[ ピッチビデオ（字幕ボタン"CC"が右下にあります） / Pitch Video ]](https://vimeo.com/163763962)
