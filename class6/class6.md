# 第六課：LLM 紅隊演練（LLM Red Teaming）

![任務 6](./_static/mission6.png)

> **注意：** AI 治理（AI Governance）本身是一個龐大主題，因此本課僅聚焦於 LLM 紅隊演練（LLM Red Teaming）等技術控管。

> **注意：** 本課無實作實驗，因為 LLM 掃描資源需求龐大，將以示範與討論方式進行。

## 什麼是 AI 治理（AI Governance）？
AI 治理是指為人工智慧系統的「倫理開發、部署與應用」所建立的**框架**、**政策**與**實踐**。其目標是確保 AI 技術符合社會價值、法律規範與組織目標，同時降低風險並回應偏見、透明度、人權、問責與安全等挑戰。

## AI 風險／安全 vs AI 資安（AI Risk/Safety vs AI Security）

**AI 安全／風險（AI Safety/Risk）**

著重於防止 AI 服務造成非預期傷害，確保其倫理運作並符合人類價值，考量技術漏洞以外的更廣泛社會影響——保護人類使用 AI。相關標準如 NIST AI 600-1（美國國家標準與技術研究院 AI 600-1），涵蓋 AI 安全的風險管理框架（Risk Management Framework）。

**AI 資安（AI Security）**

著重於防護 AI 服務免於外部威脅，如網路攻擊與資料外洩，確保 AI 服務的機密性與完整性。相關通用框架有 OWASP Top 10 for LLM（開放式網路應用程式安全計畫十大風險清單），MITRE ATLAS（人工智慧系統對抗性威脅圖譜，Adversarial Threat Landscape for Artificial Intelligence System）——保護 AI 系統本身。

## 什麼是 LLM 紅隊演練？
LLM 紅隊演練是有系統地測試這類 AI 系統，以發現潛在漏洞、風險與失效模式。其概念類似於資安紅隊演練（defensive/blue vs offensive/red），但專注於找出 LLM 可能被攻破或失效的方式。

## F5 LLM 紅隊演練解決方案
以下為 F5XC Web App Scanning 在 LLM 探索上的部分報告範例：

![class6-1](./_static/class6-1.png)

---

![class6-2](./_static/class6-2.png)
