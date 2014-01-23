{
    "document-title": "後期最終成果発表会",
    "footer-text": "2014/1/24　後期最終成果発表会", 
    "aspect-ratio": 1.33,
    "show-footer-in-title-page": false
}

!SLIDE

<center>

<br>
# 高度ICT演習向け<br>eポートフォリオシステムの開発 
<style>
  #meibo{
    margin-top: 10px;
  }
</style>

<br><br>

<table id="meibo" style="margin-left: 6.5em">
<tr>
<td width=35%>B4</td>
<td width=35%>B3</td>
<td width=35%>B2</td>
</tr>
<tr>
<td>中野 佑</td>
<td>赤木 勇極</td>
<td>内山 武尊</td>
</tr>
<tr>
<td>長崎 洸祐</td>
<td>菅野 久樹</td>
<td>川口 拓郎</td>
</tr>
<tr>
<td>山本 賢人</td>
<td>佐藤 祐磨</td>
<td>諸原 聖</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>中田 友貴</td>
<td>水尻 裕人</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>教員</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>神谷 年洋</td>
</tr>
</table>
</center>

!SLIDE
## 目次
<div style="display:-webkit-box;display:-moz-box;">
<div style="width:50%; margin:0em e3m;">
- 授業の分類と本学の現状
- 本学のPBLにおける問題
- 一般的なeポートフォリオシステム
-要求開発
  - ヒアリング
  - 機能の洗い出し
  - プロトタイピング

</div>
<div style="width:50%; margin:0em e3m;">
- 実装
  - 開発範囲の設定
  - 開発体制について
- スケジュール
- 学び
</div>
</div>

!SLIDE
## 背景

<div style="display:-webkit-box;display:-moz-box;">
<div style="width:50%; margin:0em e3m;">
<p> <b>受動的な学習(例: 座学)</b></p>
* 座学の授業で教師による</br>一方的な知識伝達
* 本学ではMoodle\*で支援</br>されている
</div>
<div style="width:50%; margin:0em e3m;">

<p> <b>能動的な学習(例: 高度ICT演習)</b></p>
* 学習者が自主的に問題設定し、</br>活動する
* 本学のPBLには学習を支援する</br>システムが無い
</div>
</div>
</div>
</div>
<div style="display:-webkit-box;display:-moz-box;">
<div style="width:50%; margin:0em 1em;">
<img src="img/lecture.jpg" style="width:70%;height:70%;">
</div>
<div style="width:50%; margin:0em 1em;">
<img src="img/PBL.jpg" style="width:70%;height:70%;">
</div>
</div>

<p style="font-size:75%;margin-left:10px;　">\*Moodle: CMS(Course Management System)の一種</p>


!SLIDE

## 問題
- 活動記録がないので見返すことができない
- 学生間で、<font color = #ff0000>どのように学習しているか共有できていない</font>
- 学生ごとに活動が異なるため、<font color = #ff0000>教員は学生に合わせた指導ができない</font>
</br>
<center>&#11015;</center>
</br>
<p>これらの問題はeポートフォリオシステムで解決することができる</p>

!SLIDE

## eポートフォリオシステムとは
- <font color = #ff0000>学習者個人に重きを置いた</font>、学習活動を可視化する仕組み
- <font color = #ff0000>授業に合わせて構築する必要がある</font>
- 大学によっては全学的に導入している例もある
- 既存のeポートフォリオシステムとして、Mahara、Sakaiなどがある
<font size="3">引用文献:小川賀代，小村道昭，大学力を高めるeポートフォリオ〜エビデンスに基づく教育の質保証を目指して〜，2012</font>

!SLIDE

## 目的
- 高度ICT演習における
  - 学生の<font color = #ff0000>学習の振り返り</font>及び<font color = #ff0000>担当教員の指導を支援する</font>
  - 担当教員と学生からeポートフォリオシステムの要件を収集し、</br>取り入れながら開発をする
<!-- -->
<!-- - プロジェクトの進め方や最新技術に触れながら開発に関する知識を修得する(教育系PBLの目的) -->
<!-- -->

!SLIDE
## 本プロジェクトでの開発工程
-要求開発
  - ヒアリング(2回)
  - 機能の洗い出し
  - プロトタイピング(2回)
- 実装
  - 開発範囲の設定
  - 使用技術の選定

