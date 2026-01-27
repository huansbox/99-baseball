# 隕石數學防衛隊 Meteor Math Defense

9x9 乘法練習遊戲，太空隕石主題，iPad 觸控優化。

**[線上遊玩](https://huansbox.github.io/99-meteor/)**

## 快速開始

### 本地測試
```bash
# 使用任意 HTTP 伺服器
npx serve .

# 或 Python
python -m http.server 8000

# 或 VS Code Live Server 擴充功能
```

瀏覽器開啟 `http://localhost:8000`

### GitHub Pages 部署

1. 推送至 GitHub
2. Settings → Pages → Source: main branch / root
3. 等待部署完成

## 遊戲規則

- **三回合制**：每回合 10 題，難度遞增
- **隕石墜落**：輸入正確答案擊毀隕石
- **越早擊毀分數越高**：天空 100 分、高空 80 分、低空 60 分、地面 40 分
- **Combo 加成**：連續答對可獲得最高 2 倍分數
- **錯題追蹤**：答錯或落地的題目會進入錯題庫，優先複習

## 技術需求

- 現代瀏覽器（Safari/Chrome）
- 建議橫向使用 iPad

## 授權

MIT License
