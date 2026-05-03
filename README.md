# Sync Labs

Sync Labs (sync.so) provides studio-grade AI lip-sync and visual dubbing APIs. Their technology synchronizes video lip movements with any audio track using state-of-the-art neural networks, enabling professional video dubbing, content localization, and personalized video generation at scale. Backed by Y Combinator.

## APIs

| API | Description |
|---|---|
| [Sync Labs API](https://sync.so/docs/introduction) | AI lip-sync REST API: single generation, batch, assets, models |
| [Python SDK](https://pypi.org/project/syncsdk/) | Official Python 3.8+ SDK (`pip install syncsdk`) |
| [TypeScript SDK](https://www.npmjs.com/package/@sync.so/sdk) | Official Node.js 18+ SDK (`npm i @sync.so/sdk`) |

## Models

| Model | Description | Cost/sec |
|---|---|---|
| sync-3 | Most powerful, 4K native, professional grade | $0.133 |
| lipsync-2-pro | Premium quality, enhanced facial detail | $0.067 |
| lipsync-2 | General purpose, preserves speaking style | $0.035 |
| lipsync-1.9 | Fastest, maximum speed for simple videos | $0.020 |
| react-1 | Expressive lip sync with emotions | Custom |

## OpenAPI Specifications

| Spec | File |
|---|---|
| Sync Labs API v2 | [openapi/sync-labs-openapi.yml](openapi/sync-labs-openapi.yml) |

## Capabilities

### Shared Per-API Definitions

| Capability | Description |
|---|---|
| [Sync Labs API](capabilities/shared/sync-labs-api.yaml) | Generation, batch, assets, models, cost estimation |

### Workflow Capabilities

| Workflow | Description |
|---|---|
| [Video Dubbing](capabilities/video-dubbing.yaml) | Full dubbing workflow: generate, batch, estimate, monitor |

## Artifacts

| Type | Resource |
|---|---|
| Spectral Rules | [rules/sync-labs-rules.yml](rules/sync-labs-rules.yml) |
| JSON Schema - Generation | [json-schema/sync-labs-generation-schema.json](json-schema/sync-labs-generation-schema.json) |
| JSON Structure - Generation | [json-structure/sync-labs-generation-structure.json](json-structure/sync-labs-generation-structure.json) |
| JSON-LD Context | [json-ld/sync-labs-context.jsonld](json-ld/sync-labs-context.jsonld) |
| Example - Create Generation | [examples/sync-labs-create-generation-example.json](examples/sync-labs-create-generation-example.json) |
| Vocabulary | [vocabulary/sync-labs-vocabulary.yml](vocabulary/sync-labs-vocabulary.yml) |

## Links

- **Website**: https://sync.so
- **Documentation**: https://sync.so/docs/introduction
- **Quickstart**: https://sync.so/docs/quickstart
- **Pricing**: https://sync.so/pricing
- **API Keys**: https://sync.so/settings/api-keys
- **Y Combinator**: https://www.ycombinator.com/companies/sync-2
- **Contact**: hello@sync.so

## Maintainers

**Kin Lane** | kin@apievangelist.com