!SLIDE
## 調査
- 既存のeポートフォリオシステムを比較した

<table id="solid" width="100%" align="center" >
<tr>
	<th></th>
	<th>成果物の共有<br>のしやすさ</th>
	<th>(教育工学的)<br>振り返り</th>
	<th>UI<br>(操作性)</th>
	<th>公開<br>eポートフォリオ\*</th>
	<th>カスタマイズ性</th>
</tr>
<tr align="center">
<td><img src="img/SakaiLogolg.jpg" width="60"></td>
	<td>○</td>
	<td>○</td>
	<td>×</td>
	<td>×</td>
	<td><font color = #ff0000>×</font></td>
</tr>
<tr align="center">
	<td><img src="img/Mahara_logo.png" width="70"></td>
	<td>○</td>
	<td>×</td>
	<td>○</td>
	<td>○</td>
	<td><font color = #ff0000>×</font></td>
</tr>
</table>
<br>
<font style="font-size: 60%; margin-top: 1.5em;">引用文献:宮崎誠「eポートフォリオシステム評価 - Mahara vs Sakai OSP -」</br>(法政大学情報メディア教育研究センター研究報告 Vol.25 特別号 2011年) </font>
</br></br>
- 既存のeポートフォリオシステムは使用せずに開発を行う
  - 要求を引き出しながら<font color = #ff0000>適応的に開発する必要がある</font>ため
<p style="font-size:75%;margin-left:10px;　">\*公開eポートフォリオ：学外にも公開されるポートフォリオ</p>

!SLIDE

## 第1回ヒアリング
- 高度ICTコースのコース長へeポートフォリオシステムについて</br>ヒアリングを行った
  - <font color = #ff0000>PDCAサイクルを回せるように</font>して欲しい
  - 動くシステムを定期的に見せて欲しい
<br>
### 洗い出された機能一覧
- ゴール管理機能
- 日誌投稿機能
- 成果物管理機能
- eポートフォリオ作成機能
- フィードバック機能
- グループ管理機能

!SLIDE

## プロトタイピング１回目
- ホワイトボードを使い、<font color = #ff0000>メンバー間で話し合いながら</font>作成
- iPadのPoPソフトを使ってデモができるようにした
<img style="width:30%;" src="img/IMG_0042.JPG" align = "center">
<img style="width:30%;" src="img/IMG_0043.JPG" align = "center">
<img style="width:30%;" src="img/IMG_0045.JPG" align = "center">

!SLIDE

## 第2回ヒアリング
- ７月にICTコース長にヒアリング
  - 機能のイメージがわかないので利用例が欲しい
  - 画面設計レベルでプロトタイピングして欲しい
  - 新しい機能の要求はなく、機能の具体化をして欲しい
!SLIDE

## プロトタイピング２回目
- ヒアリングより再度プロトタイピングを行った
- 実装するシステムをメンバー間で共有するために画面設計を行った
<img style="width:100%;" src="img/goal.png">

!SLIDE

## 洗い出された機能一覧（再掲）
- ゴール管理機能
- 日誌投稿機能
- 成果物管理機能
- eポートフォリオ作成機能
- フィードバック機能
- グループ管理機能

!SLIDE
## ゴール管理機能
- 学習者が<font color = #ff0000>学習目標をたてて</font>、目標達成までの過程を可視化する機能
 - 長期的なゴールが入力できる
 - ゴールの達成度をバーンアップチャート\*で表示する
<tr>
 <img src="img/screendiagram/goalrogo-03.png" style="width:55%;height:55%;float:left;border:solid thin;">
</tr>
<tr>
 <p style="font-size:75%;margin-left:40px;margin-top:50px"><b>\*ゴールの数が増減した場合でも進捗状況が判断しやすい</font></p>
</tr>

!SLIDE
## 日誌投稿機能
- 日々の活動をから、<font color = #ff0000>新たな発見や学び、困ったこと</font>を投稿できる
 - 短い文章で、システムに蓄積できる
 - ゴールと日誌の関連付けがされる

 <img src="img/screendiagram/personalrogo-01.png" style="width:45%;height:45%;border:solid thin;">

!SLIDE
## 成果物管理機能
- 学習活動によって作成した成果物をシステムに蓄積する
 - システムへPDFやソースコードのアップロードなどが行える
 - WebDAV機能で、ファイラーを使ってアップロードできる
   <img src="img/d&dImage.png" style="width:72%;height:72%;border:solid thin;">

