# AI Model Databases

A community-maintained registry of AI model databases, pricing trackers, and capability catalogs.

## Background

There is no single database with information about all the available AI model databases. We started this as a community-contributed project to address that.

[![xkcd 927: Standards](https://imgs.xkcd.com/comics/standards.png)](https://xkcd.com/927/)

*[xkcd 927](https://xkcd.com/927/)*

## The Registry

| # | Database | URL | Form |
|---|---|---|---|
| 1 | Models.dev | https://models.dev/ | Web |
| 2 | Helicone LLM Cost | https://www.helicone.ai/llm-cost | Web |
| 3 | PricePerToken | https://pricepertoken.com/ | Web |
| 4 | Artificial Analysis | https://artificialanalysis.ai/api-reference | Web |
| 5 | LiteLLM model catalog | https://docs.litellm.ai/docs/providers | Library (Python) |
| 6 | simonw/llm-prices | https://github.com/simonw/llm-prices | Repo |
| 7 | assistant-ui/modelpedia | https://github.com/assistant-ui/modelpedia | Repo |
| 8 | pydantic/genai-prices | https://github.com/pydantic/genai-prices | Library (Python) |
| 9 | Portkey-AI/models | https://github.com/Portkey-AI/models | Repo |
| 10 | truefoundry/models | https://github.com/truefoundry/models | Repo |
| 11 | agentstation/starmap | https://github.com/agentstation/starmap | Repo |
| 12 | dcSpark/ai-model-catalog | https://github.com/dcSpark/ai-model-catalog | Repo |
| 13 | mitkury/aimodels | https://github.com/mitkury/aimodels | Repo |
| 14 | nuxdie/ai-pricing | https://github.com/nuxdie/ai-pricing | Repo |

Machine-readable version: [`databases.json`](databases.json).

## Scope

In scope: any project whose primary purpose is to enumerate AI models, their pricing, capabilities, context windows, providers, or benchmarks.

Out of scope: inference SDKs that happen to ship a model list as an internal implementation detail, single-provider model pages, blog posts.

## Contributing

Found one we missed? Open a PR adding it to [`databases.json`](databases.json). See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

[MIT](LICENSE)
