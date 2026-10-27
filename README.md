### Shoujun Diao · 刁寿钧

I build the inference infrastructure behind generative-AI products, and I like explaining systems well enough that other people can see them.

**Now** · Backend architect at [Lovart](https://www.lovart.ai), an AI-agent product: service topology, gateways, the model and tool access layers, and what inference costs. Recent work: core services Python → Go, a 30% TTFT cut that let a 14-node H200 cluster run on 6, and routing with fallback across 10+ model vendors.

**Before** · Nine years at Tencent (2016–2025). Five of them as tech lead for the gateway, AutoML and data-processing modules of Tencent Cloud's TI platform, from zero to commercialization; its AI gateway took a 100× traffic surge during the DeepSeek boom without an incident. Before that, edge computing and AI cameras at YouTu Lab, and the brand-advertising platform.

**Writing** · [diaosj.info](https://diaosj.info). In progress: *A model gateway is a routing problem, not a proxy* · *Burn-down: a cost model for inference* · *Leaving one cloud: notes from a multi-cloud migration*.

#### Things here

| Infra | Explaining systems | Tools |
| --- | --- | --- |
| [p2c-simulator](https://github.com/diaosj/p2c-simulator) · 5k QPS across 300 rate-limited nodes; why power-of-two-choices beats a global scan | [https-simulator](https://https-simulator.vercel.app) · TLS handshake, certificates and MITM, animated | [bar-raiser-cli](https://github.com/diaosj/bar-raiser-cli) · Socratic interview drills with Claude, in Rust |
| | [concurrency-arena](https://concurrency-arena.vercel.app) · process vs thread vs event loop vs goroutine under I/O and CPU load | [my-garden](https://github.com/diaosj/my-garden) · the site itself, Astro |

Elsewhere: speaker in the Apache APISIX community; co-translator of *Problem Solving with Algorithms and Data Structures Using Python* (2019) and translator of *Practical Data Analysis* (2018); self-taught Go (weiqi) player, amateur 5-dan.

shoujun.diao@gmail.com · Shanghai
