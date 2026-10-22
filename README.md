# causal-dag-notation
An extended notation for represent Causal Dags. Inspired by Pearl, McElreath, Gelman 


The main idea: extend the node of a dag.

A metric has a lot of implicit data that is not represented in a default causal dag, such as:

1. The granularity of the metric.
2. The model equation behind a metric.
3. Where the data (if it exists) comes from to measure that metric.

This notation is intended to provide these extra pieces of metadata, so that it's easier to get a more complete view of what a statistical model actually does.



## Example

Consider the model in [Statistical Rethinking 2024](https://github.com/rmcelreath/stat_rethinking_2024/blob/main/slides/Lecture_14-GLMM3.pdf)

<img width="2000" height="1125" alt="image" src="https://github.com/user-attachments/assets/1f59e9a5-4139-468e-a707-4f88ffdcd85d" />

The Dag does not capture:
1. The granularity of each node,
2. The formulas,
3. What the nodes are,
4. What the estimands are.


With my notation I'd represent this as...


```mermaid
flowchart TD


```
