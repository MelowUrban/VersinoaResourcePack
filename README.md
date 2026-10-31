# Versinoa Server Resource Pack

Minecraft Java Edition **1.21.11** / VersinoaMainSystem **1.18.0** 用の統合パックです。

[最新版リリース](https://github.com/MelowUrban/VersinoaResourcePack/releases/tag/server-v1.18.0)から `VersinoaServer-1.18.0.zip` をダウンロードしてください。

## 内容

- 戦闘13技能・生活7技能の個別アイコンとスキルツリー用の画像フォント。
- 大きな白いツリー画面、方向ボタンによる移動、大小表示切替。
- 個人インベントリの2×2クラフト欄に、左上リング・右上ブレスレット・左下ネックレス・右下イヤリングの背景。
- 旧ホットバー右4枠の背景を通常表示へ戻します。

このZIPだけを適用してください。旧アクセサリーパックとの重ね合わせは不要です。スキル解放・SP・装備・保存はサーバープラグインが担当します。Java専用で、Bedrockへ同じ画面を表示するパックではありません。

## サーバー配布

Paperを正常停止し、既存 `server.properties` の同名設定を変更して再起動します。

```properties
resource-pack=https://github.com/MelowUrban/VersinoaResourcePack/releases/download/server-v1.18.0/VersinoaServer-1.18.0.zip
resource-pack-sha1=c539c34f0b8e8e055c816e0ee2e1d143050b5ddd
require-resource-pack=true
```

- サイズ: 209566 bytes
- SHA-1: `c539c34f0b8e8e055c816e0ee2e1d143050b5ddd`
- SHA-256: `13c7f79c305f57f2658a9a9674d25f83aa9285e0b30f105a15a9074df5b0ecfc`

ログインなしのダウンロード結果が元ZIPと完全一致することを確認しました。この説明は設定例であり、実サーバーの設定ファイルは変更していません。

## 確認範囲

元のスキル画面試作は本人が実機動作を確認済みです。今回拡大・統合した画面は新たな実機確認前です。画像フォントの263セルは256×256の描画上限内に収めています。自由なマウスドラッグには対応せず、方向ボタンで移動します。

パックには画像、フォント定義、案内文のみを含みます。Minecraft本体JAR、プラグインソース、秘密設定、認証情報は含みません。一部GUI画像はMojangのMinecraft Java1.21.11素材に基づきます。

## 過去版

[1.11.0の旧ホットバー背景](https://github.com/MelowUrban/VersinoaResourcePack/releases/tag/accessories-v1.11.0)は履歴として保持しています。
