# 制作素材カタログ・メタデータ棚

creative-asset-catalog-metadata-shelf は Adobe系素材を案件横断で管理する制作者 向けの closed alpha プロダクトです。素材名、用途、権利、メタデータ、利用先を棚へ登録し、再利用と納品確認に使う。

## Source

- PICKUP Rank: 51
- Domain / Idea No: AdobePlugin / 7
- Repository: creative-asset-catalog-metadata-shelf
- 主な公開先: BOOTH / GitHub Release
- created_idea: `D:/AI/AdobePlugin/created_idea_007_creative-asset-catalog-metadata-shelf`
- 同梱ZIP: `D:/AI/AdobePlugin/created_idea_007_creative-asset-catalog-metadata-shelf/idea_007_creative-asset-catalog-metadata-shelf.zip`
- 開始時 README: 存在しない
- Adobe host: Bridge
- Host inference: 素材カタログとメタデータ棚はファイル横断管理が主目的で、Adobe Bridge のメタデータ/アセットブラウズ用途に最も合うため。

## Alpha Scope

- 代表シナリオ4件の自動検証
- 必須項目不足、警告、混在バッチの分類
- src/adobe/ のホスト連携シェル
- QCDS、security/privacy、traceability、release checklist、manual test docs
- docs ZIP: `dist/creative-asset-catalog-metadata-shelf-docs.zip`

## Commands

```powershell
npm test
node src/cli/index.js samples/representative-suite.json
npm run build:docs
```

手動テストは Codex 側では未実施です。手順は `docs/manual-test.md` と `docs/strict-manual-test-addendum.md` にあります。

