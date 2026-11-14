<h1 align="center">Prajit Rahul</h1>

<p align="center">
  <strong>Software Engineer</strong><br>
  ML Compilers · AI Inference and Optimization
</p>

<p align="center">
  M.S. in Computer Science, University of Southern California<br>
  AMD ROCm Certified Associate
</p>

<p align="center">
  <a href="https://prajit-rahul.github.io/portfolio-website/">Portfolio</a> ·
  <a href="mailto:pselvam@usc.edu">Email</a>
</p>

<p align="center">
  <a href="#open-source-contributions">Open Source</a> ·
  <a href="#compiler-engineering">Compiler Engineering</a> ·
  <a href="#ai-inference-and-optimization">AI Inference</a> ·
  <a href="#ai-engineering">AI Engineering</a> ·
  <a href="#selected-projects">Projects</a> ·
  <a href="#technical-skills">Technical Skills</a>
</p>

## Open Source Contributions

| Pull request | Contribution |
| --- | --- |
| [IREE #25089](https://github.com/iree-org/iree/pull/25089) | **Encoding interfaces**<br>Generalized encoding capability checks across type propagation, HAL-to-Stream conversion, and dispatch dimension handling. |
| [torch-mlir #4791](https://github.com/llvm/torch-mlir/pull/4791) | **Quantized operator lowering**<br>Lowered quantized batched matrix multiplication, handling zero points, signedness, and integer widths. |
| [torch-mlir #4810](https://github.com/llvm/torch-mlir/pull/4810) | **GridSample lowering correctness**<br>Improved nearest-even rounding and tensor access safety, with numerical regression tests. |
| [LLVM #221490](https://github.com/llvm/llvm-project/pull/221490) | **MLIR control-flow correctness**<br>Fixed switch-case parsing and printing for wide and negative integers. Added range diagnostics and regression tests. |
| [IREE #24953](https://github.com/iree-org/iree/pull/24953) | **CPU and WebAssembly math support**<br>Added double-precision math support in IREE’s LLVM CPU backend and WebAssembly bitcode libraries. |
| [IREE #24924](https://github.com/iree-org/iree/pull/24924) | **AMD RDNA4 code generation**<br>Added tests for matrix instruction selection and packed tensor layouts, with CMake and Bazel integration. |

## Compiler Engineering

- Developed **C++ compiler changes** across LLVM, MLIR, torch-mlir, and IREE, covering tensor lowering to Linalg, numerical correctness, and runtime integration.
- Worked on **LLVM pass plugins and runtime instrumentation**, including pass registration, IR traversal, instrumentation placement, and runtime linkage.
- Validated **compiler transformations and generated code** with lit, FileCheck, IR inspection, numerical comparisons, and end-to-end execution.

## AI Inference and Optimization

- Built the **Edge AI Inference Benchmark** for vision, vision-language, audio anomaly detection, and speech recognition. Exported models to ONNX, verified inference outputs, and integrated them into ONNX Runtime.
- Prepared **MMStar, ImageNet, NYUv2, ToyADMOS, and LibriSpeech** for evaluation. Implemented task-specific accuracy scoring and ran inference performance benchmarks separately.
- Benchmarked **vLLM serving on AMD Instinct MI300X**, measuring time to first token and generation throughput.
- Fine-tuned **Llama 3.1 8B Instruct** on GSM8K with Unsloth, LoRA, and GRPO. Tested the saved adapter with sample inference.

## AI Engineering

- Built an **AI observability assistant** that connects to Prometheus, Grafana, and Datadog through MCP servers, with schema discovery, query generation, validation, and retries.
- Developed a **semantic search API** with FastAPI, PostgreSQL, and pgvector, using HNSW indexing, tenant isolation, and group-based access controls.

## Selected Projects

- **Lightweight Multilingual Translation for Edge Devices.** Distilled language-specific MarianMT teachers into a smaller multilingual student and applied post-training quantization for edge inference. [Project repository](https://github.com/Prajit-Rahul/Lightweight-Multilingual-Translation-for-Edge-Devices)
- **Multimodal Stock Forecasting.** Compared SARIMA, LSTM, T5, and Temporal Fusion Transformer models using historical prices, text sentiment, and market indicators. [Project repository](https://github.com/Prajit-Rahul/Transformer-Based-Multi-Modal-Stock-Market-Prediction)

## Technical Skills

| Area | Tools |
| --- | --- |
| **Compiler and build tools** | `C++` `Python` `LLVM` `MLIR` `Linalg` `torch-mlir` `IREE` `CMake` `Bazel` `lit` `FileCheck` |
| **AI inference and fine-tuning** | `PyTorch` `ONNX` `ONNX Runtime` `vLLM` `LoRA` `GRPO` |
| **GPU programming** | `HIP` `ROCm` `Triton` |
| **Other** | `FastAPI` `Node.js` `PostgreSQL` `pgvector` `Docker` `Kubernetes` `MCP` |
