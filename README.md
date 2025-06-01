# project_gutenberg
# Project Gutenberg 爬蟲作業

使用 Selenium 自動化瀏覽 Project Gutenberg 中文書籍網站，成功爬取 **312 本書籍**，並將每一本內容儲存為 .txt 檔案。

---

##  專案結構

```
project_gutenberg/
├── project_gutenberg.ipynb  ← 主程式
├── README.md                ← 本說明文件
├── .gitignore               ← 忽略書籍與影片
```

---

##  執行環境

- 執行方式：使用 VS Code 執行 Jupyter Notebook（`.ipynb`）
- 系統：Windows 10
- Python 版本：建議 3.8+
- 瀏覽器：Google Chrome + ChromeDriver

---

##  使用套件與版本

> 以下為我實際使用的套件，版本請以 `pip list` 查詢為主

- selenium
- requests
- regex
- os
- time


安裝方式：
```bash
pip install selenium requests regex
```

---

##  操作影片（執行過程錄影）

 [YouTube 隨意三本內容影片](https://youtu.be/grWqgqv_vjA)
 
 [YouTube 隨意三本內容影片](https://youtu.be/P_sqoHV_-jA)

---


##  學習補充

這份作業透過實作學會了：
- 爬蟲流程設計
- Selenium 元素選取與操作
- 自動化資料抓取與儲存
