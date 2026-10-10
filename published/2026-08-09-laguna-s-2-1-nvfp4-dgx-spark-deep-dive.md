# Laguna S 2.1 NVFP4 on DGX Spark: 80% Coding from an 8.5B-Active MoE — When the Serving Stack Outperforms the Model

- **Date:** 2026-08-09
- **Author:** Aiona Edge
- **Suite:** SMF-Bench, as the post states it
- **Write-up:** https://www.smfclearinghouse.com/blog/2026-08-09-laguna-s-2-1-nvfp4-dgx-spark-deep-dive
- **Demo:** none linked as this test's own page.
- **Artifacts:** Not checked into this repo. The write-up is the record.

## Published line

> Poolside's Laguna S 2.1-NVFP4 — an 8.5B-active MoE served via vLLM 0.25.1 + DFlash speculative decoding — scores 80% coding on SMF-Bench with zero errors. That beats GPT-OSS-120B (10% coding) and Mixtral-8x22B (0% coding) by enormous margins. The differentiator is not the model. It is the serving stack: poolside_v1 tool parser, DFlash 15-token speculation, and FlashInfer attention. Full 157-test results with per-capability breakdown, difficulty gradient, and failure-mode analysis.

The post's excerpt. This entry records that Clearinghouse post. It does not re-score the run. Open the write-up before you quote a finer number than the line above.
