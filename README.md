# Prajit Rahul

Software Engineer | ML Compiler Engineering | AI Inference and Model Optimization

I work on ML compilers and inference systems, from tensor operation lowering and runtime integration to model export, benchmarking, and compression. M.S. in Computer Science, University of Southern California.

## Open Source Contributions

- **IREE encoding interfaces** — Generalized encoding capability checks across type propagation, HAL-to-Stream conversion, and dispatch dimension handling. [IREE #25089](https://github.com/iree-org/iree/pull/25089)
- **Quantized operator lowering** — Developed torch-mlir lowering for quantized batched matrix multiplication, handling zero points, signedness, and integer widths. [torch-mlir #4791](https://github.com/llvm/torch-mlir/pull/4791)
- **MLIR control-flow correctness** — Fixed parsing and printing of wide and negative switch-case values and added range diagnostics and regression tests. [LLVM #221490](https://github.com/llvm/llvm-project/pull/221490)
- **IREE CPU backend and WebAssembly** — Added missing double-precision math support in the LLVM CPU backend and WebAssembly bitcode libraries. [IREE #24953](https://github.com/iree-org/iree/pull/24953)
- **AMD RDNA4 code generation** — Added IREE regression tests for matrix instruction selection and packed tensor layouts, with CMake and Bazel integration. [IREE #24924](https://github.com/iree-org/iree/pull/24924)

## Compiler Engineering

- Develop C++ compiler changes with LLVM, MLIR, torch-mlir, and IREE, including tensor lowering to Linalg, numerical correctness, and runtime integration.
- Integrate RISC-V CPU microkernels into IREE, covering data tiling and packing, hardware feature detection, runtime dispatch, and cross-compilation.
- Validate compiler transformations and generated code with lit, FileCheck, IR inspection, numerical comparisons, and end-to-end execution.

## AI Inference and Optimization

- Build ONNX Runtime evaluation workflows for vision, vision-language, and audio models, covering ONNX export, dataset preparation, accuracy scoring, and inference performance.
- Benchmark LLM serving with vLLM on AMD Instinct MI300X, measuring time to first token and generation throughput. Fine-tune Llama models with LoRA and GRPO.
- Apply knowledge distillation and post-training quantization to reduce model footprint for edge inference. [Lightweight Multilingual Translation for Edge Devices](https://github.com/Prajit-Rahul/Lightweight-Multilingual-Translation-for-Edge-Devices)

## Technical Skills

- **Compiler and build tools** — C++, Python, LLVM, MLIR, Linalg, torch-mlir, IREE, CMake, Bazel, lit, FileCheck
- **Inference and model optimization** — PyTorch, ONNX, ONNX Runtime, vLLM, LoRA, GRPO, knowledge distillation, post-training quantization
- **GPU programming** — HIP, ROCm, Triton

**Certification** — AMD ROCm Certified Associate

## Contact

- [Email](mailto:pselvam@usc.edu)
- [Portfolio](https://prajit-rahul.github.io/portfolio-website/)
