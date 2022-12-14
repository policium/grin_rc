# GRIN RC 組み立て手順

## はじめに

この度はGRIN RCのご購入ありがとうございます。このキットははんだ付けとファームウェアの書き込み作業が必要です。以下の手順に従って組み立ててください。

## 注意事項

本製品はKailh Chocスイッチに対応しています。キーキャップは17.5x16.5mm以下のサイズに対応します。MBK Choc推奨です。

## 作業内容

[１．事前準備](#%EF%BC%91%E4%BA%8B%E5%89%8D%E6%BA%96%E5%82%99)  
[２．キット内容の確認](#%EF%BC%92%E3%82%AD%E3%83%83%E3%83%88%E5%86%85%E5%AE%B9%E3%81%AE%E7%A2%BA%E8%AA%8D)  
[３．初期動作確認](#%EF%BC%93%E5%88%9D%E6%9C%9F%E5%8B%95%E4%BD%9C%E7%A2%BA%E8%AA%8D)  
[４．電子部品のはんだ付け](#%EF%BC%94%E9%9B%BB%E5%AD%90%E9%83%A8%E5%93%81%E3%81%AE%E3%81%AF%E3%82%93%E3%81%A0%E4%BB%98%E3%81%91)  
[５．OLEDのはんだ付け](#%EF%BC%95oled%E3%81%AE%E3%81%AF%E3%82%93%E3%81%A0%E4%BB%98%E3%81%91)  
[６．RGBLEDのはんだ付け](#%EF%BC%96rgbled%E3%81%AE%E3%81%AF%E3%82%93%E3%81%A0%E4%BB%98%E3%81%91)  
[７．スイッチソケットのはんだ付け](#%EF%BC%97%E3%82%B9%E3%82%A4%E3%83%83%E3%83%81%E3%82%BD%E3%82%B1%E3%83%83%E3%83%88%E3%81%AE%E3%81%AF%E3%82%93%E3%81%A0%E4%BB%98%E3%81%91)  
[８．タッチセンサーの調整](#%EF%BC%98%E3%82%BF%E3%83%83%E3%83%81%E3%82%BB%E3%83%B3%E3%82%B5%E3%83%BC%E3%81%AE%E8%AA%BF%E6%95%B4)
[９．ボトムプレートの取り付け](#%EF%BC%99%E3%83%9C%E3%83%88%E3%83%A0%E3%83%97%E3%83%AC%E3%83%BC%E3%83%88%E3%81%AE%E5%8F%96%E3%82%8A%E4%BB%98%E3%81%91)  
[１０．スイッチプレート／スイッチの取り付け](#%EF%BC%91%EF%BC%90%E3%82%B9%E3%82%A4%E3%83%83%E3%83%81%E3%83%97%E3%83%AC%E3%83%BC%E3%83%88%E3%82%B9%E3%82%A4%E3%83%83%E3%83%81%E3%81%AE%E5%8F%96%E3%82%8A%E4%BB%98%E3%81%91)  
[１１．ディスプレイカバーの取り付け](#%EF%BC%91%EF%BC%91%E3%83%87%E3%82%A3%E3%82%B9%E3%83%97%E3%83%AC%E3%82%A4%E3%82%AB%E3%83%90%E3%83%BC%E3%81%AE%E5%8F%96%E3%82%8A%E4%BB%98%E3%81%91)  
[１２．ファームウェアの書き込み](#%EF%BC%91%EF%BC%92%E3%83%95%E3%82%A1%E3%83%BC%E3%83%A0%E3%82%A6%E3%82%A7%E3%82%A2%E3%81%AE%E6%9B%B8%E3%81%8D%E8%BE%BC%E3%81%BF)  
[１３．動作確認](#%EF%BC%91%EF%BC%93%E5%8B%95%E4%BD%9C%E7%A2%BA%E8%AA%8D)  

## １．事前準備

### キット以外に必要な部品を準備する

![キー配列](https://user-images.githubusercontent.com/3132296/184517997-46335e94-6a34-457d-919d-be060dce6e9e.png)
- Choc V1対応キーキャップ 17.5x16.5mm以下のサイズ
- Kailh Chocスイッチ66個

### 工具を準備する
- はんだごて（電子基板用）
- はんだ
- フラックス
- フラックスクリーナー（IPA等のアルコールや溶剤でも代用可能）
- ピンセット
- ニッパー（OLEDの足を切断するため少し大きめのもの）
- プラスドライバー(No.0)
- ウエス、キムワイプ、綿棒
- グリス、オイル（スタビライザーおよびスイッチの潤滑用）
- テスター(トラブル時の原因調査用)

## ２．キット内容の確認
以下が揃っていることをご確認ください。
不足がある場合は、ストアサイトのトップページ下部にある、メールアイコンよりメッセージを下さい。

### 袋①
* 基板
* スイッチプレート
* ボトムプレート

### 袋②
* 0603 チップ抵抗 2.2k 1個
* 0603 チップ抵抗 10k 1個
* 0603 チップコンデンサ 30pF 8個
* トリマコンデンサ 20pF 1個
* 0603 チップコンデンサ 100nF 2個
* タッチセンサーIC 2個

### 袋③
* OLEDモジュール

### 袋④
* RGBLED 66個
* スイッチソケット 66個

### 袋⑤
* 低頭ねじ短 M2x2.5mm 6個
* 低頭ねじ長 M2x8mm 3個
* 両めねじスペーサー M2x3mm 7個
* 両めねじスペーサー M2x5mm 1個

### 袋⑥
* M2ワッシャー黒 4個
* 低頭ねじ中 M2x5mm 4個
* 両めねじスペーサー M2x5mm 3個
* M2精密ねじ M2x4mm 3個

### 袋⑦
* ディスプレイカバー（アクリル板）
* ゴム足

## ３．初期動作確認

袋①から基板を取り出します。  
出荷状態の基板は動作確認用ファームウェアが書き込み済みになっています。先ず正常動作することを確認します。  

#### PCに接続し認識されることを確認する
#### ピンセット等で端子を短絡させ入力されることを確認する
ピンセット等の導体で写真の2点を短絡して「1」が入力されることを確認してください。入力されない場合は、ストアサイトのトップページ下部にある、メールアイコンよりメッセージを下さい。

## ４．電子部品のはんだ付け

### 下記の順番で取り付けてください。
* R1：0603 チップ抵抗 2.2kΩ
* R8：0603 チップ抵抗 10kΩ
* C15～C22：0603 チップコンデンサ 30pF
* C23：トリマコンデンサ 20pF
* C24, C25：0603 チップコンデンサ 100nF
* U5, U6：タッチセンサーIC

### チップ部品のはんだ付け

フラックスを塗布してから、片方のパッドに予備はんだします。  
<img src="https://user-images.githubusercontent.com/3132296/184535738-2d754ac4-0466-409e-b996-f62616462318.jpg" width="25%">  
パッドをこてで温めながら部品をピンセットで固定して仮はんだします。  
<img src="https://user-images.githubusercontent.com/3132296/184535757-cba9bc4b-cfa4-48cb-b1e3-fbe4d7df799b.jpg" width="25%">  
反対側のパターンをはんだ付けしてから仮はんだした側も綺麗にはんだ付けします。  
<img src="https://user-images.githubusercontent.com/3132296/184535764-0454520a-ad06-4bf6-b21c-ffa48c4da335.jpg" width="25%">  
フラックスを除去します。  
<img src="https://user-images.githubusercontent.com/3132296/184535770-6dbacd05-e6ca-49a3-b7ca-29e98304d01c.jpg" width="25%">
<img src="https://user-images.githubusercontent.com/3132296/184535774-8ed4108c-405f-4446-87cc-94a1390d7b66.jpg" width="25%">  

### トリマコンデンサのはんだ付け

シルクに従った向きにはんだ付けしてください。  
<img src="https://user-images.githubusercontent.com/3132296/184582545-ad02b40f-f5ad-4f4f-bbea-aad645dbeab0.jpg" width="25%">
<img src="https://user-images.githubusercontent.com/3132296/184582561-86ccb1e2-e8df-4c02-900d-ec44eb890441.jpg" width="25%">  

### IC部品のはんだ付け

かどのパッド1か所に予備はんだします。  
<img src="https://user-images.githubusercontent.com/3132296/184561582-306fe682-8e2d-43ca-8b99-23c0f8856373.jpg" width="25%">  
パッドをこてで温めながら部品をピンセットで固定して仮はんだします。  
```
注意
IC部品には向きがあります！シルクの線の目印とICのポッチで向きを合わせてください。
```
<img src="https://user-images.githubusercontent.com/3132296/184566023-e8063e86-b14c-4699-9d6a-394cc4821440.jpg" width="25%">  
他の足にはんだ付けします。  
<img src="https://user-images.githubusercontent.com/3132296/184561634-93ea5f32-274f-4d13-8f81-7fd14d523529.jpg" width="25%">  
フラックスを除去します。  
<img src="https://user-images.githubusercontent.com/3132296/184561660-ad2d7693-f5e3-45f5-899e-d777de74e72f.jpg" width="25%">  

## ５．OLEDのはんだ付け

袋③からOLEDを取り出し、はんだ付けします。  
取り付ける前にコネクタに黄色のテープが張り付けられていることを確認します。剝がれている場合はセロハンテープ等を貼り付けて絶縁してください。  
<img src="https://user-images.githubusercontent.com/3132296/184564560-0312b95a-ce82-48d5-9333-46bf7f7f98fb.jpg" width="25%">
<img src="https://user-images.githubusercontent.com/3132296/184563860-c64b7062-c393-49ea-8d0d-c242a7aab497.jpg" width="25%">  

裏側の足はニッパーで切り取ってください。  
<img src="https://user-images.githubusercontent.com/3132296/184563870-56463e8f-26a6-4ba6-9849-d4e471471e3b.jpg" width="25%">
<img src="https://user-images.githubusercontent.com/3132296/184563874-a1ba4da2-2d5c-40ec-8a96-85fd644c42a3.jpg" width="25%">  

```
ワンポイント
OLEDの足は固いので大き目のニッパーを利用してください。
また事前にマスキングテープで足をとめておくと足が飛び散らないようにできます。
```

## ６．RGBLEDのはんだ付け

```
LEDをはんだ付けしてもLEDが光らない場合は先に下記のtestファームウェアに書き換えてから作業してみてください。
https://github.com/policium/grin_rc/tree/main/firmware
```

RGBLEDは番号の小さい順にはんだ付けしてください。また行ごとにLEDの向きが違うため気を付けてください。  
袋④からRGBLEDを取り出し、三角の目印とRGBLEDの足の切り欠きを合わせながら、穴にRGBLEDを差し込みます。  
<img src="https://user-images.githubusercontent.com/3132296/184566091-fd26ca73-329e-4cd8-9d70-92109d34ba1f.jpg" width="25%">  

フラックスを塗布してからはんだ付けします。RGBLEDは熱に弱いため長時間温めすぎないようにしてください。  
<img src="https://user-images.githubusercontent.com/3132296/184561978-fc616f62-c0b6-46b9-bc6b-7c01f51278b3.jpg" width="25%">
<img src="https://user-images.githubusercontent.com/3132296/184561982-893cc023-a365-495e-ad32-d99394312fc1.jpg" width="25%">  

フラックスを除去します。  
<img src="https://user-images.githubusercontent.com/3132296/184562003-3bc0e751-550e-4e33-9e28-217fe200ed0f.jpg" width="25%">  

PCに接続してLEDが点灯することを確認します。RGBLEDは番号順に通信しているため、  
点灯しないRGBLEDがある時は、点灯しないRGBLEDとひとつ前のRGBLEDを確認してください。  

## ７．スイッチソケットのはんだ付け

袋④からソケットを取り出し、穴に差し込みフラックスを塗布します。  
```
注意
ソケットには向きがあるためシルクに従って注意して差し込んでください。
向きを間違えるとソケットが破損する恐れがあります。
```
<img src="https://user-images.githubusercontent.com/3132296/184566942-91ed057b-3136-411e-ac8c-6533ad874014.jpg" width="25%">  

はんだ付けし、フラックスを除去します。  
```
注意
ソケットが浮かないように注意してください。接触不良の原因になります。
```
<img src="https://user-images.githubusercontent.com/3132296/184567210-c9687893-0d89-4d8a-8be0-f78a6f19f538.jpg" width="25%">  

```
ワンポイント
スイッチとスイッチプレートを先に取り付けてから作業すると楽にソケットをはんだ付け出来ます。
その時、先にスタビライザーを取り付けることを忘れないでください！
```

## ８．タッチセンサーの調整

タッチセンサーの感度を調整します。トリマコンデンサを1周回すと感度高～低を繰り返すようになっています。  

テキストエディタを開いた状態でPCに接続します。  

タッチセンサーが反応するとOLEDに「TAP」を表示するようになっています。トリマコンデンサを回し、何もしなくても反応する状態から反応しなくなるところまで回転してください。反応しなくなるところからさらに15度回転します。スイッチパネル上からタッチして「TAP」が表示されることを確認してください。調子が悪い場合は微調整します。  

## ９．ボトムプレートの取り付け

袋⑤から低頭ねじ短と両めねじスペーサーM2x3mmを4個ずつ取り出し、4か所に取り付けます。  
![GRIN_RC_bottom_1](https://user-images.githubusercontent.com/3132296/188760339-a5c32d42-2da7-4533-b665-5af4510d60f8.png)

袋⑤から低頭ねじ長と両めねじスペーサーM2x3mmを3個ずつ取り出し、3か所に取り付けます。  
![GRIN_RC_bottom_2](https://user-images.githubusercontent.com/3132296/188760380-84f08afe-6251-4de5-be64-1ae502353ff0.png)

袋⑤から低頭ねじ短と両めねじスペーサーM2x5mmを1個ずつ取り出し取り付けます。  
![GRIN_RC_bottom_3](https://user-images.githubusercontent.com/3132296/188760392-72a24b13-e2ac-40c5-8934-d73009b65aa0.png)

基板をボトムプレートに重ねます。  

## １０．スイッチプレート／スイッチの取り付け

※スイッチプレートとスイッチのはめあいが硬めになっています。スイッチの爪および端子を傷めないように慎重に取り付けてください。

袋⑥から両めねじスペーサーM2x6mmを3個取り出し取り付けます。
![GRIN_RC_pcb](https://user-images.githubusercontent.com/3132296/188761709-7392534e-0ecc-44b5-b47a-4761839bc401.png)

スタビライザーをスイッチプレートに取り付けてください。必要であれば事前にグリスを塗布してください。  
裏から見た様子です。  
<img src="https://user-images.githubusercontent.com/3132296/184582858-4af13b18-ccd3-404b-a1b1-adef978634f5.jpg" width="25%">  

先にスイッチプレートにいくつかスイッチを取り付けます。  

スイッチプレートを基板に重ねます。スイッチの端子を曲げないように気を付けてください。  

袋⑥から低頭ねじ中とM2ワッシャー黒を4個ずつ取り出し、基板とスイッチプレートの間にM2ワッシャー黒を挟みながら4か所に取り付けます。  
![GRIN_RC_top_1](https://user-images.githubusercontent.com/3132296/188760863-b3fa8d52-41c2-4f89-86fc-ff132f58ff5d.png)

袋⑤から低頭ネジ短を1個取り出し、1か所に取り付けます。  
![GRIN_RC_top_2](https://user-images.githubusercontent.com/3132296/188761060-ef044fed-29c2-47a9-b4c3-6d23ac066c75.png)

スイッチを取り付けていきます。  

スイッチの端子に気を付けながらスイッチを重ねます。  

ピンセットで爪を抑えながら押し込みます。（硬めなので手だけで押し込むとツメが曲がる可能性があります）  

## １１．ディスプレイカバーの取り付け

袋⑦からディスプレイカバーを取り出し、保護紙を取り外します。

袋⑦からM2精密ねじを3個取り出し、ディスプレイカバーを取り付けます。

## １２．ファームウェアの書き込み

[こちら](https://github.com/policium/grin_rc/tree/main/firmware)からファームウェアをダウンロードしファームウェアを書き込みます。
標準ファームはgrin_keebs_grin_rc_default.zipです。VIA用は作成予定です。
ファームウェアの書き込みにはQMK Toolboxを利用してください。
タクトスイッチを長押しすることでDFUモードになります。

## １３．動作確認

ファームウェアの書き込みが完了するとキーボードとして利用できるようになります。すべてのスイッチが入力されることを確認をして、必要であれば修正してください。  
作業は以上になります。お疲れさまでした。


