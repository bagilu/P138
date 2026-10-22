# P138 V0.004 — SBI-P-SDS v3.4 靜態檢查

- PASS：ZIP 最外層同名資料夾、README、config-sample.js、database/、docs/。
- PASS：無直接使用 Supabase，無資料表、RLS、GRANT、RPC；相關項目 N/A。
- PASS：未含部署憑證或 config.js。
- PASS：Web Version V0.004 與 CSS / JS cache busting 一致。
- PASS：JavaScript 語法檢查（node --check）。
- REVIEW：完整瀏覽器拖曳、手機觸控及食譜關卡仍需實機驗證。
