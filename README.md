# Andy 量化賭波（亞盤試水 + 角球實驗）

私人工作區：馬會盤、細倉紀律、edge 紀錄。本地先；之後先上 `annlch/Football-back-test`。

## 已鎖定範圍
- 聯賽：英超、歐聯／歐霸、西甲／德甲／意甲
- 主線：亞盤／讓球（edge ≥5%；0.5–1u；1u=bankroll 1%）
- 實驗線：角球大細（edge ≥8%；0.25–0.5u；分開統計）
- 莊家：香港賽馬會
- xG／角球數據：聯賽 Understat（及角球 for/against）；歐戰 Sofascore

## 檔案
| 檔 | 用途 |
|----|------|
| `edge-log.csv` | 亞盤 + 角球（用 market_line 区分） |
| `ah-checklist.md` | 亞盤選盤 |
| `ah-model-skeleton.md` | 亞盤模型 v0.1 |
| `corners-ou-skeleton.md` | 角球大細模型 v0.1 |
| `xg-sources.md` | 數據源 |

真錢下注前須人工確認。單日仍最多 3 注、日虧 -3u 停（亞盤+角球合計）。
