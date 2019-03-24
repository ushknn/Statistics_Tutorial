# データ分析未経験者向けの教材資料を作成
	(目的) 仕事で未経験の人が会社にたくさん入ってくることになりそうなので、その人達をサポートするため。
	       以下二点に重点を置く。
	       	�@分析現場で絶対に必要な数学知識を身に着ける。
	       	�Aプログラム実装しながらコーディングのスキルも身に着けてもらう。
	       	
	(制約)
			�@対象者 = プログラミングと分析 未経験
			�A学習期間 3-6 ヶ月間程度


## やってみようと思案しているもの

### 1. 二項分布 & 正規分布 ( & ポアソン分布 )
	1.1 コイン & サイコロ作成
		
	1.2. 二項分布でヒストグラムを作成
		1.1で作ったコインとサイコロを使う
		サイコロの確率や試行数を変化させてヒストグラムの形の違いを見る

	1.3. 正規分布 & 二項分布 & ポアソン分布でフィッティング
		matplotで表示してヒストと合うか確認する
		(ポイント) ベルヌーイの成功確率や試行回数を変化させて、中心極限定理をグラフで確認。正規分布の有用性を理解してもらう。
		
		
	1.5. 二項分布のpが分かっていないサイコロで作成されたヒストグラムを正規分布でフィッティングし、pを類推する。


### 2. 回帰分析

	2.1 最小二乗法でフィッティング
		最小二乗法の計算をスクラッチで実装しフィッティングする
		(参考↓)
		https://qiita.com/ishizakiiii/items/72be4ce16a10f97d6183
	
	2,2 2.1のエラーバー付きVer
    	(TODO)データ探す
		
	2.3 コインを使って減衰曲線(cf 表が初めて出るまでに投げたコインの回数のヒスト)を作成し、Logでスケールして最小二乗法でフィッティング
		(ポイント)
			�@ 1.で使ったコインを使う。
			�A 独立事象の例示として良いと思うのだが。
		これはやる必要ないかな？？
		
### 3. 株価の変動からリスクとリターンを求めて相関関係を求める。
	(TODO) ボラの高い・低い証券を選択し株価のデータを取得
	(ポイント)
		 �@正規分布と最小二乗法を応用
		 �Aデータの構造性を体験できる。
	   