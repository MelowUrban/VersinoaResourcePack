# Versinoa Resource Pack

Minecraft Java Edition 1.21.11 向けの、任意で使用できるアクセサリー枠背景パックです。

ホットバー右4枠に、右から **リング・ブレスレット・ネックレス・イヤリング** のシルエットを表示します。対象は HUD のホットバー、サバイバルのインベントリ、通常チェスト形式の GUI です。

背景は固定画像です。アイテムを置いてもその下に残り、別の GUI や他のパックによる上書きには自動対応しません。装備枠・技能・攻撃制限などのゲーム処理はサーバー側プラグインが担当するため、このパックの導入は必須ではありません。Bedrock Edition では使用できません。

## 配布ファイル

- ファイル: `VersinoaAccessories-silhouettes-1.21.11.zip`
- サイズ: `8499 bytes`
- SHA-1: `bcaea180def4abc61acdad4d3e986604388558a5`
- リリースタグ: `accessories-v1.11.0`

このリポジトリの [Releases](https://github.com/MelowUrban/VersinoaResourcePack/releases/tag/accessories-v1.11.0) から ZIP をダウンロードし、Minecraft の「設定 → リソースパック → パックフォルダーを開く」へ ZIP のまま置いて有効にしてください。

## サーバー配布の設定例

以下は公開済みZIPの直接ダウンロードURLです。ログインなしのダウンロードと、取得したZIPのSHA-1・サイズが元ファイルと一致することを確認しました。Paperを正常停止してから、既存のserver.propertiesの同名設定を変更し、起動してください。導入必須にする場合はrequire-resource-pack=trueに変更します。

```properties
resource-pack=https://github.com/MelowUrban/VersinoaResourcePack/releases/download/accessories-v1.11.0/VersinoaAccessories-silhouettes-1.21.11.zip
resource-pack-sha1=bcaea180def4abc61acdad4d3e986604388558a5
require-resource-pack=false
```

これは設定例です。実サーバーの設定ファイルは配布物に含みません。

## 確認範囲と内容

ZIP の構造、ファイルサイズ、SHA-1 を確認済みです。実際のゲーム画面での表示は未確認です。

パックには `pack.mcmeta`、案内文、GUI 画像3点のみを含みます。GUI 画像は Mojang の Minecraft Java 1.21.11 素材を基にしています。Minecraft 本体の JAR、プラグインのソース、サーバー設定、認証情報は含みません。
