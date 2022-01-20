<div align="center">
<img src="https://raw.githubusercontent.com/jishinmonitor/meta/main/App-Github-Banner.png" alt="Jishin Alert">
</div>

> ⚠️ **警告:** このファイルは、機械翻訳を使用しています。もし、間違いを見つけたり、翻訳を改善したい場合は、プルリクエストをお願いします。

[英語版を読む (Read English version)](https://github.com/jishinalert/meta/blob/main/README.md)

# [近日発売] 地震監視
**地震・津波警報 Android版**
EEW、地震情報、津波警報を配信し、気象庁やNIEDなど政府の公式ソースから情報を引き出すAndroid向け日本地震モニタリングアプリ。

## 特徴
* NIED観測点からのリアルタイム震度・PGA情報
* 緊急地震速報と津波警報
* マルチイベントディスプレイ対応
* 過去に発生した地震の詳細情報

## 機能ロードマップ
| 特徴 | 開始日 | 完了日 |
|---------|--------------|----------------|
| 観測点データベース ローマ字変換 | 2022年1月17日 | 停止中 |
| バックエンドアプリサーバー | TBD | TBD |
| NTP同期 | TBD | TBD |
| 地震情報レポート表示 | TBD | TBD |
| 強震モニタマップ | TBD | TBD |
| EEW通知 | TBD | TBD |
| 津波警報表示 | TBD | TBD |

## ライセンスと責任
* Jishin Alertはクローズドソースのプロプライエタリなソフトウェアです。含まれる資産、リソース、画像、音声を許可なく逆コンパイル、リバースエンジニアリング、再利用することを禁じます。
* 本アプリは、あくまでも補助的なツールとしてご利用ください。**このアプリに関連する保証はありません。このアプリを使用することで発生するいかなる問題にも責任を負いかねます。** 例えば、アプリが作動せず、いつの間にか家具に押しつぶされたり、家に津波が来たり、誤報が発せられて逃げたりしても、弊社は責任を負いません。**気象庁のホームページ、NHK、エリアメールなどの公式ソースが常にこのアプリより優先されます。** 疑問がある場合は、**それらをご確認ください。**
* Jishin Alert は、気象庁の地震予報や緊急地震速報を受信します。[ご利用にあたっては、その仕組みや注意点をご理解の上、ダウンロード・ご利用ください。](https://www.jma.go.jp/jma/en/Activities/eew.html)

## ダウンロード
このプロジェクトはまだ完成していません。

## プログラミング言語
Kotlin & Go

## クレジット
* 地図データ：Google Maps
* 防災科学技術研究所（NIED）によるEEW、リアルタイム震度、PGAデータ
* P2PQuakeによる津波情報

特別に感謝します:
* 画像解析アルゴリズムにJQuakeを採用 [(多項式補間を使用して強震モニタ画像から数値データを決定する)](https://qiita.com/NoneType1/items/a4d2cf932e20b56ca444) と [(津波警報地域 GeoJSON)](https://gist.github.com/wolf20482/864da7dd76b31efe55c6a7e025a6e015)
* [観測点データベース用](https://github.com/jishinalert/observation-points) [ingen084](https://github.com/ingen084)
