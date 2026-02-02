SIP — Streamed Inference Pipeline
Run 400B+ parameter AI models on consumer hardware with as little as 12GB of RAM.
What is SIP?
SIP is an inference engine that breaks the memory barrier for large language models. Instead of loading an entire model into memory, SIP streams model layers on demand from disk — loading only what's needed, when it's needed.
The result: frontier-scale AI models running on hardware that costs a fraction of traditional GPU infrastructure.
Why SIP?
Running large AI models today requires expensive, specialised hardware — multiple enterprise GPUs with hundreds of gigabytes of VRAM. This locks frontier AI capabilities behind a wall that only well-funded companies and research labs can afford.
SIP changes the equation. By treating model weights as a streamable resource rather than a monolithic memory block, SIP dramatically reduces the hardware requirements for inference. A model that conventionally demands 200GB+ of VRAM can run on a device with 12GB of RAM and a fast storage drive.
Key Features

Layer-level weight streaming — only one layer in memory at a time during inference
Intelligent layer routing — not every query needs every layer, SIP skips what isn't needed
Adaptive depth — simple queries run fast through fewer layers, complex queries use the full model
Hardware agnostic — runs on anything with sufficient RAM and storage, from laptops to single-board computers
Open model support — works with openly available model weights

Status
🚧 Work in progress — SIP is currently in early development. Watch this repo for updates.
License
Apache 2.0 — see LICENSE for details.
