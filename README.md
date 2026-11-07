# probably-stolen-tools

《Probably Stolen》社群工具集（純靜態網頁）。

| 工具 | 路徑 |
|---|---|
| 淨水器試算器 | [`purifier-calc/`](purifier-calc/index.html) |

## 淨水器公式（簡化）

```
去除量 = 31.25 ml × 體積加成 × (髒污加成 + 效率/100%)
體積加成 = 1 + min(體積 ml, 10000) × 0.00012   // 1 ~ 2.2
```

數值依社群逆向模型（build 26337366）簡化，忽略整數截斷，僅供參考。
