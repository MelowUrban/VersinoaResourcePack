# Versinoa Server Resource Pack

Minecraft Java Edition **1.21.11** / VersinoaMainSystem **1.26.1以上** 用の統合パックです。

最新版: [VersinoaServer-1.26.1.zip](packs/VersinoaServer-1.26.1.zip) ([ハッシュ情報](packs/VersinoaServer-1.26.1.json))。

## 内容

- 各技能のスキルツリーを、それぞれの技能のノードと接続に合わせて表示します。
- 大きなツリー画面、方向ボタンによる移動、大小表示切替を維持します。
- 個人インベントリの2×2クラフト欄のアクセサリー背景を維持します。左上リング、右上ブレスレット、左下ネックレス、右下イヤリングです。
- 旧ホットバー右4枠は通常表示のままです。

このZIPだけを適用してください。旧アクセサリーパックとの重ね合わせは不要です。
**Main 1.26.1以上とセットで使用してください。** スキル解放・SP・装備・保存はサーバープラグインが担当します。
Java用のパックです。Bedrockではプラグイン側のフォーム、またはインベントリGUIを使用します。

## サーバー配布

Paperを正常停止し、既存 `server.properties` の同名設定を変更して再起動します。
下記は版ごとのファイルURLです。特定コミットに固定したURLも、Main 1.26.1配布物の `SERVER-RESOURCE-PACK-1.26.1.txt` に記載しています。

```properties
resource-pack=https://raw.githubusercontent.com/MelowUrban/VersinoaResourcePack/main/packs/VersinoaServer-1.26.1.zip
resource-pack-sha1=7691be7a13838d38b688719e21ff245bf0d74e09
require-resource-pack=true
```

- サイズ: 250468 bytes
- SHA-1: `7691be7a13838d38b688719e21ff245bf0d74e09`
- SHA-256: `146cf8c373a48091d6491910d625dcf0775b0fa5440a3cdae8f6e41d0bde15de`

実サーバーの設定ファイルは自動変更していません。今回の表示更新は新たな実機確認前です。
自由なマウスドラッグには対応せず、方向ボタンで移動します。

パックには画像、フォント定義、案内文のみを含みます。Minecraft本体JAR、プラグインソース、秘密設定、認証情報は含みません。
一部GUI画像はMojangのMinecraft Java 1.21.11素材に基づきます。

## 過去版

- [1.18.0の統合パック](https://github.com/MelowUrban/VersinoaResourcePack/releases/tag/server-v1.18.0)
- [1.11.0の旧ホットバー背景](https://github.com/MelowUrban/VersinoaResourcePack/releases/tag/accessories-v1.11.0)

過去のリリースと添付ファイルは履歴として保持しています。
