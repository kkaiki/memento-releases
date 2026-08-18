# memento-releases

[Memento](https://github.com/kkaiki/memento)(macOS版・メニューバー常駐アプリ)の配布物置き場です。

- ソースコードはここではなく非公開リポジトリ(`kkaiki/memento`)にあります。
- ここに置くのは配布用の `.dmg` と、Sparkleが自動アップデートのチェックに使う
  `appcast.xml` だけです。
- `appcast.xml` はEdDSA署名付きで、署名が一致しないアップデートはSparkleが弾きます。

## はじめて使う方へ

1. [Releases](https://github.com/kkaiki/memento-releases/releases) から最新の `Memento-x.y.z.dmg` をダウンロード
2. マウントして `Memento.app` を「アプリケーション」フォルダへドラッグ
3. **初回だけ** Finderで右クリック →「開く」で起動してください
   (署名なしアプリはダブルクリックでは開けません。「壊れている」という表示が出た場合も、
   一旦「アプリケーション」フォルダへ移してから右クリック→開くを試してください)

2回目以降はアプリ内の「アップデートを確認…」、またはSparkleによる自動チェックで
新しいバージョンに更新できます。
