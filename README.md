# Bingcheng (Benson) Liu

AI engineer in Sydney. I build LLM-driven data products end to end: ingestion pipelines, structured model outputs, deterministic scoring, and the web front end that puts the result in front of a client. Master of IT (Artificial Intelligence) at UNSW, graduating January 2027. Before software I spent two years as a site quality engineer on high-rise construction in Shanghai. Seeing how much of that work could be automated is what led me to retrain in AI.

## Current work

<a href="https://foresight-analytics.com/fris"><picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/fris-logo-dark.svg">
  <img src="assets/fris-logo-light.svg" alt="FRIS — Foresight Risk Intelligence System" height="64">
</picture></a>

Sole developer of **[Foresight Risk Intelligence System (FRIS)](https://foresight-analytics.com/fris)** at [Foresight Analytics](https://foresight-analytics.com), Sydney.

FRIS is a B2B risk intelligence platform for institutional investors and due-diligence teams. It reads the news flow and regulatory filings that analysts used to scan by hand, extracts reputational and governance risk signals on target entities, and turns them into quantified, traceable risk ratings that can be followed over time. I own the product from requirements through to delivery: working out with analysts what the platform should report, designing the pipeline and scoring method, building the backend and front end, and presenting the results to clients. Proprietary; no public code.

## Selected projects

- [ai-automated-trading-system](https://github.com/bensonliu-sudo/ai-automated-trading-system) — news → relevance score → LLM trade thesis → async IBKR execution, with Telegram alerts. Full source.
- [financial-sentiment-transformers](https://github.com/bensonliu-sudo/financial-sentiment-transformers) — 36-run benchmark of TF-IDF, CNN, BiLSTM, BERT and FinBERT on Financial PhraseBank; macro-F1 0.861, leaked checkpoint found and excluded.
- [construction-inspection-ledger](https://github.com/bensonliu-sudo/construction-inspection-ledger) — inspection workflow as a tamper-evident ledger: 3 Solidity contracts, 42 tests, deployed and verified on Sepolia, with a live demo page.
- [news-recommender-mind](https://github.com/bensonliu-sudo/news-recommender-mind) — interpretable hybrid news re-ranker on MIND-small with a leakage-audited evaluation protocol.
- [air-quality-forecasting](https://github.com/bensonliu-sudo/air-quality-forecasting) — multi-horizon pollutant forecasting, 90%-missing-series reconstruction, residual anomaly detection.
- [pest-detection-yolov8](https://github.com/bensonliu-sudo/pest-detection-yolov8) — two-stage YOLOv8 detect-then-classify pipeline for 12 pest classes, mAP@0.5 0.77.
- [Intelligent-Watermark-Pipeline](https://github.com/bensonliu-sudo/Intelligent-Watermark-Pipeline) — synthetic-watermark dataset generation and U-Net mask detection (prototype).
- [ai-inspector](https://github.com/bensonliu-sudo/ai-inspector) — paused prototype: AI assistant for build-to-drawing site quality inspection; location parsing and drawing indexing work, the drawing-reading step is beyond current multimodal models, findings written up.

Course-project repositories hold write-ups only; source is available on request.

[LinkedIn](https://www.linkedin.com/in/bingcheng-liu-930a29385) · bingcheng.liu01@gmail.com

---

**中文简介**：刘冰骋，悉尼 AI 工程师，新南威尔士大学 IT（人工智能）硕士在读（2027 年 1 月毕业）。目前在 Foresight Analytics 独立开发面向机构投资者的风险情报平台 FRIS；上方仓库为个人与课程项目展示。
