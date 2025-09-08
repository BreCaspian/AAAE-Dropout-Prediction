# Attention-Augmented Autoencoder for Robust Student Dropout Prediction

This repository contains the implementation and resources for the paper "Attention-Augmented Autoencoder for Robust Student Dropout Prediction".

## 🌟 Overview

This project presents a novel approach to student dropout prediction using an attention-augmented autoencoder architecture. The model combines the power of autoencoders for feature learning with attention mechanisms to focus on the most relevant student characteristics for dropout prediction.

**Keywords**: Student Dropout Prediction, Attention Mechanism, Autoencoder, Educational Data Mining, Deep Learning

---

## 🏛️ Repository Structure

```
AAAE-Dropout-Prediction/
│
├── LICENSE              # 📜 开源许可证 (MIT License)
├── README.md            # 🚀 仓库主页 (You are here!)
├── requirements.txt     # 📦 Python 依赖包
├── .gitignore           # 🙈 Git 忽略规则
│
├── Codebase/            # 💻 核心源代码 (Core Source Code)
│   └── Release.ipynb    #    - 包含模型定义、训练和评估全部流程的 Jupyter Notebook
│
├── Database/            # 💾 数据集 (Dataset)
│   ├── Processed/       #    - 存储预处理后 (如SMOTE、标准化) 的数据
│   └── RawData/         #    - 存放原始 .csv 数据集
│
└── Paper/               # 📄 论文与文档 (Paper & Documentation)
    ├── paper.pdf        #    - "Attention-Augmented Autoencoder" 研究论文
    └── Figure/          #    - 论文或报告中使用的图表
```

---

## 🚀 Getting Started

Follow these steps to set up the project and run the model.

### **1. Setup**

First, clone the repository and install the required dependencies.

Bash

```
# Clone the repository
git clone https://github.com/BreCaspian/AAAE-Dropout-Prediction.git
cd 

# Install dependencies (including Jupyter)
pip install -r requirements.txt
```

### **2. Data Preparation**

Place your raw student dataset (`.csv` file) inside the **`Database/RawData/`** directory. The Jupyter Notebook is configured to load data from this location.

### **3. Running the Model**

All code for data processing, model training, and evaluation is contained in a single Jupyter Notebook.

1. Launch Jupyter Lab or Jupyter Notebook from your terminal:

   Bash

   ```
   jupyter notebook
   ```

2. In your browser, navigate to `Codebase/` and open **`Release.ipynb`**.

3. Execute the cells sequentially from top to bottom to reproduce the entire workflow and results.

------

## 📊 Model Architecture

<p align="center">
  <img src="Paper/Figure/AAE.png" alt="AAE Architecture" width="75%">
  <br>
  <em>Figure 1. Overall architecture of the Autoencoder (AAE)</em>
</p>

<p align="center">
  <img src="Paper/Figure/Attention.png" alt="Attention Mechanism" width="75%">
  <br>
  <em>Figure 2. Attention mechanism integrated into the autoencoder</em>
</p>


## 📈 Results

**TABLE I**  
*Performance comparison of all experimental models, with the average recall, precision, and F1 scores calculated as the arithmetic mean of values for classes 0 and 1.*

| Model                          | Accuracy | Avg Recall | Avg Precision | Avg F1 Score |
|--------------------------------|----------|------------|---------------|--------------|
| Attention-Augmented Autoencoder | 98.33%   | 0.99       | 0.97          | 0.98         |
| Autoencoder                     | 96.67%   | 0.96       | 0.96          | 0.96         |
| Neural Network                  | 95.00%   | 0.97       | 0.91          | 0.94         |
| Decision Tree                   | 93.33%   | 0.89       | 0.93          | 0.91         |
| Logistic Regression             | 93.33%   | 0.91       | 0.91          | 0.91         |
| Support Vector Machine          | 93.33%   | 0.91       | 0.91          | 0.91         |
| Naive Bayes                     | 91.67%   | 0.85       | 0.92          | 0.88         |
| Random Forest                   | 91.67%   | 0.88       | 0.90          | 0.88         |
| MLP                             | 90.00%   | 0.86       | 0.86          | 0.86         |
| TabNet                          | 90.00%   | 0.86       | 0.86          | 0.86         |




---

## 📄 Citation

If you use this code or find our work helpful, please cite:

```bibtex
@article{paper_2024,
  title={Attention-Augmented Autoencoder for Robust Student Dropout Prediction},
  author={Name and Co-authors},
  journal={Journal Name},
  year={2025},
  volume={XX},
  pages={XXX-XXX}
}
```

## 📝 License

This project is licensed under the MIT License - see the [MIT LICENSE](LICENSE) file for details.

## 🤝 Contact

This project is maintained by:

- **Author** – yaoyuzhuo6@gmail.com  
- **Author** – yansihan6636@gmail.com
- **Author** – 2264248122@qq.com

For questions, feedback, or collaboration inquiries, feel free to reach out.

