---
marp: true
size: 16:9
theme: am_purple
paginate: true
headingDivider: [2,3]
footer: \ *黄一展* *Alpa: Automating Inter- and Intra-Operator Parallelism for Distributed Deep Learning* *2024年1月13日（v1.3）*
---

<!-- _class: cover_a 
<!-- _header: "" --> 
<!-- _footer: "" --> 
<!-- _paginate: "" --> 

# Alpa: Automating Inter- and Intra-Operator Parallelism for Distributed Deep Learning

OSDI 2022
黄一展 
2024E8021682144 
HIAS


## Abstract
<!-- _class: trans -->
<!-- _footer: "" -->
<!-- _paginate: "" -->

## Abstract
- 问题与背景：当前GPU多作业的现状与存在的问题。在云环境下，由于负载对GPU不同资
源的需求不同，因此导致单应用独占方式导致GPU利用率过低。
> However, GPU-compute applications stress the GPU 
ar chitecture in different ways — leading to suboptimal resource utilization when a 
single GPU is used to run a single application.

- 解决方案与结果：作者提出的解决方案，包括此方案具体解决了什么问题，设计理念，以及最
后达到的效果.
> We propose the Hybrid Slowdown Model (HSM) to 
dynamically and accurately predict application slowdown due to interference.
we use HSM to guide various resource management schemes in multitask in GPUs. 
HSM significantly improves system throughput by 18.9%

## 1. Introduction
<!-- _class: trans -->
<!-- _footer: "" -->
<!-- _paginate: "" -->


## 2. Background: Distributed Deep Learning
<!-- _class: trans -->
<!-- _footer: "" -->
<!-- _paginate: "" -->


## 3. Overview
<!-- _class: trans -->
<!-- _footer: "" -->
<!-- _paginate: "" -->
 

## 4. Intra-Operator Parallelism
<!-- _class: trans -->
<!-- _footer: "" -->
<!-- _paginate: "" -->


## 5. Inter-Operator Parallelism
<!-- _class: trans -->
<!-- _footer: "" -->
<!-- _paginate: "" -->


## 6. Parallelism Orchestration
<!-- _class: trans -->
<!-- _footer: "" -->
<!-- _paginate: "" -->


## 7. Limitations and Discussion
<!-- _class: trans -->
<!-- _footer: "" -->
<!-- _paginate: "" -->


## 8. Evaluation
<!-- _class: trans -->
<!-- _footer: "" -->
<!-- _paginate: "" -->


## 9. Related Work
<!-- _class: trans -->
<!-- _footer: "" -->
<!-- _paginate: "" -->


## 10. Conclusion
<!-- _class: trans -->
<!-- _footer: "" -->
<!-- _paginate: "" -->