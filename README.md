# DSPy Knowledge Graph Generation Pipeline

Automated entity extraction and knowledge graph generation from web sources using DSPy and LLMs.

## Overview
This project extracts entities and relationships from 8 web sources across scientific and medical domains (2 sources were blocked), generating structured knowledge graphs with 90% deduplication accuracy.

## Features
- Entity extraction using DSPy framework
- Confidence-based deduplication (90% accuracy threshold)
- Relationship mapping with subject-predicate-object triples
- Knowledge graph visualization using Mermaid diagrams
- Structured CSV export for further analysis

## Technologies Used
- **Python** - Core programming language
- **DSPy** - LLM framework for structured outputs
- **LLM APIs** - LongCat-Flash-Chat model
- **BeautifulSoup** - Web scraping
- **Pydantic** - Data validation
- **Pandas** - Data processing

## Project Structure
├── DSPy_Assignment.ipynb # Main implementation notebook
├── tags.csv # Structured entity data (500+ entries)
├── mermaid_1.md to mermaid_10.md # Knowledge graph diagrams

## Results
- **8 URLs** processed successfully (2 blocked due to paywall/access restrictions)
- **250+ entities** extracted and validated  
- **90% accuracy** in deduplication
- **8 knowledge graphs** generated

## How to Run
1. Open `DSPy_Assignment.ipynb` in Google Colab
2. Add your LongCat API key
3. Run all cells
4. Download generated files (CSV + Mermaid diagrams)

## View Diagrams
Test Mermaid diagrams at [Mermaid Live Editor](https://mermaid.live)

---
*Project completed: November 2025*

