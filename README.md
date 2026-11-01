# Versinoa Server Resource Pack

Minecraft Java Edition **1.21.11** / VersinoaMainSystem **1.28.0以上** 用の統合パックです。

最新版: [VersinoaServer-1.28.0.zip](packs/VersinoaServer-1.28.0.zip) ([ハッシュ情報](packs/VersinoaServer-1.28.0.json))。

## 内容

- 緑のスタミナ・青の魔力バーをホットバー上部に表示します。EXPなどの通知とは別の高さです。
- 満腹度をつながったケーキ風のバーへ変更します。
- 刀・双剣・大剣・斧・槍・爪・盾・黒魔法・光魔法・精霊魔法・弓・鎌・武術の13種へ支給された透過武器テクスチャを適用します。通常の刀と試験用刀を含む14アイテム定義に対応します。
- 武器は平面の手持ちモデルです。新しい専用3D形状や弓の引き絞り差分画像は含みません。バニラの武器・素材へ一括上書きしません。
- 金色グラデーションの星形体力、技能別スキルツリーの画像・フォント・接続線、2×2クラフト欄のアクセサリー背景を保持します。

このZIPだけを適用してください。旧アクセサリーパックとの重ね合わせは不要です。
**Main1.28.0と同梱のSkills0.8.1をセットで使用してください。** キャラクターのデータ・戦闘・技能解放・SP・保存はサーバープラグインが担当します。
Java用のパックです。BEのテクスチャは変更しません。BEやパック未読込ではプラグインが数値のリソース表示へ切り替えます。

## サーバー配布

Paperを正常停止し、両プラグインJARを交換し、既存server.propertiesのURLとSHA1を一緒に更新して再起動します。
下記は版ごとのURLです。特定コミットに固定したURLはMain配布物のdocs/visual-1.28.0/SERVER-RESOURCE-PACK.txtにも記載します。

```properties
resource-pack=https://raw.githubusercontent.com/MelowUrban/VersinoaResourcePack/main/packs/VersinoaServer-1.28.0.zip
resource-pack-sha1=71f4327c07439973666f09712b86f69353d9587b
require-resource-pack=true
```

- サイズ: 306621 bytes
- SHA-1: `71f4327c07439973666f09712b86f69353d9587b`
- SHA-256: `f8a2cb379925aaddda256d91248258a61b4db041ccba9e3b15ae77e2328ffa58`

実サーバーの設定は自動変更していません。新しい表示の実機最終確認は未実施です。
パックは画像・表示モデル・フォント・案内文だけを含み、本体JAR・プラグインソース・秘密設定を含みません。
一部GUI画像はMojangのMinecraft Java1.21.11素材に基づきます。支給武器PNGは原本と同じバイトです。

## 過去版

- [1.27.0の星形体力統合パック](packs/VersinoaServer-1.27.0.zip)
- [1.26.1の技能別スキルツリー統合パック](packs/VersinoaServer-1.26.1.zip)
- [1.18.0の統合パック](https://github.com/MelowUrban/VersinoaResourcePack/releases/tag/server-v1.18.0)
- [1.11.0の旧ホットバー背景](https://github.com/MelowUrban/VersinoaResourcePack/releases/tag/accessories-v1.11.0)

過去のファイル・リリース・添付ファイルは履歴として保持しています。
