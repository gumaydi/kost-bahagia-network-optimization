# Testing and results

[Home](../README.md) · [Evidence](evidence-index.md)

## 1. Observed client experience and completion

The project lead directly confirmed on **6 November 2026** that all installed Wi-Fi endpoints were operating normally following the field implementation, and that moving between covered zones felt **seamless in practical use**. This is a **field observation provided by the lead**. The archive does not contain an instrumented roaming walk test, measured handoff interruption, or proof that 802.11k/802.11v/802.11r features were enabled.

## 2. Recorded Speedtest screenshot

A shared screenshot dated **7 December 2025, 09:26** (`IMG-20251207-WA0018.jpg`) shows:

| Metric | Value |
| :-- | --: |
| Download | **338 Mbps** |
| Upload | **354 Mbps** |
| Idle ping | **13 ms** |
| Jitter | **1 ms** |

The screenshot documents one point-in-time test. The tested floor, client hardware, path and comparison baseline are not established. It must not be interpreted as the speed received by every AP or as a before/after benchmark.

## 3. Measurement boundaries

| Question | Current source |
| :-- | :-- |
| Were all 12 APs finally working? | **Yes, confirmed by lead** (E11) |
| Was moving between zones smooth? | **Yes, observed by lead** (E11) |
| Were timing, disruption and RSSI captured during roaming? | No surviving repeatable measurement |
| Is an advanced roaming standard proven active? | No controller/device feature export |
| Is there a controlled before/after performance dataset? | No comparable baseline |
| Is there a per-floor site-survey heatmap? | No archived signal survey |

## 4. Repeatable future test procedure

For each floor, document anonymized AP labels, date/time, client type, band, RSSI/SNR, active channel and width, gateway reachability, ping loss, repeated throughput, and a walking route with reassociation timing. Compare against consistent baselines and share only sanitized aggregates if permission allows. This is an enhancement opportunity rather than a claim about already-performed tests.
