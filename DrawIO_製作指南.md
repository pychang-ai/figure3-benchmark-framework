# Draw.io 製作指南 - Figure 3 Benchmark Framework

## 🎨 快速製作步驟

### 1. 開啟 Draw.io
- 前往 https://app.diagrams.net/
- 選擇 "Create New Diagram"
- 選擇 "Blank Diagram"

### 2. 設定畫布
- File → Page Setup
- Format: Custom
- Width: 1920px
- Height: 1080px
- 或選擇 A4 Landscape

### 3. 建立基本形狀

#### 步驟流程：
1. **拖拉 Rounded Rectangle** (圓角矩形)
2. **設定顏色和大小**
3. **添加文字**
4. **複製並修改**
5. **用箭頭連接**

### 4. 顏色設定

```
Stage 1-2 (藍色): #D6EAF8
Stage 3 (橙色): #FDEBD0
Stage 4 (綠色): #D5F5E3
Stage 5 (紫色): #E8DAEF
Stage 6 (深灰): #2C3E50 (白色文字)
```

### 5. 文字內容

#### Stage 1:
```
Data Collection & Description

5 Taiwanese Ports · 2001–2026 · 301 months/port

Kaohsiung · Keelung · Taipei · Taichung · Anping
```

#### Stage 2:
```
Experimental Setup (NeuralForecast)

Train/Test split (last 12 months) · h=12 · input_size=24

max_steps=1000 · Standard scaling · RTX 4060 Ti
```

#### Stage 3:
```
10 Deep Learning Models × 5 Architectural Families

子框架：
- Basis Expansion: N-BEATS · N-HiTS
- Transformer: PatchTST · TFT
- MLP/Linear: DLinear · TiDE
- CNN: TCN · BiTCN · TimesNet
- RNN: LSTM
```

#### Stage 4:
```
Evaluation Metrics

MAE · RMSE · MAPE · SMAPE · R²
```

#### Stage 5:
```
Three-Tier Statistical Comparison Framework

Tier 1: Global - Friedman Test + Nemenyi Post-hoc
Tier 2: Pairwise - Diebold–Mariano + Harvey Correction  
Tier 3: Set-based - Model Confidence Set (MCS)

問題標籤：
- Are models different?
- Which pairs differ?
- Best subset?
```

#### Stage 6:
```
Results

Model Rankings · Port-Specific Guidelines · Best Model Set
```

## 🔧 製作技巧

1. **複製形狀**: Ctrl+C, Ctrl+V
2. **對齊**: 選擇多個物件 → Arrange → Align
3. **群組**: 選擇多個物件 → Ctrl+G
4. **箭頭**: 從 Arrows 類別拖拉
5. **顏色**: 右側 Style 面板設定

## 💾 儲存格式

- .drawio (可再編輯)
- .png (圖片)
- .pdf (向量)
- .svg (網頁用)

## 📤 匯出設定

- Resolution: 300 DPI
- Background: Transparent or White
- Border: 10px