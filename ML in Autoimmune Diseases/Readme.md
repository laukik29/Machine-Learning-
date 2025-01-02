# Machine Learning in Autoimmune Diseases

This repository focuses on leveraging machine learning to study autoimmune diseases, with specific applications in pediatric inflammatory bowel disease (PIBD) and genetic analysis of autoimmune conditions. The project applies advanced data processing and supervised learning techniques to enhance diagnosis, classification, and understanding of autoimmune disorders.

## Project Highlights

### 1. **Classification of Pediatric Inflammatory Bowel Disease (PIBD)**
- **Objective**: Classify PIBD subtypes—Crohn's Disease (CD), Ulcerative Colitis (UC), and Inflammatory Bowel Disease Unclassified (IBDU).
- **Dataset**: Histological and endoscopic data of 287 patients.
- **Methodology**:
  - Supervised learning using the Random Forest algorithm.
  - Numerical encoding of gastrointestinal abnormalities at 10 specific locations.
- **Results**: Achieved 65% accuracy in predicting PIBD subtypes.
- **Optimizations**:
  - Data preprocessing, feature engineering, and hyperparameter tuning.
  - Ensemble methods to improve generalization.
- **Further Work**: Implementing SVMs and addressing class imbalances.

### 2. **Genetic Approach for Disease Diagnosis**
- **Objective**: Identify key genes associated with autoimmune diseases and develop a robust diagnosis model.
- **Data Collection**: Genetic information from healthy and affected individuals.
- **Analysis**:
  - Statistical evaluation of genes to calculate corrected p-values.
  - Identification of significant genes, such as **STAT1**, **IFI44**, **HLA-DRB1**, and others.
- **Results**:
  - Developed a Random Forest classifier with a prediction accuracy of 73%.
- **Key Insights**:
  - Highlighted critical genetic pathways and their roles in autoimmune diseases.
  - Explored environmental triggers contributing to disease progression.

## Tools and Techniques
- Machine Learning Algorithms: Random Forest, SVM (planned).
- Statistical Analysis: p-value computation and feature importance analysis.
- Metrics: Accuracy, precision, recall, F1-score, and confusion matrix.

## Future Directions
- Extend genetic analysis to larger and more diverse datasets.
- Integrate advanced models like deep learning for higher accuracy.
- Explore cross-population studies to enhance generalizability.

## References
1. [Classification of Pediatric Inflammatory Bowel Disease using Machine Learning](https://doi.org/10.1038/s41598-017-02606-2)
2. [Paediatric inflammatory bowel disease in India: A multicenter study](https://doi.org/10.1097/MEG.0000000000001859)
3. [Inflammatory Bowel Disease: Genetics, Epigenetics, and Pathogenesis](https://doi.org/10.3389/fimmu.2015.00551)

## Repository Structure
- **/data**: Contains training and testing datasets.
- **/code**: Scripts for preprocessing, training, and evaluation.
- **/results**: Model outputs, confusion matrices, and classification reports.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/laukik29/Machine-Learning-
