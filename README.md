# 🚀 Azure AI Learning Roadmap (LLMs, SLMs, RAG, Vector Search)

Este repositório contém um plano de estudos prático e progressivo para aprender **IA generativa usando Azure**, com foco em:

- Azure AI Foundry
- Azure AI Search (RAG)
- CosmosDB Vector Search
- Modelos LLMs/SLMs (ex: GPT, Phi-3, Mistral)
- Criação de copilotos práticos e APIs com OpenAPI

---

## 📅 Cronograma de 4 semanas

### ✅ Semana 1: Fundamentos e Copilotos
| Dia | Tema | Conteúdo |
|-----|------|----------|
| 1   | Introdução à Azure AI Studio | Criar primeiro copiloto e testar interface |
| 2   | LLMs vs SLMs | Diferenças, aplicações e modelos disponíveis |
| 3   | Prompt Engineering | Temperatura, exemplos, system prompt |
| 4   | Fontes de conhecimento | Upload de arquivos .pdf, .txt, .md |
| 5   | Busca externa via ferramenta | Usar plugin de pesquisa externa |
| 6   | Projeto 1: Copiloto de Produto | Criar copiloto para responder dúvidas sobre produto interno |
| 7   | Revisão | Anotar bons prompts e melhorias |

---

### 🔍 Semana 2: Azure AI Search + RAG
| Dia | Tema | Conteúdo |
|-----|------|----------|
| 8   | Introdução a RAG | Conceito e arquitetura |
| 9   | Criar índice no AI Search | Indexação de PDFs ou dados estruturados |
| 10  | Conectar ao copiloto | Fonte de conhecimento baseada em AI Search |
| 11  | Relevância e filtros | Filtros por metadados e boosting |
| 12  | Projeto 2: Base de conhecimento | Copiloto com documentos internos da empresa |
| 13  | Melhoria de precisão | Ajustes no prompt e estrutura de indexação |
| 14  | Apresentação do projeto | Documentação e demo |

---

### 🧠 Semana 3: CosmosDB Vector Search
| Dia | Tema | Conteúdo |
|-----|------|----------|
| 15  | Vetores e embeddings | Conceitos básicos de semântica |
| 16  | Embeddings com OpenAI | Geração com `text-embedding-ada-002` ou Phi-3 |
| 17  | CosmosDB com vetores | Armazenamento de vetores + metadados |
| 18  | Busca vetorial | Similaridade via `vectorSearch` |
| 19  | Projeto 3: FAQ Vetorial | FAQ inteligente com base em embeddings |
| 20  | Conectar copiloto via OpenAPI | Ferramenta externa chamando CosmosDB |
| 21  | Comparativo | AI Search vs CosmosDB Vector |

---

### 🧩 Semana 4: Integração e Projetos Finais
| Dia | Tema | Conteúdo |
|-----|------|----------|
| 22  | Agentes com múltiplas fontes | Uso combinado de AI Search, ferramentas e embeddings |
| 23  | Prompt avançado | CoT, few-shot, funções persistentes |
| 24  | Projeto final | Copiloto completo: RAG + Vetor + API externa |
| 25  | Logging | Application Insights para copilotos |
| 26  | UX de respostas | Refinar tom, instruções e mensagens de fallback |
| 27  | Publicação | Deploy e embed em aplicações |
| 28  | Conclusão | Checklist e próximos passos |

---

## 📁 Estrutura sugerida do repositório
```
azure-ai-learning-roadmap/
│
├── copilotos/
│   ├── copiloto-produto-foundry.yaml
│   ├── copiloto-interno-ai-search.yaml
│   └── copiloto-faq-cosmosdb.yaml
│
├── prompts/
│   ├── boas-praticas.md
│   └── exemplos-chain-of-thought.md
│
├── notebooks/
│   ├── gerar-embeddings.ipynb
│   └── buscar-vetores-cosmosdb.ipynb
│
├── openapi-tools/
│   └── status-pedido-api.yaml
│
└── README.md
```

---

## ✨ Exemplos de Projetos

### 🧾 Copiloto de Produto Interno
- Responde perguntas sobre funcionalidades, integração e preços
- Fonte: documentos PDF + AI Search

### 📚 Base de conhecimento para RH
- Documentos internos + CosmosDB Vetorial
- Permite consulta por linguagem natural

### 🛠️ Integração com OpenAPI
- Copiloto que consulta status de pedido ou calcula valor

---

## 📌 Requisitos
- Azure Subscription com acesso ao AI Studio
- Habilitação do Azure OpenAI e AI Search
- CosmosDB com suporte a vetores (preview)

---

> Feito por [Juliana Wisniewski] 💙 com foco em aprendizagem contínua na nuvem ☁️


