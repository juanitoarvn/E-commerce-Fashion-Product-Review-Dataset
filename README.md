# E-commerce-Fashion-Product-Review-Dataset

## Overview
This dataset contains customer reviews from **Tokopedia’s fashion category**, collected between **January 2024 and March 2025**. Reviews were gathered using **Selenium** and **BeautifulSoup**, resulting in a raw dataset of **19,915 entries** consisting of both text and images.

## Data Processing
- **Initial Dataset**: 19,915 entries (text + images).
- **Cleaning Step**: Records without valid textual reviews were removed, leaving **15,470 entries**.
- **Class Imbalance Handling**: The dataset was highly imbalanced due to the dominance of 5-star ratings. To address this, the data was balanced for sentiment classification tasks.
- **Final Dataset**: After balancing, the dataset contains **5,227 reviews**.

## Dataset Composition
- **Text + Images**: 1,698 entries include both textual reviews and images.  
- **Text Only**: The remaining reviews consist of textual reviews without images.  
- **Balanced Labels**: Final dataset ensures a fair distribution of sentiment classes, making it suitable for **sentiment analysis** tasks.  

As shown in *Figure 2* (not included here), the balancing step significantly improved label distribution, allowing for more reliable training and evaluation of sentiment analysis models.

## Applications
This dataset can be used for:
- Text-based sentiment analysis.
- Image-based sentiment classification.
- Multimodal sentiment analysis (fusion of text and image features).
- Research on handling class imbalance in customer review datasets.

---

📌 **Note**: Please cite appropriately if you use this dataset for academic or research purposes.
