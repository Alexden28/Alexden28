### Pasquale Alessandro Denora

AI & Data Science master's student (double degree, Politecnico di Bari and Université Côte d'Azur).
I work on **evaluating what language models actually do**, and on machine learning for finance.

**Finance and ML**

- [**finllm-qa**](https://github.com/Alexden28/finllm-qa): fact-checks LLM-written financial
  commentary against SEC EDGAR and FRED data. Every number, direction word, period and company
  is traced back to the source. Three small open LLMs told to use only the facts
  still contradicted the data in 76% of 801 commentaries; checker precision 88% on a hand audit.
- [**equity-vol-forecasting**](https://github.com/Alexden28/equity-vol-forecasting): GARCH, HAR
  and an LSTM forecasting NASDAQ and S&P 500 volatility out of sample (1998–2026), with Diebold-Mariano
  tests, VaR backtests and a volatility-targeting strategy. The LSTM does not beat GARCH(1,1).
- [**finsent-lora**](https://github.com/Alexden28/finsent-lora): financial sentiment with a
  TF-IDF baseline, a fine-tuned RoBERTa, LoRA on Qwen2.5 and zero-shot LLMs, tested in domain
  (Financial PhraseBank) and out of domain (finance tweets). LoRA on Qwen2.5-1.5B ties a fully fine-tuned
  RoBERTa on news (88 macro-F1) but generalises worse to tweets (61 vs 73).

**LLM security and evaluation**

- [**openclaw-security-study**](https://github.com/Alexden28/openclaw-security-study): indirect
  prompt injection against LLM agents (research internship, INRIA Sophia Antipolis).
- [**Impact-of-Large-Language-Model-on-the-Cognitive-Process**](https://github.com/Alexden28/Impact-of-Large-Language-Model-on-the-Cognitive-Process):
  protocol for measuring cognitive offloading and undue trust in LLM role-playing agents.

**Other**: [federated learning, FedAvg vs FedAdam](https://github.com/Alexden28/Fed_Avg-vs-Fed_Adam) ·
[ontology enrichment pipeline](https://github.com/Alexden28/Progetto_FLC-main) ·
[KiCad PCB from Python](https://github.com/Alexden28/esp32c3-sensor-node-pcb) ·
[parametric CAD](https://github.com/Alexden28/freecad-parametric-parts) ·
[browser game](https://github.com/Alexden28/neon-swarm)

Python · PyTorch · scikit-learn · pandas · Hugging Face (transformers, PEFT) · arch · Git ·
Italian (native), English, French

[LinkedIn](https://www.linkedin.com/in/alessandro-denora-33220b238/)
