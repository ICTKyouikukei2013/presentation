{
    "document-title": "後期最終成果発表会",
    "footer-text": "2014/1/24　後期最終成果発表会", 
    "aspect-ratio": 1.33,
    "show-footer-in-title-page": false
}

!SLIDE

<center>

## 高度ICT演習向け<br>eポートフォリオシステムの開発 
<style>
  #meibo{
    margin-top: 10px;
  }
</style>

<table id="meibo">
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
- 高度ICT演習について
- 未来大のPBLにおける問題
- 一般的なeポートフォリオシステム
- 前期の活動
 - 要件収集
 - ヒアリング
 - ペーパープロトタイプ
 - 機能の洗い出し
</div>
<div style="width:50%; margin:0em e3m;">
- 後期の活動
 - 実装範囲の設定
 - 開発体制
- スケジュール
- 学び
</div>
</div>

!SLIDE
## 背景(1/2)
<img style="width:320px; float:right; margin:0 20px 0 20px;"  src="img/DSCF0528.JPG" align = "right" >
- 公立はこだて未来大学(以下、未来大)にはPBL\*型の授業として<font color = #ff0000>高度ICT演習</font>がある
 - <font color = #ff0000>単位が出ない中</font>、学生が自主的に</br>活動を行う
 - ソフトウェア開発のプロセスを経験し、基礎となる知識やスキルを習得する
</br></br>
<p style="font-size:63%;margin-left:10px;">\*PBL: Project/Problem Based Learningの略。問題定義から解決までを学習者が主体的に学習を進めていく方法。</p>

!SLIDE
## 背景(2/2)

<div style="display:-webkit-box;display:-moz-box;">
<div style="width:50%; margin:0em e3m;">
### 受動的な学習(例: 座学)
* 座学の授業で教師による</br>一方的な知識伝達
* テストによる評価が行われる
</div>
<div style="width:50%; margin:0em e3m;">

### 能動的な学習(例: PBL)
* 学習者が自主的に問題設定し、</br>活動する
* 活動過程を含めた評価が必要
</div>
</div>
<div style="display:-webkit-box;display:-moz-box;">
<div style="width:50%; margin:0em 1em;">
<img src="img/5430587649_7669371a8f.jpg" style="width:70%;height:70%;">
</div>
<div style="width:50%; margin:0em 1em;">
<img src="img/PBL3.jpg" style="width:70%;height:70%;">
</div>
</div>

!SLIDE

## 問題
<ul>

<li>未来大の高度ICT演習には能動的な学習を支援するシステムが無い
<ul>
<li class="li-rightarrow">活動記録がないので見返す事ができない</li>
<li class="li-rightarrow"><font color = #ff0000>学生がどのように学習しているかわからない</font></li>
</ul>
</li>
<li>教員は学生に合わせた指導ができない
<ul>
<li class="li-rightarrow"><font color = #ff0000>学生ごとに活動が異なるため</font></li>
</ul>
</li>
</ul>
<ul>
<li>受動的な学習の中で、未来大ではMoodle\*を導入している</li></ul>
</br></br>
<p style="font-size:75%;margin-left:10px;">\*Moodle: CMS(Course Management System)の一種</p>

!SLIDE

## 目的
- 高度ICT演習における
  - 学生の<font color = #ff0000>学習の振り返り</font>及び<font color = #ff0000>担当教員の指導を支援する</font>
  - 担当教員と学生からeポートフォリオシステムの要件を収集し、</br>取り入れながら開発をする
<!-- -->
<!-- - プロジェクトの進め方や最新技術に触れながら開発に関する知識を修得する(教育系PBLの目的) -->
<!-- -->

!SLIDE

## 一般的なeポートフォリオシステム
<ul>
	<li>システムを用い学習目標を立てることができる</li>
	<li>大学ごとにeポートフォリオシステムを構築しなければならない</li>
	<li>金沢工業大学では全体に導入している例もある</li>
  <li>自由に利用できるように公開されているものとしてMahara, sakaiなどがある</li>
</ul>
</br></br>
<p style="font-size=55%;">eポートフォリオ: 活動過程を人に見せるために、活動の証拠となるものや生成した成果物を載せたもの</p>

!SLIDE
<!-- ## 紙のポートフォリオと比較して -->
<!-- * ネットワークを介したフィードバックや共同編集が可能 -->
<!-- * データが経年劣化しない -->
<!-- * 大量のデータを一つのPCで管理できる -->
<!--  -->
<!-- <img style="width:320px;" src="img/2418668807_2928b77d03.jpg" align = "center"> -->
<!-- <br><p align = center >http://www.flickr.com/photos/lfr/2418668807/</p> -->

## 既存のeポートフォリオ 
- 既存のeポートフォリオシステムを比較した

<img style="width:100%;" src="img/hikaku_1.png"><br>

<font size="3">引用文献:宮崎誠「eポートフォリオシステム評価 - Mahara vs Sakai OSP -」</br>(法政大学情報メディア教育研究センター研究報告 Vol.25 特別号 2011年) </font>
</br></br>
- 要求を引き出しながら適応的に開発する必要がある

<!-- <img style="width:20%; margin: 0 20px 0 20px;" style = "float:right" src="img/SakaiLogolg.jpg" > -->
<!-- <img style="width:30%"  style="float:right" src="img/Mahara_logo.png" > -->


!SLIDE

## 前期の活動
- 高度ICT演習の担当教員によるeポートフォリオ要求定義会議
- 第1回ヒアリング
- ペーパープロトタイプ1回目
- 第2回ヒアリング
- ペーパープロトタイプ2回目
- 機能の洗い出し

!SLIDE

