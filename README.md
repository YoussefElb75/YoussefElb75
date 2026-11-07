## Youssef

**Senior quantitative developer and data scientist in capital markets, specialising in LLM and agentic AI systems for trading workflows.**

Experience across structured products, derivatives pricing and front-office data: equity and credit derivatives, autocalls and EMTN structuring, rates and FX, volatility surfaces, risk and sensitivities.

I build production-grade pricing and risk models, LLM and agentic pipelines that turn unstructured trader and client messages into validated structured data, and the data platforms behind them: validated against reference libraries such as QuantLib, tested, typed and run through CI.

### Focus areas

Market finance (structured products, derivatives, credit, volatility) · LLM / agentic AI in production (extraction, RAG, evaluation, guardrails) · Machine learning for pricing and risk · Data engineering (Databricks, Spark, Delta Lake)

### Featured projects

- **[autocall-pricer](https://github.com/YoussefElb75/autocall-pricer)** — Monte Carlo pricer for autocalls and worst-of autocalls (2–5 underlyings) under correlated Black-Scholes, with exact log-normal simulation, antithetic variates, bump-and-reprice greeks and correlation sensitivity; validated against QuantLib.
- **[credit-pricer](https://github.com/YoussefElb75/credit-pricer)** — Credit derivatives library: ISDA-convention CDS bootstrapping, CS01, CDS indices, Gaussian-copula CDO tranches with base correlation, and CLNs; matches QuantLib's ISDA and midpoint engines to within 5e-4 bp.
- **[crypto-vol-surface](https://github.com/YoussefElb75/crypto-vol-surface)** — Arbitrage-free BTC/ETH implied volatility surfaces from Deribit's public API: raw SVI per expiry and SSVI with no-butterfly and no-calendar checks, smile analytics (ATM, 25Δ RR/BF), Black-76 pricing and greeks.
- **[market-data-lakehouse](https://github.com/YoussefElb75/market-data-lakehouse)** — Medallion lakehouse on Databricks for ECB FX, yield-curve and €STR data plus a synthetic tick stream: Delta Lake, Lakeflow pipelines and jobs, Unity Catalog governance, data contracts, quarantine and freshness SLAs, dev/prod via bundles.

### Tech stack

- **Languages:** Python · C# · SQL
- **LLM / GenAI:** LangGraph · LangChain · agentic workflows and tool calling · RAG (embeddings, vector stores) · structured output (Pydantic / JSON Schema) · prompt engineering · LLM evaluation and guardrails · fine-tuning (LoRA) · OpenAI / Azure OpenAI / Anthropic APIs · local models (Ollama, vLLM) · Hugging Face Transformers
- **Data science / ML:** pandas · NumPy · scikit-learn
- **Data engineering:** PySpark · Databricks (Delta Lake, Lakeflow, Unity Catalog) · FastAPI · Docker
- **Quant:** QuantLib · Monte Carlo · volatility surfaces · credit models
- **Engineering:** pytest · mypy · CI (GitHub Actions)

### Contact

LinkedIn: [your-profile](https://www.linkedin.com/in/your-profile)
