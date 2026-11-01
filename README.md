# Versinoa Server Resource Pack

Minecraft Java Edition **1.21.11** / VersinoaMainSystem **1.27.0以上** 用の統合パックです。

最新版: [VersinoaServer-1.27.0.zip](packs/VersinoaServer-1.27.0.zip) ([ハッシュ情報](packs/VersinoaServer-1.27.0.json))。

## 内容

- 体力アイコンを金色グラデーションの星へ変更します。半分・点滅・ハードコア・毒・衰弱・凍結・吸収の表示を含みます。
- 通常体力を10アイコンで表示する調整はMain 1.27側で行います。乗り物の体力アイコンは従来の表示です。
- 各技能のノードと接続に対応するスキルツリー画像を維持します。
- 大きなツリー画面、方向ボタンによる移動、大小表示切替を維持します。
- 個人インベントリの2×2クラフト欄のアクセサリー背景を維持します。左上リング、右上ブレスレット、左下ネックレス、右下イヤリングです。
- 旧ホットバー右4枠は通常表示のままです。

このZIPだけを適用してください。旧アクセサリーパックとの重ね合わせは不要です。
**Main 1.27.0以上とセットで使用してください。** スキル解放・SP・装備・保存はサーバープラグインが担当します。
Java用のパックです。Bedrockのテクスチャは変更しません。Bedrockのスキル画面はプラグイン側のフォーム、またはインベントリGUIを使用します。

## サーバー配布

Paperを正常停止し、既存 `server.properties` の同名設定を変更して再起動します。
下記は版ごとのファイルURLです。特定コミットに固定したURLも、Main 1.27.0配布物の `SERVER-RESOURCE-PACK-1.27.0.txt` に記載しています。

```properties
resource-pack=https://raw.githubusercontent.com/MelowUrban/VersinoaResourcePack/main/packs/VersinoaServer-1.27.0.zip
resource-pack-sha1=451f46d327cbad3d57056de2f468a0ada53214ba
require-resource-pack=true
```

- サイズ: 266290 bytes
- SHA-1: `451f46d327cbad3d57056de2f468a0ada53214ba`
- SHA-256: `0ff909ad23d8e212ff88130ed5dcdef01960d4ffa30e2c567419927d3cad1a82`

実サーバーの設定ファイルは自動変更していません。今回の表示更新は新たな実機確認前です。
自由なマウスドラッグには対応せず、方向ボタンで移動します。

パックには画像、フォント定義、案内文のみを含みます。Minecraft本体JAR、プラグインソース、秘密設定、認証情報は含みません。
一部GUI画像はMojangのMinecraft Java 1.21.11素材に基づきます。

## 過去版

- [1.26.1の技能別スキルツリー統合パック](packs/VersinoaServer-1.26.1.zip)
- [1.18.0の統合パック](https://github.com/MelowUrban/VersinoaResourcePack/releases/tag/server-v1.18.0)
- [1.11.0の旧ホットバー背景](https://github.com/MelowUrban/VersinoaResourcePack/releases/tag/accessories-v1.11.0)

過去のファイル、リリース、添付ファイルは履歴として保持しています。
