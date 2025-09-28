# CMPT470-APR-LLM-Research
# Leveraging Large Language Models and Historical Patterns for Efficient Automated Program Repair

📄 **Authors**: Babafunmise Adebowale, Pallavi, Wahhaj Javed  
🎓 University of Saskatchewan, CMPT 470 (Winter 2025)  

---

## 📕 Paper
- [Download PDF](./Project_CMPT470_Automated_Program_Repair.pdf)

---

## 📌 Abstract
Automated Program Repair (APR) aims to reduce software maintenance costs by automatically generating patches for buggy code. Traditional APR methods rely on predefined fix patterns or limited bug-fix pairs, which often restrict their generalization. With the rise of Large Language Models (LLMs), such as DeepSeek, it becomes possible to learn more flexible, context-aware repair strategies.  
This study fine-tunes DeepSeek-Coder-V2-Lite-Instruct on **RunBugRun** and **CTSSB-1M** datasets and evaluates performance both in-domain and out-of-domain (QuixBugs). Results show improvements in structural and semantic repair metrics, though with trade-offs in generalization.

---

## 🚀 Highlights
- Fine-tuned **DeepSeek-Coder-V2-Lite-Instruct** for single-statement Python bug repair.  
- Benchmarked on **RunBugRun**, **CTSSB-1M**, and **QuixBugs**.  
- Outperformed Codex and GPT-3.5 Turbo on QuixBugs (24/40 repairs).  
- Demonstrates trade-offs between in-domain specialization and cross-domain robustness.  

---

## 📊 Key Results
| Benchmark  | Base Model Exact Match | Fine-Tuned Exact Match |
|------------|------------------------|-------------------------|
| RunBugRun  | 11.5%                  | 17.1%                  |
| CTSSB-1M   | 1%                     | 17%                    |
| QuixBugs   | 27.5%                  | 50% (with import fix)  |

---

## ⚠️ Note
This repository preserves the **final paper** as the primary artifact.  
Due to lab machine resets, the full codebase is not available.  
