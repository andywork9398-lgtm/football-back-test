# xG 數據棧（已鎖）

| 用途 | 來源 | 備註 |
|------|------|------|
| 聯賽（英超／西甲／德甲／意甲） | Understat | 主源：xG / xGA / npxG |
| 歐聯／歐霸 | Sofascore | 單場／近期 xG；口徑或同 Understat 略有差 |
| 賽程／歷史 | FBref | 唔作唯一即時 xG |
| 傷停／輪換 | Transfermarkt | 手動調 mu 時寫 notes |

## 每場抄數（v0.1）

1. Understat（或 Sofascore 歐戰）：主／客近 6–10 場 xG for、xG against（能分主客更好）
2. 換算粗 `mu`（見 ah-model-skeleton）
3. Transfermarkt：明顯傷停 → notes + 調 mu
4. 馬會：盤線 + 水 → 計 edge
5. edge log 註明 `xg_source=understat` 或 `sofascore`
