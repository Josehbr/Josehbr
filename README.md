# José Hernane

**AI Engineer** — levo LLMs a produção: agentes em tempo real, RAG multifonte e pipelines de extração com verificação independente do modelo, sobre uma base de backend em Python, Rust e .NET.

Belo Horizonte, Brasil · [josehernane.dev](https://josehernane.dev) · [LinkedIn](https://www.linkedin.com/in/jos%C3%A9-hernane-16706b1b6/) · [josehernane83@gmail.com](mailto:josehernane83@gmail.com)

## Em produção

- **Coaching de IA em tempo real** — ~2 s da transcrição ao insight acionável durante a call. LiveKit, Deepgram em streaming, saída estruturada, Supabase Realtime; 500+ testes e quality gate de segurança no CI.
- **RAG multifonte** — calls, WhatsApp, GitHub e boards unificados em uma camada de contexto com pgvector, consumida por chat, API e MCP; suíte versionada de evals e custo rastreado via LiteLLM.
- **Extração verificada para petições jurídicas** — cascata de modelos, auditor independente com modelo e prompt próprios, mais de 20 invariantes determinísticas; 30–90 min de trabalho do advogado em ~2–3 min por caso.

Estudos de caso completos em [josehernane.dev/projetos](https://josehernane.dev/projetos).

## Open source

| Repositório | O que é |
|---|---|
| [Tokenizers-RS](https://github.com/Josehbr/Tokenizers-RS) | BPE, WordPiece, SentencePiece-BPE e Unigram LM implementados do zero em Rust, com benchmark de tempo e compressão |
| [Rinha-de-Backend-2026](https://github.com/Josehbr/Rinha-de-Backend---2026) | Detecção de fraude com busca vetorial k-NN em Rust sob 1 CPU e 350 MB — 27º lugar, p99 de 1,46 ms, zero falhas |
| [Tokenizacao-PMI-BPE](https://github.com/Josehbr/Tokenizacao-PMI-BPE) | O mesmo treinador BPE com seleção por PMI em Python, Rust e C++, comparados com metodologia rígida de bench |
| [triagem-inteligente (n8n)](https://github.com/Josehbr/n8n) | Triagem de mensagens de uma clínica com n8n + LLM — 100% em eval de 20 casos, US$ 0,001 por mensagem |
| [motor-chat-contextual](https://github.com/Josehbr/motor-chat-contextual) | Backend de chat com RAG + CAG: Flask, LangChain, ChromaDB, Redis e MySQL |

## Escrevo sobre engenharia de IA em produção

- [Antes do prompt: implementei os 4 algoritmos de tokenização dos LLMs em Rust](https://josehernane.dev/blog/antes-do-prompt-tokenizadores-llms-rust)
- [Rinha de Backend 2026: busca vetorial, Rust e engenharia com IA](https://josehernane.dev/blog/rinha-backend-2026-rust-ia-engenharia)
- [RAG, CAG ou arquitetura híbrida?](https://josehernane.dev/blog/rag-cag-ou-arquitetura-hibrida)
- [Observabilidade para agentes em produção](https://josehernane.dev/blog/observabilidade-agentes-producao)
- [Como medir qualidade, latência e custo](https://josehernane.dev/blog/medir-qualidade-latencia-custo)

## Stack

Python · FastAPI · Rust · C# / .NET · PostgreSQL / pgvector · Supabase · Prefect · LiteLLM · MCP · LiveKit · Deepgram · Docker · pytest / Vitest / Playwright
