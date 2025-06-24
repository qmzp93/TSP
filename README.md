# Vertex Cover Solver using Grover's Algorithm

本專案使用 **Grover’s Algorithm** 解決組合優化中的 **Vertex Cover Problem (VCP)**，以 **Qiskit 1.x** 與 **Google Colab** 為執行平台，支援多圖測試、量子電路可視化與測量結果直方圖。

---

## 📌 專案目標

- 實作 Grover’s Algorithm 搜尋大小為 `k` 的 vertex cover
- 套用於 4 張不同結構的圖形進行測試與統計分析
- 可視化合法解與非解的分佈、成功率與直方圖輸出

---

## 🧠 Vertex Cover 問題定義

對於一張無向圖 \( G = (V, E) \)，找出一個頂點子集合 \( C \subseteq V \)，使得每一條邊 \( (u,v) \in E \) 至少有一端點在 \( C \) 中。本專案針對固定大小 \( |C| = k \) 的情況使用 Grover 進行搜尋。

---

## 🧰 使用技術

- Python 3.11
- Qiskit 1.x（含 qiskit-aer）
- Google Colab（或任意 Jupyter 環境）
- matplotlib（繪製直方圖）

---

## 📦 安裝方式

請先於 Colab 或本地安裝必要套件：

```bash
pip install qiskit qiskit-aer matplotlib


也可以使用https://www.onlinegdb.com/online_c++_compiler 這個網站進行編譯

程式碼位於main.cpp中

報告詳細內容都在112502036.pdf中
