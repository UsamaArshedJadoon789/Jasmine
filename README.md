# Big Data Analytics Technology Implementation

This repository contains implementations for two main tasks:

## Task 1: Graph In-degree Distribution Computation
Implementation of in-degree distribution computation across three platforms:
- Apache Hadoop
- Apache Spark (GraphX)
- JasmineGraph

### Datasets
- Epinions social network
- Youtube Social Network
- Google Web Graph
- LiveJournal social network (scaling test)

## Task 4: Watermarks in Data Stream Processing
Implementation of stream processing applications using:
- Apache Kafka
- Apache Flink

### Datasets
- EDGAR log datasets
- Generated 1M record dataset using OOSimulator

## Repository Structure
```
.
├── data/
│   ├── graph/          # Graph datasets for Task 1
│   ├── edgar_small/    # Small EDGAR datasets for Task 4
│   └── edgar_large/    # Large EDGAR dataset for Task 4 scaling
├── hadoop/             # Hadoop implementation
├── spark/              # Spark GraphX implementation
├── jasminegraph/       # JasmineGraph implementation
├── kafka-flink/        # Kafka and Flink implementation
└── docs/
    ├── screenshots/    # Setup and execution screenshots
    └── plots/          # Performance visualization plots
```

## Setup and Configuration
Detailed setup instructions for each platform will be documented in their respective directories.

## Performance Analysis
Performance metrics and comparisons will be documented in the docs directory.
