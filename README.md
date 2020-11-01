# Overview of UNIFUZZ platform


## Introduction

UNIFUZZ is a platform for using and evaluating fuzzers conveniently.
UNIFUZZ consists of the following main components:
- Useable Fuzzers
- Benchmark
- Seeds
- Metrics for Evaluating Fuzzers


The corresponding paper will appear on USENIX Security 2021 [paper pdf](https://nesa.zju.edu.cn/download/UNIFUZZ%20A%20Holistic%20and%20Pragmatic%20Metrics-Driven%20Platform%20for%20Evaluating%20Fuzzers.pdf). 

For citing this paper:

```
@inproceedings{unifuzz-li,
	title={{UNIFUZZ}: A Holistic and Pragmatic Metrics-Driven Platform for Evaluating Fuzzers},
	author={Li, Yuwei and Ji, Shouling and Chen, Yuan and Liang, Sizhuang  and  Lee, Wei-Han and Chen, Yueyao and Lyu, Chenyang and Wu, Chunming and Beyah, Raheem and Cheng, Peng and Lu, Kangjie and Wang, Ting},
	booktitle={Proceedings of  the  30th {USENIX} Security Symposium},
	year={2021},
}
```

### 1. Useable Fuzzers

Currently we provide Dockerfile for 35 usable fuzzers.

https://github.com/unifuzz/dockerized_fuzzing


### 2. Benchmark 

Currently we provide 20 real-world programs for fuzzing evaluation.

https://github.com/unifuzz/unibench

In addition, we also provide Dockerfile for building these programs under different fuzzer instrumentations.

https://github.com/unifuzz/unibench_build


### 3. Seeds for Fuzzing

This repo consists of the seeds used in the evaluations of UNIFUZZ paper.

https://github.com/unifuzz/seeds

### 4. Metrics for Evaluating Fuzzers

https://github.com/unifuzz/metrics


### 5. Supplementary Results of UNIFUZZ Paper
Due to space limitaion of the published paper, we present some supplementary results of UNIFUZZ paper here. 

https://github.com/unifuzz/supplementary_results
