# R8.kadai.No1
令和８年度E3B一班の課題研究

## 課題研究の進捗管理
このサイトを使って課題研究の進捗を管理しています。

## 2026年5月28日の進捗
### 🎯 今日の成果
**『Arduino R4を実際に使って光らせた』**

#### 内容
- Arduino R4 マイコンボードを用いたLED制御の実装に成功しました
- 基本的なLED点灯プログラムの作成と実行を完了しました

#### 使用技術
- **マイコン**: Arduino R4
- **制御対象**: LED
- **プログラミング言語**: Arduino言語（C++ベース）

#### コード例
```cpp
// Arduino R4でLEDを点灯させるサンプルコード
void setup() {
  pinMode(13, OUTPUT);  // デジタルピン13をLED出力に設定
}

void loop() {
  digitalWrite(13, HIGH);  // LEDを点灯
  delay(1000);             // 1秒待機
  digitalWrite(13, LOW);   // LEDを消灯
  delay(1000);             // 1秒待機
}
```

#### 次のステップ
- [ ] より複雑なLED制御パターンの実装
- [ ] センサーとの連携
- [ ] 複数のLED制御
- [ ] プロジェクトドキュメントの拡充

---

## プロジェクト構成
```
R8.kadai.No1/
├── README.md          (このファイル)
├── src/               (ソースコード)
└── docs/              (ドキュメント)
```

## 参考資料
- [Arduino公式ドキュメント](https://docs.arduino.cc/)
- [Arduino R4 リファレンス](https://docs.arduino.cc/hardware/uno-r4-wifi)

---

**最終更新日**: 2026年5月28日
