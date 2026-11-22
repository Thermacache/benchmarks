# ThermaCache AI - Public Benchmark Suite &amp; Specification

Welcome to the public benchmarks and architecture specification repository for ThermaCache AI.

This repository contains:

1. colab\_50\_stream\_suite.py: The ready-to-run 50-stream concurrent stress test harness.
2. docs/: Full PDF technical research reports, ROI spreadsheets, and architecture charts.
3. spec/: Detailed mathematical models for the Power-of-Two-Choices (P2C) Joint Cost Scheduler.

---

## 📊 Live 50-Stream Concurrency Test Results

* Total Concurrent Requests Sent: 50
* Out-Of-Memory Crashes Verification: 0 OOM Crashes (100% Safe)
* Parallel Threads Executed: 50
* Overall Cache Hit Rate: 46.0% - 65.0%
* Avg TTFT Prefill Speedup (Warm Cache Hit): 0.0369s (36.9 ms)
* P50 (Median) Response Latency: 0.0454s (45.4 ms)
* P99 Tail Latency Spike Limit: 0.0645s (64.5 ms)
* Peak GPU Junction Temp Limit: 62.4°C (Target Limit: &lt;63.0°C)
* Peak P2C Server Routing Queue Depth: 11 (Avg: 1.96)
