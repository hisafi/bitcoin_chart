# matplotlib.financeでビットコインのチャート生成

大阪Pythonの会 #07(11/26)のハンズオン資料

図形描画ライブラリのmatplotlibにfinanceという便利な機能があります。これを使えば簡単にローソク足チャートを作成できる！  
[公式サイト：matplotlib.finance](https://matplotlib.org/api/finance_api.html)  
参考：[Pythonでローソク足チャートの表示（matplotlib編）](https://qiita.com/toyolab/items/1b5d11b5d376bd542022)  

今回はビットコインの約定履歴を元にローソク足チャートを描画します。ちなみに、データはbitflyerのAPIより取得したものを用いています。  
[API【bitflyer】約定履歴](https://lightning.bitflyer.jp/docs?lang=ja&_ga=2.216037458.593837218.1507286358-1023458056.1504920363#約定履歴)

jupyter notebook使ったことがない方は、[Try Jupyter!](https://try.jupyter.org)を一緒に試していきましょう！ 
