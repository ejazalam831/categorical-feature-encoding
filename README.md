# Handling Non-Numeric Features: A Complete Guide

A comprehensive tutorial on encoding categorical variables for machine learning, covering nominal and ordinal features with practical examples.

## Overview

This notebook addresses one of the most common challenges in machine learning: converting categorical (non-numeric) features into formats that algorithms can understand. Using an employee dataset, it demonstrates various encoding techniques and when to apply them.

## Topics Covered

- **Categorical Feature Types**: Understanding nominal vs ordinal variables
- **Label Encoding Problems**: Why the naive approach often fails
- **One-Hot Encoding**: Best practices for nominal features with low cardinality
- **Target Encoding**: Handling high-cardinality categorical features
- **Ordinal Encoding**: Preserving natural order in ranked categories
- **Encoding Selection**: Choosing the right technique for your data

## Dataset

The tutorial uses a synthetic employee dataset containing:
- Departments (Sales, Engineering, Marketing, HR, Finance)
- Education levels (High School, Bachelor, Master, PhD)
- Cities (New York, Seattle, Miami, Denver, Chicago, Austin)
- Experience levels (Entry, Junior, Mid, Senior)
- Salary information

## Requirements

```python
pandas
numpy
scikit-learn
```

## Encoding Techniques Covered

### Nominal Features (No Natural Order)
- **One-Hot Encoding**: For low cardinality (≤10 categories)
- **Target Encoding**: For high cardinality with strong target relationships

### Ordinal Features (Natural Order Exists)
- **Ordinal Encoding**: Preserving hierarchical relationships

## Quick Reference

| Feature Type | Cardinality | Best Method | Reason |
|--------------|-------------|-------------|---------|
| Nominal | 2-10 categories | One-Hot Encoding | Preserves all information |
| Nominal | 10+ categories | Target Encoding | Reduces dimensionality |
| Ordinal | Any size | Ordinal Encoding | Maintains natural order |

## Contributing
Suggestions and improvements are welcome! Feel free to open an issue or submit a pull request.
