# Versinoa Server Resource Pack

Minecraft Java Edition **1.21.11** / VersinoaMainSystem **2.0.0** 用の統合パックです。

最新版: [VersinoaServer-2.0.0.zip](packs/VersinoaServer-2.0.0.zip) ([ハッシュ情報](packs/VersinoaServer-2.0.0.json))。

## 内容

- 1200種類の素材・加工品・通貨のアイテムモデルとテクスチャ。
- 通常モンスター1〜20の3Dモデル・テクスチャ。プラグイン管理の実体に単体ItemDisplayが追従します。
- 既存の13武器テクスチャ、星形体力、スタミナ・魔力バー、連続した満腹度バー、技能別スキルツリー、アクセサリー背景を保持します。

このZIPだけを適用してください。旧パックとの重ね合わせは不要です。
**Main2.0.0、同梱Skills0.15.0、MonsterSkills0.6.1の3JARをセットで更新してください。**
キャラクター・技能解放・SP・アイテムID互換・戦闘・保存はサーバープラグインが担当します。

Javaで対象パックを受諾した場合に3D表示します。BE版、判定不能、未受諾、Java/BE混在で同じ個体を見る場合は通常モブ表示になります。BEのカスタムエンティティ接続は未実装です。
モデルは静止姿勢で追従し、部位別アニメーションはありません。ヒットボックスとAIは通常モブ本体を使います。

## サーバー配布

Paperを正常停止し、3JARを交換し、既存server.propertiesのURLとSHA1を一緒に更新して再起動します。
以下は版ごとのURLです。Main配布物のdocs/release-2.0/SERVER-RESOURCE-PACK.txtには特定コミット固定URLを記載します。

```properties
resource-pack=https://raw.githubusercontent.com/MelowUrban/VersinoaResourcePack/main/packs/VersinoaServer-2.0.0.zip
resource-pack-sha1=b0630832f87c43f5c3488f16c57ef3b8668ad314
require-resource-pack=true
```

- サイズ: 3618761 bytes
- SHA-1: `b0630832f87c43f5c3488f16c57ef3b8668ad314`
- SHA-256: `a2fefda701aeb865b6fe544baaab6c034bd995cb997f990fa719e8f9d2fc0ac8`

実サーバー設定の自動変更・配備は行っていません。新しい表示の実機最終確認は未実施です。
パックは表示資産だけを含み、プラグインJAR・秘密設定を含みません。一部GUI画像はMinecraft Java1.21.11素材に基づきます。

## 過去版

- [1.28.0のHUD・武器テクスチャ統合パック](packs/VersinoaServer-1.28.0.zip)
- [1.27.0の星形体力統合パック](packs/VersinoaServer-1.27.0.zip)
- [1.26.1の技能別スキルツリー統合パック](packs/VersinoaServer-1.26.1.zip)
- [1.18.0の統合パック](https://github.com/MelowUrban/VersinoaResourcePack/releases/tag/server-v1.18.0)
- [1.11.0の旧ホットバー背景](https://github.com/MelowUrban/VersinoaResourcePack/releases/tag/accessories-v1.11.0)

過去のファイル・リリース・添付ファイルは履歴として保持しています。
