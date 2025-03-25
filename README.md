# Chronic Kidney Disease Clustering using K-Means  
（使用 K-Means 進行慢性腎病分群）

## 📌 Project Overview / 專案概述  
This project applies **K-Means clustering** to analyze chronic kidney disease (CKD) data. The dataset contains multiple medical indicators, and the goal is to identify different patient groups based on their health conditions.  

本專案利用 **K-Means 分群** 方法，對慢性腎病（CKD）數據進行分析。數據集包含多個醫學指標，目標是根據健康狀況識別不同類型的病患群組。  

---

## ⚙️ Execution Environment / 執行環境  
This project can be run in the following environments:  

本專案可於以下環境執行：  

1. **Google Colab (Recommended) / Google Colab（推薦）**  
   - Open the notebook directly in Colab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/121g9FnufVDYUS8lGxv-avby1hKRYs3J4/view?usp=sharing)  
   - Ensure you upload the dataset before running the notebook.  

   - 在 Colab 中開啟 Notebook：[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/121g9FnufVDYUS8lGxv-avby1hKRYs3J4/view?usp=sharing)  
   - 請先上傳數據集，確保能夠正常運行。  

2. **Local (Python + Jupyter Notebook)**  
   - Install dependencies:  
     ```bash
     pip install -r requirements.txt
     ```
   - Run Jupyter Notebook:  
     ```bash
     jupyter notebook
     ```
   - Open the file `K-Means_ckd.ipynb` and execute the code cells.  

    **本機執行（Python + Jupyter Notebook）**  
     - 安裝所需套件：
       ```bash
       pip install -r requirements.txt
       ```
     - 啟動 Jupyter Notebook：
       ```bash
       jupyter notebook
       ```
     - 開啟 `K-Means_ckd.ipynb` 並執行程式碼。  

---

## 📊 Dataset / 數據集  
The dataset contains medical indicators such as **serum creatinine, blood urea, potassium, anemia, diabetes, and hypertension**. These features are used to cluster patients and assess their health risks.  

數據集包含 **血清肌酐、血尿素、鉀含量、貧血、糖尿病、高血壓** 等醫學指標，這些變數被用來對病人進行分群，並評估健康風險。  

---

## 🔍 Key Features & Analysis / 主要功能與分析  
- **K-Means Clustering**: Identifies patient groups based on key medical indicators.  
- **Risk Score Calculation**: Uses weighted medical variables to assess CKD risk.  
- **Cluster Profiling**: Analyzes the characteristics of each cluster.  
- **Visualization**: PCA plots and statistical summaries.  

- **K-Means 分群**：根據關鍵醫學指標識別不同的病患群組。  
- **風險分數計算**：基於加權醫學變數來評估 CKD 風險。  
- **群組特徵分析**：解析每個群組的健康指標特性。  
- **視覺化分析**：包含 PCA 降維與統計圖表。  

---

## 🚀 How to Run / 如何執行  

### **Option 1: Run on Google Colab / Google Colab 執行（推薦）**  
1. Click the **"Open in Colab"** button above.  
2. Upload the dataset.  
3. Run all the cells in the notebook.  
-
1. 點擊上方 **「Open in Colab」** 按鈕。  
2. 上傳數據集。  
3. 執行 Notebook 內所有程式碼區塊。  

---

### **Option 2: Run Locally / 本機執行**  
1. Clone this repository:  
   ```bash
   git clone https://github.com/YOUR-USERNAME/K-Means-CKD.git
   cd K-Means-CKD
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook and run the file:  
   ```bash
   jupyter notebook
   ```
4. Select `K-Means_ckd.ipynb` and execute the cells.  
-
1. 複製專案倉庫：  
   ```bash
   git clone https://github.com/YOUR-USERNAME/K-Means-CKD.git
   cd K-Means-CKD
   ```
2. 安裝相依套件：  
   ```bash
   pip install -r requirements.txt
   ```
3. 啟動 Jupyter Notebook 並運行：  
   ```bash
   jupyter notebook
   ```
4. 選擇 `K-Means_ckd.ipynb` 並執行程式碼。  

---

## 📈 Results / 分析結果  
The clustering results show that patients can be grouped based on their **blood urea, creatinine levels, potassium levels, and CKD risk scores**. The highest-risk group has significantly elevated creatinine and blood urea levels.  

分群結果顯示，病人可根據 **血尿素、血清肌酐、鉀含量和 CKD 風險分數** 進行分類。風險最高的群組，其血清肌酐和血尿素含量顯著升高。  

Key findings:  
- **Cluster 2** has the highest CKD risk (Mean Risk Score ≈ 48.12).  
- **Cluster 1** has the lowest risk, with very few cases of diabetes or hypertension.  
- CKD patients in **Cluster 2 & Cluster 3** show significantly elevated creatinine and blood urea levels.  

關鍵發現：  
- **Cluster 2** 具有最高的 CKD 風險（平均風險分數 ≈ 48.12）。  
- **Cluster 1** 風險最低，幾乎沒有糖尿病或高血壓病例。  
- **Cluster 2 和 Cluster 3** 的 CKD 患者，血清肌酐和血尿素含量顯著提高。  

---

## 👥 Contributors / 共同協作者  
- @lai5566
- @yusinchenn
- @ziyan9453
---

## 🔗 References / 參考資料  
1. [CKD Dataset Source](https://www.kaggle.com/datasets/mansoordaku/ckdisease)  
2. [K-Means Clustering - Scikit-learn](https://scikit-learn.org/stable/modules/clustering.html#k-means)  
3. [Google Colab Guide](https://colab.research.google.com/)  
