# 研究と頓挫した理由

こちらはOpticalFlowアルゴリズムの一つ、Lucas-Kanade法を使って運動器の超音波画像内で組織の移動距離を推定するためのプログラムです。
基本的には超音波画像上のスペックル（波束の反射・散乱により生じる粒状のパターン）をトラッキングします。
しかし、例えば筋繊維が平行移動するだけだとかなり良い精度で追えるのですが、筋が収縮弛緩を繰り返すとスペックルが出たり消えたりして追えなくなるという問題が頻発します。
ノイズ低減のために平均値フィルタやガウシアンフィルタをかけると若干マシになりますが、それでも実用的なレベルに至りませんでした。

### 改良できるアイデアがあれば教えてください

[Twitter の DM](https://x.com/Pt96442837Pt) 
