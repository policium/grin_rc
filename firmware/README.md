# GRIN RCのファームウェア書き込み方法
[QMK toolbox](https://github.com/qmk/qmk_toolbox)から最新の[リリース](https://github.com/qmk/qmk_toolbox/releases)をダウンロードしてインストールしてください。  
QMK toolbox を起動してOpenボタンをクリックしてファームウェアのbinファイルを選択します。  

ファームウェアには以下があります。
* grin_keebs_grin_rc_default.bin　標準ファームウェア  
* grin_keebs_grin_rc_via.bin　VIA/REMAP用ファームウェア
* grin_keebs_grin_rc_test.bin　動作確認用ファームウェア  

Auto-Flashにチェックを入れます。  
GRIN RCをPCに接続します。  
GRIN RCのリセット用タクトスイッチを長押し（押し続ける）します。（短く押すとリセット。長く押すとDFUモードになります。）  
自動で書き込みが始まり、完了するとキーボードがリセットされます。
