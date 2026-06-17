# ESG — 碳排放與因子模型分析

ESG／永續金融課程作業：分析**碳排放**與**Fama-French 五因子**對股票報酬的關係，標的為 00923（ESG ETF）成分股。

## 內容
| 檔案 | 說明 |
|------|------|
| `ESG.ipynb` | HW1 / HW2 / Final：讀取五因子+Rf、00923 成分股、碳排放、日報酬，以 `statsmodels` 做因子迴歸與績效分析 |

### 相關文件
`113352019_sustainability_announcement.pptx`、`ESG 翻譯.docx`、`永續價值金字塔.docx`、`2024-EFM-Sustainable Portfolio Construction…pdf`（參考論文）

## 資料
資料來源為 TEJ 與公開資料，已隨附於本資料夾（共 ~22 個 csv/xlsx）：五因子+Rf、00923 成分股、上市碳排放、上市日報酬、薪酬、勞基法違規、身障進用、育嬰假等 ESG 與財務指標。

`ESG.ipynb` 以相對路徑讀取本資料夾內的資料，直接執行即可。

## 執行
```bash
pip install pandas numpy statsmodels matplotlib openpyxl
```
