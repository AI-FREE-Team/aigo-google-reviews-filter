# aigo-google-reviews-filter

## Preface 前言

現行商家網路評價資訊多以影音、圖文、評分等三種方式呈現，但前兩者主要以質化描述進行商家評比，缺乏可量化數據供使用者分析；評分則以一到五星級進行評分，但在五個類別的評分尺度中，不同使用者會依據當下的情緒、過去的用餐經驗而有不同主觀的分數，導致分數與評論內容不相符的狀況產生。


同時在社群上，也有不肖的商家、消費者，透過灌水的方式惡意操弄評分系統，除了聘雇網軍大量濫充正向評論，也經常能夠看到網民集結，蓄意發動攻訐店家進行負評；本專題透過 AI 自然語言技術，建立繁體中文評論 word-embedding，同時設計新的評分機制提供未來消費者做參考依據，以獲得公正、客觀的市場評價。


## Data Source 資料來源

Google 商家評論 (467,250 筆)、 Foodpanda 評論(40,663 筆)


## Data Cleaning Process 資料清理流程

![image](https://raw.githubusercontent.com/AI-FREE-Team/aigo-google-reviews-filter/main/images/1.png)

## Data Exploration 資料探索

![image](https://raw.githubusercontent.com/AI-FREE-Team/aigo-google-reviews-filter/main/images/2.png)

## Model Usage 模型使用

Word-Embedding + LSTM

## Inference Example 

![image](https://raw.githubusercontent.com/AI-FREE-Team/aigo-google-reviews-filter/main/images/%E6%A8%A1%E5%9E%8B%E6%8E%A8%E8%AB%96%E4%BE%8B%E5%9C%96.png)
