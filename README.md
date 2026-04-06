# putkoff · Abstract Endeavors

> Systems for markets, media, and models — built to stay legible under pressure.

---

## Approach

- **Schemas over ad-hoc objects**
- **Registries over globals**
- **Queues over callbacks**
- **Explicit wiring over ambient configuration**

I optimize for systems that remain understandable, debuggable, and trustworthy after they’ve grown large enough to matter.

---

## Systems

### **SolCatcher**
Real-time Solana market-data infrastructure for log ingestion, deterministic decoding, staged persistence, and fault-isolated processing.  
[Repo](https://github.com/AbstractEndeavors/solcatcher) · [API](https://api.solcatcher.io) · [Explorer](https://solcatcher.io/)

### **abstract_solana**
Schema-driven Python SDK for Solana JSON-RPC with typed body builders, PostgreSQL/JSONB caching, rate limiting, RPC fallback, and PumpFun curve utilities.  
[Repo](https://github.com/AbstractEndeavors/abstract_solana)

```python
from abstract_solana.abstract_rpcs import abstract_solana_rate_limited_call
from abstract_solana.pumpFun import derive_bonding_curve_accounts, isOnCurve

balance = abstract_solana_rate_limited_call("getBalance", pubkey="YourWalletHere")

if isOnCurve(mint):
    accounts = derive_bonding_curve_accounts(mint)
````

### **EthCatcher / PutNodeContracts**

On-chain financial infrastructure across swap execution, liquidity interaction, deterministic fee accounting, asset lifecycle tracking, and incentive-driven protocol mechanics.
[EthCatcher](https://ethcatcher.io/) · [Contracts](https://github.com/putkoff/PuTnodeContracts)

### **abstract-media-intelligence**

A modular media intelligence platform for turning PDFs, images, and video into searchable, structured, SEO-ready datasets.
[Platform](https://github.com/AbstractEndeavors/abstract-media-intelligence)

| Module                                                                  | Function                                       |
| ----------------------------------------------------------------------- | ---------------------------------------------- |
| [abstract_hugpy](https://github.com/AbstractEndeavors/abstract_hugpy)   | Summarization, keywords, metadata, refinement  |
| [abstract_pdfs](https://github.com/AbstractEndeavors/abstract-pdfs)     | PDF decomposition, manifests, HTML publishing  |
| [abstract_videos](https://github.com/AbstractEndeavors/abstract-videos) | Video ingestion, transcription, frame analysis |
| [abstract_ocr](https://github.com/AbstractEndeavors/abstract-ocr)       | Layout-aware OCR and structured extraction     |

### **abstract_shapes**

GeoJSON-based spatial filtering and proximity-driven targeting for deterministic lead qualification and geographic decision systems.
[Repo](https://github.com/AbstractEndeavors/abstract_shapes) · [Live](https://abstractendeavors.com/maps)

### **Solar Simulation**

Physics simulation for trajectory modeling, orbital interaction, and system analysis in dynamic gravitational environments.
[Live](https://abstractendeavors.com/SolarSimulation) · [Repo](https://github.com/AbstractEndeavors/abstract-solar-sim)

### **CalcIt**

Typed interface for math and physics APIs with live evaluation, unit-aware inputs, and direct endpoint exploration.
[Live](https://abstractendeavors.com/calcit) · [API](https://math.abstractendeavors.com/endpoints)

### **Loan Payoff Calculator**

Debt modeling and payoff analysis.
[Live](https://abstractendeavors.com/loans)

### **Debt & Inflation Calculator**

Scenario-based debt and inflation analysis.
[Live](https://abstractendeavors.com/debt)

---

## Stack

`Python` · `TypeScript` · `PostgreSQL / JSONB` · `Solana / solders` · `JSON-RPC` · `HuggingFace` · `GeoJSON` · `Solidity / EVM`

---

## Network

[abstractendeavors.com](https://abstractendeavors.com)
[thedailydialectics.com](https://thedailydialectics.com)
[clownworld.biz](https://clownworld.biz/)
[solcatcher.io](https://solcatcher.io/)
[ethcatcher.io](https://ethcatcher.io/)
[jrputkey.com](https://jrputkey.com/)
[partners@abstractendeavors.com](mailto:partners@abstractendeavors.com)

