# JavaScript
「ぐるれこめんど」（レストンランを乱数でレコメンドさせるコード・画像一式）

・概要
食べたいグルメに合わせて、レストランを選んでくれるサービス（ぐるれこめんど）を作りました。
私がレストラン選びを面倒くさいと感じる（どこも評価が高くて選ぶのに悩む）経験から、選んでくれるサービスを作ろうと思いました。

機能は、JSで条件分岐と乱数を掛け合わせて作りました。
食べたいグルメを選択し、それに合わせて乱数でレストランが表示されます。

使い方は、
食べたいグルメを選択→「GO」ボタンを押す→レストランの名前・写真・マップが表示される→店名を押すとレストランのリンクに飛ぶ、マップを押すとお店のマップが開く

・その他機能
日本語・英語の言語選択機能をつけました（jqueryで選択した内容で、言語の表示が変わるだけ）。
マップの非表示⇄表示の切り替え、初期状態では非表示、レコメンドを実行すると該当するレストランのマップが表示されるようにしました。

・今後の課題
レコメンドするレストランのリンク、マップリンクを手作業でJSファイルに貼り付けました。
もっと大量のデータを扱うため、今後はAPIを学んで活用していきたい
