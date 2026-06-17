# ESG — ESG 因子分析與自建選股策略

ESG／永續金融課程作業，分兩部分：

- **ETF 成分股投組分析**：以 **00923 ETF 成分股**（202403）建構等權／市值加權／碳排放加權投組，並用 Fama-French 因子估計 alpha。
- **期末專案：自建 ESG 選股策略**：以女性主管比率、高管基層薪資差異、育嬰留停申請率、身障進用、ROE、是否違反勞基法等社會／治理指標，從**台灣上市公司**篩選並回測投組（2022–2024）。

## 內容
| 檔案 | 說明 |
|------|------|
| `ESG.ipynb` | HW1／HW2：00923 成分股的等權／市值／碳排加權投組與 Fama-French 因子 alpha；Final：自建 ESG 篩選選股策略與回測（`statsmodels`）|

### 相關文件
`113352019_sustainability_announcement.pptx`、`ESG 翻譯.docx`、`永續價值金字塔.docx`、`2024-EFM-Sustainable Portfolio Construction…pdf`（參考論文）

## 資料
資料來源為 TEJ 與公開資料，已隨附於本資料夾（共 ~22 個 csv/xlsx）：五因子+Rf、00923 成分股、上市碳排放、上市日報酬，以及女性比率、薪酬差異、育嬰留停、身障進用、違反勞基法、ROE 等 ESG／社會／治理指標。

`ESG.ipynb` 以相對路徑讀取本資料夾內的資料，直接執行即可。

## 執行
```bash
pip install pandas numpy statsmodels matplotlib openpyxl
```
