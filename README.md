<!-- HEADER -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:0D1117,45:007ACC,100:4FC1FF&text=Aarmen%20Sidhu&fontSize=46&fontColor=FFFFFF&fontAlignY=32&desc=Data%20Science%20@%20SFU%20%E2%80%94%20building%20GenAI%20%26%20ML%20systems&descSize=17&descAlignY=52"/>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:4FC1FF,50:007ACC,100:79C0FF" width="100%"/>
</p>

<!-- SOCIAL LINKS -->
<p align="center">
  <a href="https://www.linkedin.com/in/aarmensidhu/" target="_blank">
    <img src="https://img.icons8.com/color/48/linkedin.png" width="40" alt="LinkedIn"/>
  </a>
  <a href="mailto:asa618@sfu.ca">
    <img src="https://img.icons8.com/color/48/gmail.png" width="40" alt="Email"/>
  </a>
  <a href="https://aarmensidhu.netlify.app" target="_blank">
    <img src="https://img.icons8.com/color/48/domain.png" width="40" alt="Portfolio"/>
  </a>
  <a href="https://github.com/aarmens702-hub" target="_blank">
    <img src="https://img.icons8.com/material-outlined/48/github.png" width="40" alt="GitHub"/>
  </a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:4FC1FF,50:007ACC,100:79C0FF" width="100%"/>
</p>

<!-- ABOUT ME -->
<h2>💻 About Me</h2>

<p>
I'm a <strong>Data Science student at Simon Fraser University</strong> who likes building the whole system, not just the notebook — the model, the pipeline around it, the tests that prove it works, and the interface someone actually uses.
</p>

<p>✨ <strong>What I work on</strong></p>

<ul>
  <li>Building <strong>LLM agents and RAG systems</strong> that cite their sources</li>
  <li><strong>ML systems engineering</strong>: inference serving, quantization, batching, benchmarking under load</li>
  <li><strong>Data platforms</strong>: warehouses, orchestration, and quality gates</li>
  <li><strong>Honest validation</strong>: time-based splits, leakage checks, and diff-testing against reference engines</li>
</ul>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:4FC1FF,50:007ACC,100:79C0FF" width="100%"/>
</p>

<!-- EXPERIENCE -->
<h2>💼 Experience</h2>

<h3>Supply Chain Analyst — SFU Beedie Analytics × BC Hydro</h3>
<p><em>Apr 2025 – Jun 2025 · Burnaby, B.C.</em></p>
<ul>
  <li>Built a composite risk model across <strong>100+ suppliers and 15+ procurement categories</strong> in a 3-person team</li>
  <li>Modeled a <strong>25% tariff scenario</strong> in Python and Tableau, presenting to <strong>BC Hydro and KPMG</strong>; placed 2nd in division</li>
</ul>

<h3>API Research Volunteer — TeejLab</h3>
<p><em>Dec 2023 – Aug 2024 · Burnaby, B.C.</em></p>
<ul>
  <li>Wrote Python scrapers extracting endpoint, authentication, and schema metadata from <strong>500+ APIs across 10+ industries</strong></li>
  <li>Classified APIs by industry, function, and compliance, structuring the data for a <strong>production API discovery platform</strong></li>
</ul>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:4FC1FF,50:007ACC,100:79C0FF" width="100%"/>
</p>

<!-- PROJECTS -->
<h2>🚀 Featured Projects</h2>

### [`$ genai-stack-coder`](https://github.com/aarmens702-hub/genai-stack-coder)
<p><strong>Tech:</strong> Python • PyTorch • QLoRA/Unsloth • Hugging Face • llama.cpp • Ollama • FastAPI</p>
<ul>
  <li>Fine-tuned <strong>Qwen2.5-Coder-7B on a single 12GB GPU</strong> to write current OpenAI/Anthropic SDK code: <strong>12% → 72%</strong> on a 50-prompt benchmark I built, with <strong>zero deprecated API calls</strong> after tuning</li>
  <li>Curated a <strong>6,665-pair, license-audited</strong> instruction dataset with scripted harvesting, filtering, and dedup</li>
  <li>Wrote a ~400-line <strong>coding-agent harness</strong> (22 protocol tests); the tuned model wrote the first version of its own demo app</li>
</ul>

### [`$ mailo`](https://github.com/aarmens702-hub/mailo)
<p><strong>Tech:</strong> Python • Amazon Bedrock AgentCore • Strands • A2A • MCP • Cedar • Cognito</p>
<ul>
  <li>Multi-agent email-campaign system: a thin <strong>orchestrator delegating to 3 specialists over A2A</strong>, with tools behind an MCP Gateway</li>
  <li><strong>Zero-trust identity on every hop</strong> — per-request M2M tokens, workload token exchange, secrets in Token Vault; found and fixed a real <strong>IDOR vulnerability</strong> and added the regression test</li>
  <li>A <strong>Cedar policy at the Gateway</strong> default-denies and caps email sends <em>outside the prompt</em>, so a jailbroken model still can't bypass it</li>
