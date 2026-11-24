# 資料約定

這些內容是本地合成演練資料，不代表真實人物、機構、作品或交易。原始值按來源記錄；空值和待核狀態表示尚未確認，不等同否定、零或已完成。

现代绘画委托估值使用的作品、交易和客户委托范围。

- `works.csv`：欄位 `work_id, artist_id, title, attribution, medium, width_cm, height_cm, created_from, created_to`。
- `transactions.csv`：欄位 `tx_id, work_id, sold_on, status, price, currency, fee_included, lot_scope, source_id`。
- `mandates.csv`：欄位 `mandate_id, client_id, work_id, purpose, as_of, authorized_range, state`。
- `source_checks.csv`：欄位 `source_id, provider, captured_on, record_version, review_state, derived_from`。

同一標識只在其對應資料域內使用；版本、時間和狀態欄位保留各自來源含義。
