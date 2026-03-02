# おとあそび 🎵

子供向けのサウンドボードPWAです。

## 収録音

### 🐾 どうぶつ
| ボタン | 音 |
|-------|-----|
| 🐱 ねこ | にゃー |
| 🐶 いぬ | わんわん |
| 🐸 かえる | けろけろ |
| 🐘 ぞう | ぱおーん |
| 🐥 ひよこ | ぴよぴよ |
| 🐮 うし | もーもー |
| 🐷 ぶた | ぶーぶー |
| 🦁 らいおん | がおー |
| 🐦 とり | ちゅんちゅん |

### ✨ こうかおん
| ボタン | 音 |
|-------|-----|
| 💥 ポン！ | ポン |
| 🪙 コイン | チャリン |
| 🌟 レベルアップ | ファンファーレ |
| 🌀 ピロピロ | ぴろぴろ |
| 🔔 ベル | りーん |
| 🥁 たいこ | ドカン |
| 🫧 ぽわん | ぽわん |
| 🎢 ひゅ〜ん | ひゅーん |
| 🎉 やったー！ | ファンファーレ |

## 技術仕様

- 外部音源ファイルなし（Web Audio APIで全音源を合成）
- PWA対応（ホーム画面に追加・オフライン動作）
- スマホ最適化（大きなタップターゲット）

## GitHub Pagesへのデプロイ

```bash
# リポジトリを作成してファイルをプッシュ
git init
git add .
git commit -m "initial commit"
git remote add origin https://github.com/あなたのID/otoasobi.git
git push -u origin main
```

Settings → Pages → Branch: main → Save

URL: `https://あなたのID.github.io/otoasobi/`
