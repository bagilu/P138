# P138 資料庫狀態
V0.001 為純前端、無登入、無資料持久化的關卡示範，**不建立任何資料表、RLS、RPC 或 migration**。
因無資料庫物件可授權，本版 SQL permissions / health-check 均不適用，禁止對共用 Supabase 執行任何 SQL。
未來啟用 Supabase 時，應先採用 SBI-P-SDS v3.4 所規定的隔離資料 schema、RPC-only、RLS、逐表 GRANT 與專案授權。