!SLIDE
## eポートフォリオ作成機能
- <font color = #ff0000>学習活動を振り返り</font>、ひとつの形式にまとめる機能
 - ゴール、日誌、成果物からそれぞれ載せることができる
 - PDFを作成することができる
 - 学外の人向けにeポートフォリオを公開することができる
 
  <img src="img/screendiagram/portfoliologo-02.png" style="width:45%;height:45%;border:solid thin;">

!SLIDE
## フィードバック機能
- 学習者が作成したeポートフォリオに対してコメントを記入する
 -想定する用途としては、教員が学習者の学習状況を把握し、<font color = #ff0000></br>指導に用いる</font>

 <img src="img/feedback.png" style="width:45%;height:45%;border:solid thin;">

!SLIDE
## 実装範囲の設定

<img style="width:100%; margin-top:8%;" src="img/tellfn.png" align = "center">
- <font color = #ff0000>ゴール設定、日誌投稿、eポートフォリオ作成機能</font>に力を入れて開発した
- 成果物管理機能は一部機能を限定して開発した
- フィードバック機能やグループ管理機能は実装範囲外とした

!SLIDE

## 現状(1/3)

### ゴール管理機能
<ul>
<ul>
<li class="li-ballot-checked">長期的なゴールの入力</li> 
<li class="li-ballot-checked"> 短期的なゴールの入力</li>
<li class="li-ballot-checked"> グラフ表示</li>
<li class="li-ballot-checked"> ゴールの削除</li>
</ul>
</ul>


### 日誌投稿機能

<ul>
<ul>
<li class="li-ballot-checked">日誌の投稿</li> 
<li class="li-ballot-checked"> 短期的なゴールとの結びつけ</li>
<li class="li-ballot">日誌をゴールによって分類</li>
<li class="li-ballot"> 他人の日誌を閲覧</li>
</ul>
</ul>

!SLIDE

## 現状(2/3)

### 成果物管理機能
<ul>
<ul>
<li class="li-ballot-checked">Webからのファイルアップロード</li> 
<li class="li-ballot">WebDAV機能によるアップロード</li>
</ul>
</ul>

</br>
### eポートフォリオ作成機能
<ul>
<ul>
<li class="li-ballot-checked">成果物管理のみ載せる</li> 
<li class="li-ballot">ゴール、日誌から載せる</li>
<li class="li-ballot">エクスポートができる</li>
<li class="li-ballot">学外向けに公開できる</li>
</ul>
</ul>


!SLIDE

## 現状(3/3)

### グループ管理機能
<ul>
<li class="li-ballot">グループ管理機能は実装しなかった
<ul>
<li>グループに持たせる役割を決めることができなかった</li>
</ul>
</li>
</ul>

</br>
### フィードバック機能
<ul>
</li>
<li class="li-ballot">フィードバック機能は実装できなかった
<ul>
<li>LDAP認証ができておらず他の人との連携ができなかった</li>
<li>
コメント機能は実装中
</li>
</ul>
</ul>

!SLIDE

## 開発体制
<center>
<img src="img/kaihatsutaisei.png" style="width:50%;height:50%;">
</center>

!SLIDE

## 全体のスケジュール
<img style="width:95%" src="img/sukesuke.png" align = "center">

!SLIDE

## 学び
<ul>
<li>演習を通して自分の知らなかった技術を知ることができたので</br><font color = #ff0000>視野が広がった</font></br>(B4・情報デザインコース)
<li><font color = #ff0000>チケット駆動開発</font>とGitの仕組みについて知れた</br>(B2・情報システムコース)
<li>ソフトウェア開発の<font color = #ff0000>一連の流れを体験する</font>ことができた</br>(B2・情報システムコース)
<li>ペーパープロトタイピングの手法など<font color = #ff0000>デザインの技術を</br>取り入れることができた</font></br>(B4・情報システムコース)
</ul>

!SLIDE

## まとめ
- 受動的学習と能動的学習の説明
- eポートフォリオによる能動的学習の支援
- 既存のeポートフォリオシステムについて説明した
- PDCAサイクルを実現するeポートフォリオシステムを実現した
- 実装範囲を定めてeポートフォリオシステムを開発
- 開発体制や学びについて説明した
<!--結論だけを書く-->
