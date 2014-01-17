{
    "footer-text": "2014/1/24　後期最終成果発表会", 
    "show-footer-in-tiatle-page": false
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
- 高度ICT演習について
- 未来大のPBLにおける問題
- 高度ICT演習の学習および指導を支援
- 前期の活動
 - 要件収集
 - 機能の洗い出し
 - ペーパープロトタイプ
- 後期の活動
 - 開発

!SLIDE
## 背景(1/2)
<img style="width:320px; float:right; margin:0 20px 0 20px;"  src="img/DSCF0528.JPG" align = "right" >
- 公立はこだて未来大学(以下、未来大)の特徴的な授業にPBLがありPBL型の授業として<font color = #ff0000>高度ICT演習</font>がある
 - <font color = #ff0000>単位が出ない中</font>、学生が自主的に</br>活動を行う
 - ソフトウェア開発のプロセスを経験し、基礎となる知識やスキルを習得する



!SLIDE
## 背景(2/2)

<div style="display:-webkit-box;display:-moz-box;">
<div style="width:50%; margin:0em e3m;">
### 受動的な学習(例: 座学)
* 座学の授業で教師による</br>一方的な知識伝達
* テストによる評価が行われる
</div>
<div style="width:50%; margin:0em e3m;">

### 能動的な学習(例: PBL*)
* 学習者が自主的に問題設定し、</br>活動する
* 活動過程を含めた評価が必要
</div></div>
<img src="img/5430587649_7669371a8f.jpg" style="width:30%;height:30%;margin:0px 90px;">
<p style="font-size:63%;margin-left:10px;"><b>\*PBL: Project/Problem Based Learningの略。問題定義から解決までを学習者が主体的に学習を進めていく方法。</p></b>

!SLIDE

## 問題
<ul>

<li>未来大の高度ICT演習には能動的な学習を支援するシステムが無い
<ul>
<li class="li-rightarrow">活動記録がないので見返す事ができない</li>
<li class="li-rightarrow"><font color = #ff0000>学生がどのように学習しているかわからない</font></li>
</ul>
</li>
<li>教員は学生に合わせた指導ができない。
<ul>
<li class="li-rightarrow"><font color = #ff0000>学生ごとに活動が異なるため</font></li>
</ul>
</li>
</ul>
<ul>
<li>受動的な学習の中で、未来大ではMoodle\*を導入している。</li></ul>
</br></br>
<p style="font-size:75%;margin-left:10px;"><b>\*Moodle: CMS(Course Management System)の一種</p></b>

!SLIDE

## 目的
- 高度ICT演習における
  - 学生の<font color = #ff0000>学習の振り返り</font>及び<font color = #ff0000>担当教員の指導を支援する</font>
  - 担当教員と学生からeポートフォリオシステムの要件を収集し、</br>取り入れながら開発をする
<!--
- プロジェクトの進め方や最新技術に触れながら開発に関する知識を修得する(教育系PBLの目的)
 -->

!SLIDE

## 一般的なeポートフォリオシステム
<ul>
<li>eポートフォリオは<font color = #ff0000>学習者の学習活動の可視化が可能</font>
</ul>
<ul>
<li>未来大で行われる能動的な学習には支援するシステムがない
<ul>
<li class="li-rightarrow">成果物が残らないので学生が後に振り返りが出来ない</li>
<li class="li-rightarrow">教員も学生の学習を確認が出来ないためアドバイスが出来ない</li>
</ul>
</li>
</ul>


!SLIDE
<!-- ## 紙のポートフォリオと比較して
* ネットワークを介したフィードバックや共同編集が可能
* データが経年劣化しない
* 大量のデータを一つのPCで管理できる

<img style="width:320px;" src="img/2418668807_2928b77d03.jpg" align = "center">
<br><p align = center >http://www.flickr.com/photos/lfr/2418668807/</p> -->

## 既存のeポートフォリオ 
- 既存のeポートフォリオシステムを比較した

<img style="width:100%;" src="img/hikaku_1.png"><br>

<font size="2">引用文献:宮崎誠「eポートフォリオシステム評価 - Mahara vs Sakai OSP -」 (法政大学情報メディア教育研究センター研究報告 Vol.25 特別号 2011年) </font>

- 要求を引き出しながら適応的に開発する必要がある

<img style="width:20%; margin: 0 20px 0 20px;" style = "float:right" src="img/SakaiLogolg.jpg" >
<img style="width:30%"  style="float:right" src="img/Mahara_logo.png" >



!SLIDE

## 前期の活動
- 高度ICT演習の担当教員によるeポートフォリオ要求定義会議
- ICTコース長にヒアリング
- ペーパープロトタイプの作成
- 再度ICTコース長にヒアリング
- 機能の洗い出し
- ヒアリング結果からペーパープロトタイプを再度作成
!SLIDE

## ヒアリング（5月末）
高度ICT演習の担当教員にeポートフォリオシステムについての会議を開いた

- 高度ICT演習向けの開発をして欲しい
- PDCAサイクルを回せるようにして欲しい
- 動くシステムを定期的に見せて欲しい

!SLIDE

## PDCAサイクル
### Plan  
  <span class="test"> ゴール管理機能</span>
### Do
  <span class="test"> 日誌投稿機能</span>
  </br>
  <span class="test"> 成果物管理機能</span>
### Check
  <span class="test"> eポートフォリオ作成機能</span>
### Action
  <span class="test"> フィードバック機能</span>

!SLIDE

## システム全体図
<center>
<img src="img/portbacker.png" style="width:53%;height:53%;">
</center>

!SLIDE

## ペーパープロトタイプ１回目
<img style="width:30%;" src="img/IMG_0042.JPG" align = "center">
<img style="width:30%;" src="img/IMG_0043.JPG" align = "center">
<img style="width:30%;" src="img/IMG_0045.JPG" align = "center">

!SLIDE

## ペーパープロトタイプ２回目
- 実装するシステムをメンバー間で共有するために画面設計を行った
<img style="width:100%;" src="img/goal.png" align = "center">

!SLIDE

## 後期の活動
- 開発
 - Gitによる分散開発
 - Issueを使ったチケット駆動開発
- 実装範囲の設定
- 運用
 - サーバを用意し実環境での動作確認
!SLIDE

## 開発体制
<center>
<img src="img/kaihatsutaisei2.png" style="width:55%;height:55%;">
</center>

!SLIDE

## スコープ 1/2 
<table border>
<tr>
<td>機能</td>
<td>実装する</td>
</tr>

<tr>
<td>グループの管理ができる</td>
<td></td>
</tr>

<tr>
<td>外部からポートフォリオを閲覧する</td>
<td></td>
</tr>

<tr>
<td>教員が学生の学習成果物を閲覧できる</td>
<td></td>
</tr>

<tr>
<td>学生が教員からレビューをもらうことができる</td>
<td></td>
</tr>

<tr>
<td>教員が学生の目標を知ることができる</td>
<td align = "center">○</td>
</tr>

<tr>
<td>学生が学内公開と、学外公開用のビューを作成することができる</td>
<td align = "center">○</td>
</tr>

<tr>
<td>学生が学習成果物を管理することができる</td>
<td align = "center">○</td>
</tr>
<tr>

<tr>
<td>ゴールをグラフで可視化</td>
<td align = "center">○</td>
</tr>

</table>

!SLIDE

## スコープ 2/2

<table border>
<tr>
<td>機能</td>
<td>実装する</td>
</tr>

<tr>
<td>ローカルから成果物をアップロード</td>
<td></td>
</tr>

<tr>
<td>ゴールと日誌の関連付け</td>
<td align = "center">○</td>
</tr>

<tr>
<td>学生が目標と現状の自己評価をすることができる</td>
<td align = "center">○</td>
</tr>

<tr>
<td>ユーザの検索</td>
<td></td>
</tr>

<tr>
<td>認証</td>
<td></td>
</tr>

<tr>
<td></td>
<td></td>
</tr>

<tr>
<td></td>
<td></td>
</tr>

<tr>
<td></td>
<td></td>
</tr>

</table>


!SLIDE

## 全体のスケジュール
<img style="width:95%;" src="img/schedule.png" align = "center">

!SLIDE

## 学び
- 全体を通して(2年生とか)なにかあれば

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
<!-- 
目次と同じ感じですω・
-->

