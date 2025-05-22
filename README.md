# DataScience-Environment-Setup
## 環境設置紀錄
此倉庫用於紀錄我的 Python 資料科學環境設置步驟，確保未來可快速回復開發環境。
### 安裝 Anaconda
- 從 [Anaconda 官方網站](https://www.anaconda.com/) 下載並安裝最新版 Anaconda。
- 在 **Anaconda Prompt** 輸入：
  ```bash
  conda --version
    # 若成功顯示 conda x.x.x，代表安裝完成 ✅
  ```
### 設定 Jupyter Notebook
- 在 Anaconda Navigator 內找到 Jupyter Notebook，點選「Launch」啟動。
- 在 Notebook 內測試：
  ```python
  print("Hello Data Science!")
    # 若正確顯示 "Hello Data Science!"，則設置成功 ✅
  ```
### 安裝 Visual Studio Code 並配置 Python 開發環境
- 從 [Visual Studio Code 官方網站](https://code.visualstudio.com/) 下載並安裝。
- 在 Extensions ( 快捷鍵 ```Ctrl + Shift + X``` ) 搜尋 Python，並安裝 Python Extension。
- 建立 ```test.py``` 並輸入：
  ```python
  print("VS Code 設置成功!")
    # 執行程式碼，確認環境設置成功 ✅
  ```
