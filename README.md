# SWE-Bench Analysis

This repository contains tools and scripts to evaluate AI models against SWE-Bench datasets, which assess the ability of AI models to suggest correct patches for software engineering tasks.

## Features

- **Experiment Results Processing:** Load and process experiment results from various models.
- **Benchmark Analysis:** Compare model predictions with ground truth across Lite, Full, and Verified SWE-Bench datasets.
- **Statistics Generation:** Compute detailed statistics, including resolved vs. unresolved instances and per-model performance.

---

## Dataset Structure

Three main benchmarks are evaluated:

1. **Lite Bench:**
   - Smaller, more targeted dataset.
   - **Experiments (top 6):**
     - 20240702_codestory_aide_mixed
     - 20240820_honeycomb
     - 20240627_abanteai_mentatbot_gpt4o
     - 20240811_gru
     - 20240829_Isoform
     - 20240806_SuperCoder2.0

2. **Full Bench:**
   - Complete dataset.
   - **Experiments (top 5):**
     - 20240820_honeycomb
     - 20240509_amazon-q-developer-agent-20240430-dev
     - 20240617_factory_code_droid
     - 20240628_autocoderover-v20240620
     - 20240620_sweagent_claude3.5sonnet

3. **Verified Bench:**
   - Verified results from a wide range of experiments.
   - Includes models like Claude, GPT-4, and others.
  
Note: Lite and Full bench top experiments in October 10th, 2024