</ul>

### [`$ greenleaf-dashboard`](https://github.com/aarmens702-hub/greenleaf-dashboard)
<em>(2nd place — RBC × BCCAI × SFU Beedie Agribusiness Analytics Hackathon)</em>
<p><strong>Tech:</strong> Python • scikit-learn • sentence-transformers • Streamlit</p>
<ul>
  <li>Calibrated plant-stress early-warning model: <strong>0.78 ROC-AUC on a time-held-out split</strong> with explicit leakage checks — tied a gradient-boosted tree while staying fully interpretable</li>
  <li>Shipped as a daily <strong>risk-ranked watch-list catching ~2.3x more stress spikes</strong> than baseline, surfacing the controllable driver behind each alert</li>
  <li>Built an <strong>agentic RAG analyst</strong> that decides turn-by-turn whether to search docs or query live farm data, citing every source</li>
</ul>

### [`$ Inference-Benchmarks`](https://github.com/aarmens702-hub/Inference-Benchmarks)
<em>(<a href="https://huggingface.co/spaces/Aarmen/inferbench">live demo</a> — no sign-in)</em>
<p><strong>Tech:</strong> Python • FastAPI • ONNX Runtime • Docker • k6</p>
<ul>
  <li>Inference server + <strong>six-scenario benchmark harness</strong> measuring how batching, caching, quantization, and backpressure trade off latency, throughput, and accuracy</li>
  <li><strong>INT8 quantization</strong>: model 4x smaller, CPU throughput <strong>240 → 670 req/s</strong> at a 0.34 pp accuracy cost; batching cut <strong>p99 ~65%</strong> in the mid-load regime</li>
  <li>Every run writes a config snapshot so <strong>results are reproducible</strong>; two real bugs found and fixed via the benchmarks themselves</li>
</ul>

### [`$ plume`](https://github.com/aarmens702-hub/plume)
<p><strong>Tech:</strong> Rust • Apache Arrow • Parquet • DuckDB • rayon</p>
<ul>
  <li>Analytical query engine: <strong>~4,800 lines across 5 crates, 208 tests, zero warnings</strong>, with a typed DataFrame builder API</li>
  <li>Join-aware <strong>5-rule fixed-point optimizer</strong>; hash join in all six equi shapes; <strong>Parquet row-group pruning cuts decoded rows 8x</strong> on a 1M-row fixture</li>
  <li><strong>79 tests diff against DuckDB</strong> on canonicalized output — if the suite is green, the engines agree</li>
</ul>

### [`$ strata-warehouse`](https://github.com/aarmens702-hub/strata-warehouse)
<p><strong>Tech:</strong> Python • PostgreSQL • dlt • MinIO • dbt-duckdb • Dagster • Streamlit</p>
<ul>
  <li>End-to-end SaaS subscription analytics warehouse: <strong>OLTP → lakehouse → Kimball marts → dashboard</strong>, reproducible from a single <code>--seed</code></li>
  <li><strong>29 Dagster assets</strong> with daily partitions; <strong>179 dbt tests + 3 asset checks</strong> gate ~11.4M simulated usage events</li>
  <li>8-page Streamlit dashboard including a narrative <strong>"story" page driven by live warehouse numbers</strong></li>
</ul>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:4FC1FF,50:007ACC,100:79C0FF" width="100%"/>
</p>

<!-- TECH STACK -->
<h2>🛠 Tech Stack</h2>

<p><strong>Languages</strong><br/>
Python | SQL | R | Rust | TypeScript | JavaScript | C++
</p>

<p><strong>ML &amp; GenAI</strong><br/>
PyTorch | scikit-learn | Hugging Face Transformers | QLoRA fine-tuning | quantization | sentence-transformers | RAG | LLM agents &amp; tool-calling | LLM evaluation
</p>

<p><strong>Tools &amp; Infra</strong><br/>
FastAPI | Docker | ONNX Runtime | AWS Bedrock | Ollama | dbt | Dagster | Git | GitHub Actions | CI/CD
</p>

<p><strong>Data</strong><br/>
DuckDB | PostgreSQL | Apache Arrow | Parquet | pandas | NumPy | Streamlit | Tableau
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:4FC1FF,50:007ACC,100:79C0FF" width="100%"/>
</p>

<!-- CONNECT -->
<h2>📌 Let's Connect</h2>

<p>
📩 <strong>Email:</strong> <a href="mailto:asa618@sfu.ca">asa618@sfu.ca</a><br/>
🌐 <strong>Portfolio:</strong> <a href="https://aarmensidhu.netlify.app">aarmensidhu.netlify.app</a><br/>
💼 <strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/aarmensidhu/">linkedin.com/in/aarmensidhu</a><br/>
🐙 <strong>GitHub:</strong> <a href="https://github.com/aarmens702-hub">github.com/aarmens702-hub</a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,45:007ACC,100:4FC1FF&height=90&section=footer"/>
</p>
