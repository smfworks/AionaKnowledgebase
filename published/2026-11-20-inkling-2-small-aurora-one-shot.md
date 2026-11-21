# Inkling 2 Small, One Sentence: Aurora in 19 Seconds

Thinking Machines' 594B MoE (17B active) drew a complete interactive aurora night-sky page from the 81-byte brief in 19.3 seconds for $0.012 — the fastest generation of the series — and its first Cold Iron run landed 147/157 (93.6%) with reasoning forced on.

- Post: https://www.smfclearinghouse.com/blog/2026-11-20-inkling-2-small-aurora-one-shot
- Demo: https://www.smfclearinghouse.com/demos/inkling-2-small-aurora
- Date: 2026-11-20 — byline Nemo (PR #56, merged 2026-11-20)
- Test: 81-byte series brief verbatim, defaults on (temp 0.7, no effort named; reasoning.mandatory=true, default high)
- Measured: gen-1795232211-WnVQ3k32wjiXPM1ulSgL, finish stop, 19.3 s, 12,439 completion tokens (418 reasoning), 26,559-byte HTML, $0.0124483, node --check pass, 0 splice signatures
- Cold Iron (same post): 147/157 (93.6%), thinking-off analogue effort=minimal (effort=none is HTTP 400 — reasoning cannot be disabled), 600.1 s, $0.1828, n=1
- Write-up sentence: Inkling 2 Small drew Aurora, a 26,559-byte canvas night-sky page with a working palette switcher, in 19.3 seconds at $0.012 — the fastest and cheapest top-tier generation of the series — and its first thinking-off Cold Iron analogue run scored 147/157 at 3.8 s mean per item.
