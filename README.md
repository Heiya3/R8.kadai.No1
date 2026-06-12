# R8.kadai.No1

令和8年度 E3B 1班 課題研究

---

## 📋 課題研究テーマ

Bluetoothを使った自動資料読込み機

---

## 📊 研究進捗

### ✅ 6月12日までの研究の進捗

Arduino UNO R4 本体とPCとを接続し、Wi-Fi連携機能を使ってスマートフォンからの遠隔操作をできるようにした。

#### 技術スタック
| 項目 | 内容 |
|------|------|
| マイコン | Arduino UNO R4 |
| 通信方式 | Wi-Fi (ネットワーク経由) |
| 制御方法 | スマートフォンからの遠隔操作 |

#### システム構成
```
スマートフォン ←→ Wi-Fi ←→ パソコン ←→ Arduino UNO R4
```

---

## 🎯 現段階での課題点

Arduino UNO R4 とブレッドボードを接続し、スマートフォンから遠隔でブレッドボードのLEDを光らせる

### 実装予定事項
- [ ] ブレッドボードへのLED接続
- [ ] スマートフォンからのLED遠隔制御機能
- [ ] Bluetooth通信機能の実装
- [ ] モータードライバーの制御
- [ ] センサーの統合
- [ ] 自動資料読込み機構の製作

---

## 📁 プロジェクト構成

```
R8.kadai.No1/
├── README.md
├── src/
│   └── arduino/
└── docs/
```

---

## 🔗 参考資料

- [Arduino 公式ドキュメント](https://docs.arduino.cc/)
- [Arduino UNO R4 リファレンス](https://docs.arduino.cc/hardware/uno-r4-wifi)
- [Arduino Wi-Fi通信ガイド](https://docs.arduino.cc/tutorials/uno-r4-wifi/wifi-web-server)

---

**最終更新日**: 2026年6月12日
