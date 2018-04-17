# Unix Review

## 目的

1. 来週、１年生のUnix授業にチュータして参加するための知識があることを確認
1. １年生のCUIでのコマンド操作の重要性を説明できる
1. トラブルシューティングのポイント
1. vim
	- モード
		- コマンドモード
		- インサート(編集)モード
		- ビジュアルモード
		- ESC => インサートモードを抜ける
		- i, a, o ... => インサートモードに入る
	- i => カーソルの前に追加
	-	I => 行頭の追加
	- a => カーソルの後ろに追加
	-	A => 行末に追加		
	- o => 行下に追加
		- O => 行上に追加
	- dd => カーソル行の削除
	- x => カーソル位置の文字を削除
	- s => カーソル位置の文字を削除して挿入
	- S => カーソル業を削除して挿入
	- u => 操作の取り消し
	- ctrl + r => 取り消しの取り消し
	- h => カーソルを左に移動
	- j => カーソルを下に移動	
	- k => カーソルを上に移動
	- l => カーソルを右に移動
	- / => 検索
	- :wq
	- :q!
1. 基本のコマンド
	- sudo apt update
	- sudo apt upgrade
	- ctrl + alt + f1
	- ctrl + alt + f7
	- ls
	- pwd
	- cd
	- mv
	- cp
	- mkdir
	- rm
		- sudo rm -rf /
	- LANG=C => ロケールを英語に変更
	
1. tabキーによる補完
