# Building Knowledge Graphs from Unstructured Text

## Project Overview
This project focuses on extracting structured knowledge from unstructured text using Natural Language Processing (NLP) techniques. The extracted information is represented in the form of a knowledge graph, which helps in understanding relationships between different entities within a text. 

## Features
- Named Entity Recognition (NER)
- Relation Extraction (RE) using the REBEL model
- Knowledge Graph Construction
- Data Normalization and Filtering
- Visualization of Knowledge Graphs

## Methodology
The process involves the following steps:
1. **Data Collection**: Extracting data from unstructured text sources.
2. **Text Preprocessing**: Cleaning and normalizing text for better extraction.
3. **Named Entity Recognition (NER)**: Identifying important entities in the text.
4. **Relation Extraction (RE)**: Identifying relationships between entities.
5. **Graph Construction**: Structuring extracted information into a knowledge graph.
6. **Visualization**: Representing the knowledge graph visually.

## Files Included
### 1. NLP Processing Code
- **NLP_Project.ipynb**: A Jupyter Notebook implementing the entire NLP pipeline, including entity extraction, relation extraction, and knowledge graph construction.

### 2. Frontend Visualization Files
- **network_napoleon_long_text.html**: Knowledge graph visualization for long text analysis.
- **network_napoleon_small_text.html**: Knowledge graph visualization for small text analysis.
- **network_napoleon_wikipedia_kb.html**: Knowledge graph visualization using Wikipedia-based knowledge extraction.

## Dependencies
Ensure you have the following dependencies installed:
```bash
pip install transformers torch spacy networkx matplotlib bs4
```

## Usage
1. Open and run the `NLP_Project.ipynb` notebook.
2. Process a text file or enter text manually.
3. Generate and visualize the knowledge graph using the HTML files.
4. Open the visualization files in a browser to explore the extracted relationships.

## References
1. An, B., Chen, B., Han, X., & Sun, L. (2018). Accurate text-enhanced knowledge graph representation learning.
2. Kertkeidkachorn, N., & Ichise, R. (2017). T2kg: An end-to-end system for creating a knowledge graph from unstructured text.

## Future Work
- Improve entity extraction and relation classification accuracy.
- Expand multilingual support for knowledge graph generation.
- Develop a user-friendly web-based interface for visualization.

## License
This project is open-source and available under the MIT License.
