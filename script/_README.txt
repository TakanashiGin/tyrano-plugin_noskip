========== ========== ========== ==========
     CSV読み込みプラグイン
========== ========== ========== ==========

【最終更新日】2020/04/17
【  名  称  】スキップ禁止プラグイン
【  種  別  】ティラノスクリプト用の外部プラグイン
【 製 作 者 】小鳥遊銀（たかなし ぎん）
【 開発環境 】64bit版Windows10, ティラノスクリプトv501a, ティラノスタジオv100
【 動作環境 】上記開発環境にて確認
【 連 絡 先 】Twitterまでどうぞ（@diyin_near_j）
【ライセンス】MIT

---------- ----------



◇ 概要 ◇

シナリオ中でプレイヤーがスキップを実行したり、
予期しないスキップを防ぐために、明示的にスキップを防ぐプラグインです。

このプラグインを導入すると、[noskip]が使えるようになります。



◇ ファイル構成 ◇

for
 ├ init.ks
 └ _README.txt



◇ 導入方法 ◇

解凍して出てきた「noskip」フォルダを、
「data/others/plugin/」下にコピーしてください。
その後、first.ksに以下のタグを記述してください。

    [plugin name='noskip']



◇ pluginタグに指定できるパラメータ ◇

-



◇ タグリファレンス ◇

◆ [noskip]

    || 概要

    スキップを禁止します

◆ [endnoskip]

    || 概要

    スキップ禁止を解除します

◇ FAQ・既知のバグ等 ◇

-



◇ 履歴 ◇

2020/04/16  リリース
