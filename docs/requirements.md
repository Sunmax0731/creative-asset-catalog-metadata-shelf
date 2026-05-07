# 要件定義

## 目的

制作素材カタログ・メタデータ棚 は、Adobe系素材を案件横断で管理する制作者 が 素材名、用途、権利、メタデータ、利用先を棚へ登録し、再利用と納品確認に使う。

## Source

- PICKUP Rank: 51
- Domain / Idea No: AdobePlugin / 7
- Repository: creative-asset-catalog-metadata-shelf
- created_idea: `D:/AI/AdobePlugin/created_idea_007_creative-asset-catalog-metadata-shelf`
- ZIP: `D:/AI/AdobePlugin/created_idea_007_creative-asset-catalog-metadata-shelf/idea_007_creative-asset-catalog-metadata-shelf.zip`
- README確認: 開始時点では正式 repo が存在しないため、README.md は存在しない。

## Functional Requirements

- R1: assetName、metadataKey、usageStatus、license を必須項目として検査する。
- R2: 必須項目不足は fail として分類する。
- R3: `licenseUnclear` が true の場合は warning として分類し、手動確認理由を返す。
- R4: 複数アイテムの mixed-batch を pass / warning / fail に集計する。
- R5: 結果を CLI と docs/release evidence で再利用できる形にする。

## Non Functional Requirements

- UTF-8 で Markdown / JSON / JS / HTML / Python を保存する。
- 外部通信を既定で行わず、サンプルとローカル入力だけで検証できる。
- 手動テスト未実施であることを release 前 docs に明記する。

