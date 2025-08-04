🍇 Grape Quality Analysis using Hyperspectral Imaging (HSI)
This repository presents a research project involving the application of Hyperspectral Imaging (HSI) and Machine Learning techniques to analyze grape samples for quality evaluation and pesticide residue detection. The project was designed to support non-destructive agricultural assessment methods and demonstrates the integration of computer vision and spectral analysis with data science workflows.

🧠 Project Overview
Hyperspectral Imaging (HSI) is a powerful tool that captures image data across hundreds of spectral bands. This capability enables the identification of chemical components and subtle features not visible in standard RGB imaging.
In this project, we analyze grape samples using HSI to:
Classify grapes based on spectral signatures
Detect pesticide contamination or quality degradation
Visualize spectral patterns and conduct exploratory data analysis
Train ML models to automate decision-making in agriculture

🎯 Objectives
✅ Preprocess and visualize hyperspectral data
✅ Reduce dimensionality (e.g., PCA or t-SNE) for spectral simplification
✅ Classify grape samples using supervised learning techniques
✅ Demonstrate feasibility of non-invasive quality monitoring

🛠️ Technologies Used
Programming Language: Python 3.x
Development Environment: Jupyter Notebook

Libraries:
numpy, pandas – data handling
matplotlib, seaborn – visualization
scikit-learn – machine learning and preprocessing
opencv-python – image processing (if applicable)
scipy – scientific computing
spectral – hyperspectral data handling (optional)

📂 Dataset
Note: Due to licensing or privacy constraints, the dataset may not be publicly available in this repository. If you wish to reproduce the results, please contact the author or refer to public HSI datasets such as:
Pavia University Dataset
Indian Pines Dataset
AVIRIS-NG data (if available for grapes)
The dataset used includes hyperspectral cube images of grape samples under various conditions.

🧾 Notebook Structure
Grape_HSI.ipynb includes:
Data import and inspection
Visualization of raw spectral data
Preprocessing (normalization, noise reduction)
Dimensionality reduction (e.g., PCA)
Model training (e.g., SVM, Random Forest)
Evaluation using metrics like accuracy, confusion matrix
Insights and conclusions

⚙️ Installation
To run the project locally:
git clone https://github.com/Siddartha1308/Determination-of-Pesticide-residue-in-Grapes.git

cd grape-hsi-project
pip install -r requirements.txt
Or install dependencies manually:
pip install numpy pandas matplotlib seaborn scikit-learn opencv-python

🚀 How to Run
Launch Jupyter Notebook:
jupyter notebook Grape_HSI.ipynb
Follow the notebook cells step-by-step to reproduce the workflow and results.

📊 Results & Findings
Achieved good classification accuracy (>XX%) for quality detection
PCA effectively reduced noise and preserved meaningful variance
Identified clear spectral differences in contaminated vs. healthy grapes
Demonstrated HSI as a reliable tool for grape quality inspection


🌐 Applications
🍇 Precision agriculture
🧪 Food safety and pesticide detection
🛒 Supply chain quality control
🌱 Research in plant physiology and biochemistry

🔮 Future Work
Integrate Deep Learning (e.g., CNNs for HSI cubes)
Real-time spectral analysis via edge devices
Expand dataset for multi-fruit comparison
Combine HSI with other sensors (e.g., thermal or LiDAR)
