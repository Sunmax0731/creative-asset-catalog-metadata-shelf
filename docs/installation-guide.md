# インストールガイド

## Closed Alpha Package

1. GitHub Release `v0.1.0-alpha.1` から assets を取得する。
2. `dist/creative-asset-catalog-metadata-shelf-docs.zip` を展開して README と manual-test を確認する。
3. repo を clone する場合:

```powershell
git clone https://github.com/Sunmax0731/creative-asset-catalog-metadata-shelf.git
cd creative-asset-catalog-metadata-shelf
npm test
```

## Host Setup

1. 作業ディレクトリ `D:\AI\AdobePlugin\Bridge\creative-asset-catalog-metadata-shelf` で `npm test` を実行します。
2. 対象ホストは `Bridge` です。推定根拠は README と `docs/source-idea-pack.json` を参照します。
3. Adobe UXP Developer Tool または対象ホストのスクリプト読み込み機能で `src/adobe` を読み込みます。
4. パネルまたはスクリプトの検品結果がサンプルと同じ分類になることを確認します。

