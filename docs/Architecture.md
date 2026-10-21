# P138 V0.001 架構簡表

Browser → Game State (memory) → Rendering / Scoring；無 server request。

- `setHeat()`：控制火力與預期溫度。
- `requestAnimationFrame()`：用 elapsed time 更新鍋溫與熟度，避免依電腦畫格速度計時。
- Pointer Events：油瓶與鍋子接觸期間按住倒油；蛋與鏟放開執行動作。
- `score()`：六項布林檢查，每項等權。不是美味的客觀測量。
- 重啟：清空遊戲內狀態；無 localStorage / sessionStorage。

## 未來擴充

料理 recipe JSON（recipeId, ingredients, operations, ranges, rubrics）、共用工具物件與食材狀態機、多模式；如需登入依 P130 及 v3.4 的 project-local authorization 建立後端。不要把本版演示數字當成料理研究證據。
