
# Graph + Transformers for Epidemology networks

This project aims to design an experimental model to identify epidemic networks using a sample graph dataset from Foursquare. The project utilizes advanced machine learning and graph-based techniques to analyze and identify patterns within the data that can help in understanding the spread of epidemics.

---

## Features

### 1. Data Handling and Preparation
   - **Dataset Loading**: Uses Foursquare check-in data, loaded into a pandas DataFrame.
   - **Data Preprocessing**: Includes steps to clean and preprocess the data, making it suitable for analysis and modeling.

### 2. Graph-Based Analysis
   - **Graph Construction**: Constructs graphs from the dataset, representing locations and check-ins as nodes and edges.
   - **Graph Embedding**: Applies graph embedding techniques to transform the graph structure into feature vectors.

### 3. Machine Learning Models
   - **Graph Neural Networks**: Utilizes Graph Convolutional Networks (GCNs) and GraphSAGE for learning representations from the graph data.
   - **Sequence Modeling**: Implements sequence models such as GRUs for capturing temporal dynamics in the data.

### 4. Model Training and Evaluation
   - **Training Pipeline**: Defines a training pipeline for the models, including data loading, model initialization, and optimization.
   - **Evaluation Metrics**: Uses various metrics to evaluate model performance, including accuracy, precision, recall, and F1 score.

### 5. Visualization and Analysis
   - **Data Visualization**: Provides tools for visualizing the dataset and model outputs using matplotlib and other libraries.
   - **Result Analysis**: Analyzes the results of the models to interpret the findings and draw conclusions about epidemic spread.

### 6. Configuration and Documentation
   - **Configurable Parameters**: Allows configuration of various parameters such as batch size, learning rate, and model architecture.
   - **Comprehensive Documentation**: Includes detailed documentation for the code, dataset, and experimental setup.

---

## Directory Structure

```plaintext
|-- .gitignore
|-- .ipynb_checkpoints
|   |-- Foursquare_ny-checkpoint-checkpoint.ipynb
|   |-- Foursquare_ny-checkpoint.ipynb
|   |-- untitled-checkpoint.txt
|-- Foursquare_ny-checkpoint.ipynb
|-- Foursquare_ny.ipynb
|-- README.md
|-- posts-master.zip
|-- untitled.txt
```

---

### Detailed Explanation

#### **Data Handling and Preparation**

- **Foursquare_ny.ipynb**: The main Jupyter notebook for data handling and preparation. This notebook includes code for loading the Foursquare dataset, cleaning it, and preparing it for graph-based analysis.

#### **Graph-Based Analysis**

- **Graph Construction**: Code to convert the dataset into a graph format using libraries like NetworkX.
- **Graph Embedding**: Implementation of graph embedding techniques using PyTorch Geometric and other relevant libraries.

#### **Machine Learning Models**

- **Graph Neural Networks**: Code for implementing Graph Convolutional Networks (GCNs) and GraphSAGE models.
- **Sequence Modeling**: Implementation of GRU-based models for capturing temporal patterns in the data.

#### **Model Training and Evaluation**

- **Training Pipeline**: Scripts and functions to handle the training process, including data loading, model training, and evaluation.
- **Evaluation Metrics**: Functions to calculate and display various evaluation metrics.

#### **Visualization and Analysis**

- **Data Visualization**: Code for visualizing the dataset and model outputs using matplotlib.
- **Result Analysis**: Jupyter notebooks and scripts for analyzing the model results and drawing conclusions.

#### **Configuration and Documentation**

- **Configurable Parameters**: Code to allow easy configuration of various parameters such as batch size, learning rate, and model architecture.
- **Comprehensive Documentation**: Detailed comments and documentation within the code and notebooks to explain the functionality and usage.

---

These features and the structured approach make the project robust and capable of analyzing epidemic networks using the Foursquare dataset, providing valuable insights into the spread of epidemics.
