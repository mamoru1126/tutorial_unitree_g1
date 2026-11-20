# tutorial_unitree_g1

Unitree G1（実機）を VLM（Vision-Language Model）で動かすためのチュートリアルです。

## 資料

- [Unitree G1 を VLM で動かすロードマップ](https://mamoru1126.github.io/tutorial_unitree_g1/)（`docs/index.html`）

安全準備から SDK、シミュレーション、カメラ、VLM の接続、閉ループ化、腕と VLA への発展までを 8 つのフェーズに分けています。

前提とするネットワーク構成は「ローカル PC → リモート PC → G1」です。インターネットにつながっているのはリモート PC だけで、G1 はオフラインです。G1（PC2）へのソフトの導入と時刻合わせは、リモート PC を経由して行います。

## GitHub Pages の設定

Settings → Pages で、Source を「Deploy from a branch」、Branch を `master` / `/docs` にすると公開されます。