## 第1回ヒアリング
- 高度ICT演習の担当教員にeポートフォリオシステムについてヒアリングを行った

  - 高度ICT演習向けの開発をして欲しい
  - PDCAサイクルを回せるようにして欲しい
  - 動くシステムを定期的に見せて欲しい

!SLIDE

## ペーパープロトタイプ１回目
<img style="width:30%;" src="img/IMG_0042.JPG" align = "center">
<img style="width:30%;" src="img/IMG_0043.JPG" align = "center">
<img style="width:30%;" src="img/IMG_0045.JPG" align = "center">

!SLIDE

## 第2回ヒアリング
- ７月にICTコース長にヒアリング
  - 学生はどのように使うのか
  - 先生はどのように使うのか
  - どのような機能が必要か

!SLIDE

## ペーパープロトタイプ２回目
- 実装するシステムをメンバー間で共有するために画面設計を行った
<img style="width:100%;" src="img/goal.png" align = "center">

!SLIDE

## 洗いだした機能一覧
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
 - ゴールの達成度をグラフで表示する

 <img src="img/screendiagram/goalrogo-03.png" style="width:53%;height:53%;float:left">
 <p style="font-size:75%;margin-left:10px;margin-top:50px"><b>\*ゴールの数が増減した場合でも進捗状況が判断しやすい</font></p>

!SLIDE
## 日誌投稿機能
- 日々の活動をから、<font color = #ff0000>新たな発見や学び、困ったこと</font>を投稿できる
 - 短い文章で、システムに蓄積できる
 - ゴールと日誌の関連付けがされる

 <img src="img/screendiagram/personalrogo-01.png" style="width:53%;height:53%;">

!SLIDE
## 成果物管理機能
- 活動によって生成された成果物をシステムに蓄積する
 - システムへPDFやソースコードのアップロードなどが行える
 - Webdav機能<!--多分伝わらない-->で、ファイルソフトを使ってアップロードできる
   <img src="img/d&dImage.png" style="width:72%;height:72%;">

!SLIDE
## eポートフォリオ作成機能
- <font color = #ff0000>行ってきた活動を振り返り</font>、ひとつの形式にまとめる機能
 - ゴール、日誌、成果物からそれぞれ載せることができる
 - エクスポートすることができる
 - 学外の人向けにeポートフォリオを作成することができる
 
  <img src="img/screendiagram/portfoliologo-02.png" style="width:45%;height:45%;">

!SLIDE
## フィードバック機能
- 教員が、学習者の学習状況を把握し、<font color = #ff0000>指導するのを支援する</font>機能
 - 学習者が作成したeポートフォリオへコメントをする
 <img src="img/feedback.png" style="width:55%;height:55%;">

!SLIDE

## PDCAサイクルと機能の対応
<img src="img/portbacker.png" style="width:53%;height:53%;" align = "right">
### Plan  
  <p style="margin-left: 20pt"><span class="test"> ゴール管理機能</span></p>
### Do
  <p style="margin-left: 20pt">
  <span class="test"> 日誌投稿機能</span>
  </br>
  <span class="test"> 成果物管理機能</span>
  </p>
### Check
  <p style="margin-left: 20pt">
  <span class="test"> eポートフォリオ作成機能</span></p>
### Action
  <p style="margin-left: 20pt">
  <span class="test"> フィードバック機能</span>
  </p>
<!-- -->
<!-- ## システム全体図 -->
<!-- <center> -->
<!-- <img src="img/portbacker.png" style="width:53%;height:53%;"> -->
<!-- </center> -->
<!--  -->

!SLIDE

## 後期の活動
- 実装範囲の設定
- 開発

<!-- - Gitによる分散開発 -->
<!-- - Issueを使ったチケット駆動開発 -->

- 運用
<!-- - サーバを用意し実環境での動作確認 -->

!SLIDE

## ゴール管理機能
- 以下の機能は実装済み
  - 長期的なゴールの入力
  - 短期的なゴールの入力
  - グラフ表示
  - ゴールの削除

!SLIDE

## 日誌投稿機能
- 日誌をゴールによって分類する機能は実装しなかった
- 他の人との連携ができないので、他人の日誌を閲覧する機能は実装しなかった
- 以下の機能は実装済み
  - 日誌の投稿
  - 短期的なゴールのとの結びつけ

!SLIDE

## 成果物管理機能
- owncloudとの連携ができていないため、手動でのアップロードのみ実装
- ドラッグ＆ドロップによるアップロードは実装しなかった

!SLIDE

## グループ管理機能
- グループに持たせる機能を決めることができず、グループ管理機能は実装しなかった

!SLIDE

## フィードバック機能
<ul>
<li>認証ができておらず他の人との連携ができなかった</li>
<ul>
<li class="li-rightarrow">このため、フィードバック機能は実装できなかった</li>
</ul>
</ul>

!SLIDE

## 開発体制
<center>
<img src="img/kaihatsutaisei2.png" style="width:55%;height:55%;">
</center>

!SLIDE

## 全体のスケジュール
<img style="width:75%" src="img/sukesuke.png" align = "center">

!SLIDE

## 学び
<ul>
<li>演習を通して自分の知らなかった技術を知ることができたので視野が広がった</br>(B4・情報デザインコース)
<li>チケット駆動開発とGitの仕組みについて知れた</br>(B2・情報システムコース)
<li>ソフトウェア開発の一連の流れを体験することができた</br>(B2・情報システムコース)
<li>Gitを利用した分散開発の仕組みを知ることができた</br>(B2・情報システムコース)
</ul>

!SLIDE

## まとめ
- 高度ICT演習について
- 未来大のPBLにおける問題
- 高度ICT演習の学習および指導を支援
- 前期の活動
 - 要件収集
 - 機能の洗い出し
 - ペーパープロトタイプ
- 後期の活動
 - 開発
<!-- 目次と同じ感じですω・ -->

