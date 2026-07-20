# Process Query Language (PQL)

This folder contains sample PQL calculations used in the Procure-to-Pay (P2P) Process Mining project.

## KPIs Created

- Purchase Orders
- Net Order Value
- Rework Rate
- Automation Rate
- Throughput Time
- Vendor Performance
- Process Variants

## Sample PQL

```pql
COUNT_TABLE("EKPO")

AVG(DAYS_BETWEEN("Purchase Order Created","Invoice Posted"))

SUM("Net Order Value")
