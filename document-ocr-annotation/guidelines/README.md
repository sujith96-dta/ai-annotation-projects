# Annotation Guidelines

## Project Overview

This project focuses on retail shelf annotation workflows used for computer vision and retail AI systems.

The dataset includes retail shelf images containing multiple products, price tags, shelf rows, and grouped SKUs.

---

# Annotation Objectives

- Product detection
- SKU grouping
- Price tag annotation
- Shelf segmentation
- Product classification

---

# Annotation Types

## Product
Used for identifying individual retail products on shelves.

## Product Group
Used for grouping identical SKUs together.

## Price Tag
Used for detecting and annotating retail price labels.

## Shelf Row
Used for identifying shelf sections and product placement structure.

## Signage
Used for retail promotional labels and signage.

---

# Annotation Rules

- Annotate fully visible products whenever possible
- Maintain accurate polygon or bounding boundaries
- Group identical SKUs consistently
- Separate price tags from products
- Ignore heavily blurred products
- Maintain consistent labeling across images
- Avoid overlapping annotations unless required

---

# Quality Validation

Quality review includes:

- Annotation consistency checks
- SKU grouping verification
- Boundary precision validation
- Missing annotation review
- Edge case analysis

---

# AI Use Cases

This type of dataset can support:

- Retail analytics
- Shelf intelligence systems
- Planogram validation
- Product availability monitoring
- Computer vision model training
- Smart inventory systems
