# Intuit AI: Building AI Agents & Enterprise Assistants

Corporate training repository for Intuit AI Agent development and no-code automation with Claude, n8n, and Ollama.

## 📓 Hands-on Labs
- [**Enterprise Resilient LLM Inference Lab (`Ollama_HandsOn_Lab.ipynb`)**](./Ollama_HandsOn_Lab.ipynb):
  - **Dual-Tier Resilient Inference Architecture**: Anthropic Claude 3.5 Sonnet (Primary Cloud API) with automated failover to local Ollama (`qwen3.8:27b` / `llama3.2`).
  - **Prompt Engineering**: Zero-Shot, Few-Shot In-Context Learning, Chain-of-Thought (CoT), and strict JSON schemas.
  - **Hyperparameter Exploration**: Temperature tuning (0.1 deterministic vs 1.0 divergent ideation).
  - **Red-Teaming AI Security**: Direct injection overrides, Grandma persona jailbreak, and Base64 token smuggling.
  - **High-Availability (HA) Failover Testing**: Programmatic cloud degradation simulation with zero-downtime failover to local models.
