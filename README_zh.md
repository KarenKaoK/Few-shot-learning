### 專案簡介

這個專案主要使用 CUB 資料集進行 Few-Shot Learning 的範例 notebook。實作是以 `easy-few-shot-learning` 為基礎，示範如何先進行 backbone 的傳統監督式訓練，再用 episodic 的方式做 few-shot 驗證與測試。

### 專案內容

- [Few_shot_sample_code.ipynb](/Users/ren/Desktop/karen/git_karen/Few-shot-learning/Few_shot_sample_code.ipynb)：CUB few-shot learning 的完整範例 notebook


### 實作重點

這份 notebook 示範了以下流程：

- 準備 CUB 資料集
- 使用 classical training 訓練特徵抽取 backbone
- 透過 Prototypical Networks 進行 few-shot 評估
- 實作 `3-way 5-shot` 的任務設定
- 視覺化 support set 與 query set 的預測結果

### 環境需求

建議使用以下環境執行：

- Python 3
- PyTorch
- `easyfsl`
- `gdown`
- Google Colab 或本機 GPU 環境

參考來源：

- `easy-few-shot-learning`: https://github.com/sicara/easy-few-shot-learning

### 資料集補充說明

notebook 內使用的是 CUB 資料集，且有提到在 Google Colab 上可能會遇到大量資料下載受限的情況。因此若自動下載失敗，可能需要先手動上傳壓縮檔，再進行解壓與後續處理。

### 使用方式

1. 使用 Google Colab 或本機 Jupyter 開啟 [Few_shot_sample_code.ipynb](/Users/ren/Desktop/karen/git_karen/Few-shot-learning/Few_shot_sample_code.ipynb)。
2. 安裝相依套件，例如 `easyfsl` 與 `gdown`。
3. 準備 CUB 資料集。
4. 依序執行訓練、驗證與測試的程式區塊。
5. 查看最後的視覺化結果，確認 support/query sample 與模型預測表現。

### 系列文章

這個專案對應到 few-shot learning 的系列筆記連結：

-  [淺談Few-Shot Learning：(2): 實作CUB 資料集 Few shot learning](https://karenkaods.medium.com/%E6%B7%BA%E8%AB%87few-shot-learning-2-%E5%AF%A6%E4%BD%9Ccub-%E8%B3%87%E6%96%99%E9%9B%86-few-shot-learning-902070fcfda3)
- [淺談Few-Shot Learning：(1): 初步認識](https://karenkaods.medium.com/%E6%B7%BA%E8%AB%87few-shot-learning-1-%E5%88%9D%E6%AD%A5%E8%AA%8D%E8%AD%98-3cb541a866e5)
