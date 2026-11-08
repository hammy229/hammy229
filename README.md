# Arham Doshi

Computer Science & Linguistics @ UT Austin · ML/NLP Research · SWE

## About

CS + Linguistics at UT Austin.

**Currently:** [Wang Lab](https://slhs.utexas.edu/research/wang-lab/people) @ Dell Medical School, UT Austin (ALS survival prediction)

**Past:** [Wenqi Lab](https://qbrc.swmed.edu/labs/shilab/) @ UTSW (LLM-as-RNN, clinical AI) · [UT Discourse Lab](https://jessyli.com/) (LLM behavior) · SMU CS (socioeconomic status from Reddit narratives, CoNLL 2025) · [Hayden Lab](https://www.bcm.edu/research/faculty-labs/benjamin-hayden-lab), Baylor College of Medicine (data from patients with epilepsy)

## Publications

- CoNLL 2025 (co-located w/ ACL): [predicting socioeconomic status from Reddit narratives](https://aclanthology.org/2025.conll-1.23/) (co-author).
- ACL 2026: [LLM faithfulness under counterfactual medical evidence](https://arxiv.org/abs/2601.11886) (lab contributor).
- [The Loss in AI Translation](https://doi.org/10.58445/rars.1453): independent NLP research (first author).

## Technical Skills

| | |
|---|---|
| **Languages** | Python, C, C++, Java, TypeScript, JavaScript, Go, Rust, SQL, Bash |
| **Systems & Performance** | WebAssembly, CMake, GoogleTest, AddressSanitizer |
| **Cloud & MLOps** | AWS (Bedrock, SageMaker, Lambda, S3), GCP, Azure, Docker, GitHub Actions, W&B |
| **Deep Learning** | PyTorch, TensorFlow/Keras, JAX, Hugging Face, Transformers, CNNs, RNNs |
| **LLMs & Agents** | GRPO, LoRA, vLLM, RAG, FAISS, LLM agents, MCP, Claude API, OpenAI API |
| **Speech & NLP** | wav2vec2, HuBERT, Machine translation |
| **ML & Statistics** | scikit-learn, Survival analysis, Random forests, XGBoost, LightGBM |
| **Data** | pandas, NumPy, Polars, Spark |
| **Web & Backend** | Next.js, React, Node.js, Express, FastAPI, REST APIs, GraphQL, WebSockets, OpenAPI, OAuth 2.1, PostgreSQL, MongoDB, Redis, Tailwind CSS |
| **Mobile** | React Native, Android, iOS |
| **Tools & HPC** | TACC (Lonestar6, Vista), SLURM, Ray, Linux, Git |

## Projects

Every project below has the same README layout: results with evidence, why it matters, how it works, how to run it, and its limits.

### [Ember](https://github.com/hammy229/ember)

An LLM inference engine written from scratch in C++20 with no ML framework, running natively and in the browser through WebAssembly. It loads real Llama models from Hugging Face, matches a separate reference to within 4.2e-5 across all 32,000 logits, runs 815 tokens a second on one thread, and is fuzzed on every push.

[Repository](https://github.com/hammy229/ember) · [Results](https://github.com/hammy229/ember/blob/main/docs/results/2026-11-08-apple-m4.md)

### [Tink](https://github.com/hammy229/tink)

Learns the few sounds a nonspeaking person can make (a hum, a click, a sigh) and speaks what each one means, in their own banked voice. voc2vec embeddings in the browser with a Bayesian model that asks instead of guessing, evaluated on 7,077 real sounds from minimally speaking people and on dysarthric speech.

[Live demo](https://tink-quen.vercel.app/#demo) · [Repository](https://github.com/hammy229/tink)

### [MedData Escrow](https://github.com/hammy229/meddata-escrow) (in progress)

AI procurement and escrow marketplace for medical research data. An agent matches a study to a dataset and checks a sample, and PayPal holds payment until the data passes. Retrieval MRR 0.846 on a held-out set, and a hostile-model red team blocked 26 of 26 attacks. Synthetic data only.

[Repository](https://github.com/hammy229/meddata-escrow)

### [Caddie Coach](https://github.com/hammy229/caddie-coach)

A voice golf caddie and swing coach for Alexa+, built for the Amazon "Build, Ship, Shape" Hackathon 2026. Models your real distances, misses, and swing faults, then picks clubs and aim points. A self-hosted MCP server with 10 tools, 145 tests, and a one-command AWS Lambda deploy.

[Repository](https://github.com/hammy229/caddie-coach)

### [alexa-mcp-oauth](https://github.com/hammy229/alexa-mcp-oauth)

Drop-in OAuth 2.1 for self-hosted MCP servers that link to Alexa+, extracted from Caddie Coach. Stateless, with a test for each of the 7 items on Amazon's auth checklist.

[Repository](https://github.com/hammy229/alexa-mcp-oauth)

### [Jain Enlightened](https://github.com/hammy229/jain-enlightened)

A multilingual learning platform for Jain philosophy, live in Gujarati, Hindi, and English: a Laravel website, JSON API, and admin panel, plus a React Native app.

[Live site](http://www.jainenlightened.org/) · [Repository](https://github.com/hammy229/jain-enlightened)

### [LayoutDNA](https://github.com/hammy229/layout-dna)

Adapts layered designs to new aspect ratios and measures how six structural design genes survive. React client and FastAPI solver, with zero hard-constraint violations across every feasible case in a 40-case evaluation.

[Repository](https://github.com/hammy229/layout-dna)

## Research code

### [The Loss in AI Translation](https://github.com/hammy229/Loss-in-AI-Translation---Ind-Research)

An LSTM sequence-to-sequence model and a Transformer, both written from scratch in PyTorch, for Hindi to English translation, with an error analysis of what gets lost on Jain scripture.

[Repository](https://github.com/hammy229/Loss-in-AI-Translation---Ind-Research) · [Paper](https://doi.org/10.58445/rars.1453)

### [Low SES Text Classification](https://github.com/hammy229/SMU-Low-SES-Extraction-Work)

My nine-model comparison from SMU research on spotting low socioeconomic status in Reddit narratives, behind the CoNLL 2025 paper.

[Repository](https://github.com/hammy229/SMU-Low-SES-Extraction-Work) · [Paper](https://aclanthology.org/2025.conll-1.23/)

## Links

- Portfolio: [arhamdoshi.dev](https://arhamdoshi.dev)
- Email: [doshi.arham22@gmail.com](mailto:doshi.arham22@gmail.com)
- Email 2: [avd745@my.utexas.edu](mailto:avd745@my.utexas.edu)
- Twitter/X: [@arhamd22](https://x.com/arhamd22)
- LinkedIn: [linkedin.com/in/arhamdoshi](https://linkedin.com/in/arhamdoshi)
- GitHub: [github.com/hammy229](https://github.com/hammy229)
- Google Scholar: [scholar.google.com/citations?user=gzShr0gAAAAJ](https://scholar.google.com/citations?user=gzShr0gAAAAJ&hl=en)
