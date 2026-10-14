# Pin-Hao Wen

國立成功大學 資訊工程學系 ｜ NCKU CSIE

我關注**電腦視覺**與 **LLM 可靠性**：讓模型在真實系統中偵測得準，也說得對。
I work on computer vision and the reliability of LLM-generated outputs in real-world pipelines.

## 代表作品

| 專案 | 簡介 |
|---|---|
| [chimney-monitor-capstone](https://github.com/JustinWen026/chimney-monitor-capstone) | **畢業專題**：YOLOv11 煙囪排煙偵測（mAP50 0.805），多煙囪時序狀態機告警，Discord 通報，MCP + 本地 LLM 自動事故報告 |
| [chimney-monitor-llm-faithfulness](https://github.com/JustinWen026/chimney-monitor-llm-faithfulness) | **延伸研究**：工具查證的 LLM 事故報告是否忠實？以雜訊植入探針做三組消融實驗（單事故 / 三事故並發，每組 N = 80），發現被驗證的欄位從未出錯，錯誤全出現在未驗證的敘事 |

## 論文

**Verified Fields, Unverified Narratives: Injected-Noise Uptake in Tool-Grounded LLM Incident Reports for Industrial Chimney Monitoring**
Pin-Hao Wen, Shang-Liang Chen

## 技術

- **語言**：Python、Java
- **電腦視覺**：Ultralytics YOLO、OpenCV、PyTorch
- **LLM**：Ollama、Model Context Protocol (MCP)、BERTScore、LLM-as-judge
- **實驗與分析**：消融實驗設計、Welch t 檢定 / Holm 校正 / bootstrap CI、pandas、matplotlib
- **系統**：SQLite、Streamlit、Discord Webhook
