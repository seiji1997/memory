# memory

## 半導体メモリについて
SSDは半導体メモリ(NAND型フラッシュメモリ)を記憶部分に用いた記憶装置<br>
- 情報の読み書き消去を行う。
  - 重要: 読み書き消去の単位
- チップ、プレーン、ブロック、ページ、セクター(セグメント)のような単位でメモリーチップは構成される。
  - 重要: メモリチップの構成
- 読み出しデータの異常を訂正する
  - 重要: 誤り訂正符号(ECC)

## 【概念】
NANDフラッシュメモリの読み書きについて起こる現象について知る<br>

以下の観点で資料を見る<br>
-	読み書き消去は「どのように」「どの単位で」行われるか
-	データの読み書きにて起こるデータ誤りとは
-	データ誤りは何が原因か(program disturb, read disturb, data retention)
-	誤りの訂正方法は何か・訂正できるか

上記をとらえた後<br>
-	SSD内のコントローラからNANDメモリに対する書き込み消去命令
-	その他書き込みの信頼性
-	効率のよい読み出し方法
-	SSDの信頼性指標とは

「SSDの寿命を延ばすために必要なWAF(書き込み効率)のおなはし(第1回)」<br>
https://www.paltek.co.jp/techblog/tag/memory<br>
-	メモリ基本講座
-	半導体メモリとは
-	DRAMとは
-	NORとNANDとは
-	NAND応用製品(eMMC & SSD)
-	メモリ基本講座番外編


Logitec データ復旧技術センターの記事<br>
- フラッシュメモリとは
https://www.logitec.co.jp/data_recovery/column/vol_002/<br>

3次元フラッシュメモリについて<br>
-	キーのフラッシュメモリ
https://www.kioxia.com/ja-jp/rd/technology/bics-flash.html<br>


個人ブログ記事：フラッシュメモリの読み書き消去や、信頼性について<br>
-	メイントピック
https://progzakki.sanachan.com/technology/nand-flash-memory/<br>

フラッシュメモリの基礎知識<br>
-	フラッシュメモリ: SSDの記憶装置に使われる
https://www.pro.logitec.co.jp/houjin/usernavigation/hddssd/20220330/<br>

SSD/NAND 基礎講座<br>
-	1~42まで
-	”NANDフラッシュメモリの構造”
-	”ブロックマッピングとページマッピング”
-	”NANDフラッシュ_SLC　MLC　TLC　QLC　の違い”
-	”SSDにおけるウェアレベリングの概略”
-	”SSDにおけるガベージコレクションの概略”
https://www.sanei-j.com/html/column.html<br>

NANDフラッシュメモリの構造<br>
-	「NAND MEMORY CRYSTAL」
-	「MEMORY CHIP」
https://support.rusolut.com/portal/en/kb/articles/multi-plane-page-allocation-10-5-2020<br>

SSD Doujinshi<br>
https://www.kioxia.com/ja-jp/business/ssd/solution/doujinshi.html<br>

SSDの読み書きをコントロールする部分：SSDを長寿命化させる書き込み方法について<br>
https://www.kioxia.com/content/dam/kioxia/ja-jp/business/ssd/solution/doujinshi/asset/SSD-Doujinshi-1.pdf<br>

データの読み出し誤り訂正と誤り訂正符号(ECC)について<br>
https://www.kioxia.com/content/dam/kioxia/ja-jp/business/ssd/solution/doujinshi/asset/SSD-Doujinshi-2.pdf<br>
