# R8.kadai.No1
令和８年度E3B一班の課題研究

## 課題研究テーマ
**Bluetoothを使った自動資料読込み機**

自動でドキュメントをスキャン・読込できるシステムの開発

---

## 課題研究の進捗管理
このサイトを使って課題研究の進捗を管理しています。

---

## 2026年5月28日の進捗
### 🎯 今日の成果
**Arduino UNO R4のWi-Fi連携機能を実装し、スマートフォンからの遠隔操作に成功**

#### 実装内容
- Arduino UNO R4をパソコンに接続
- Wi-Fi機能を活用してネットワーク接続
- スマートフォンからの遠隔操作機能を実装

#### 使用技術
- **マイコン**: Arduino UNO R4
- **通信方式**: Wi-Fi（ネットワーク経由）
- **制御**: スマートフォンからの遠隔操作
- **プログラミング言語**: Arduino言語（C++ベース）

#### システム構成
```
スマートフォン ←→ Wi-Fi ←→ パソコン ←→ Arduino UNO R4
```

#### 次のステップ
- [ ] Bluetooth通信機能の実装
- [ ] モータードライバーの制御
- [ ] センサーの統合
- [ ] 自動資料読込み機構の製作
- [ ] ユーザーインターフェースの改善

---

## プロジェクト構成
```
R8.kadai.No1/
├── README.md          (このファイル)
├── src/               (ソースコード)
│   └── arduino/       (Arduino スケッチ)
└── docs/              (ドキュメント)
```

## 参考資料
- [Arduino公式ドキュメント](https://docs.arduino.cc/)
- [Arduino UNO R4 リファレンス](https://docs.arduino.cc/hardware/uno-r4-wifi)
- [Arduino Wi-Fi通信ガイド](https://docs.arduino.cc/tutorials/uno-r4-wifi/wifi-web-server)

---

**最終更新日**: 2026年5月28日
