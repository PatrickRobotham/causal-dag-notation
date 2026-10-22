# causal-dag-notation
An extended notation for represent Causal Dags. Inspired by Pearl, McElreath, Gelman 


The main idea: extend the node of a dag.

A metric has a lot of implicit data that is not represented in a default causal dag, such as:

1. The granularity of the metric.
2. The model equation behind a metric.
3. Where the data (if it exists) comes from to measure that metric.

This notation is intended to provide these extra pieces of metadata, so that it's easier to get a more complete view of what a statistical model actually does.
