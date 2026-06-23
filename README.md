# ESG — ESG 因子分析與自建選股策略

ESG／永續金融課程作業，分兩部分：

- **ETF 成分股投組分析**：以 **00923 ETF 成分股**（202403）建構等權／市值加權／碳排放加權投組，並用 Fama-French 因子估計 alpha。
- **期末專案：自建 ESG 選股策略**：從**台灣上市公司**，以女性主管比率(≥40%)、高管基層薪資差異(≤6.5倍)、育嬰留停申請率(≥28%)、身障進用不足人數(≤2)、四季 ROE 皆 >0 篩選，再取市值前 150 大，回測投組（2022–2024）。

## 結構
```text
ESG.ipynb          主程式（HW1／HW2 + 期末專案）
data/              輸入資料（~22 個 csv/xlsx，TEJ 與公開資料）
docs/              報告與參考文件
requirements.txt
```

## 內容
| 檔案／資料夾 | 說明 |
|------|------|
| `ESG.ipynb` | HW1／HW2：00923 成分股的等權／市值／碳排加權投組與 Fama-French 因子 alpha；Final：自建 ESG 篩選選股策略與回測（`statsmodels`）|
| `data/` | 輸入資料：五因子+Rf、00923 成分股、上市碳排放、上市日報酬，以及女性比率、薪酬差異、育嬰留停、身障進用、違反勞基法、ROE 等 ESG／社會／治理指標 |
| `docs/` | 報告與參考文件：`sustainability_announcement.pptx`、`ESG 翻譯.docx`、`永續價值金字塔.docx`（第三方參考論文因版權未隨附）|

## 執行
`ESG.ipynb` 以相對路徑讀取 `data/` 內資料，直接執行即可。
```bash
pip install pandas numpy statsmodels matplotlib openpyxl
```
