# YOLO-train
主動脈瓣偵測的訓練程式
# Aortic Valve Detection Project (NKUST Final Report)

本專案為 NKUST 機器學習期末報告之原始程式碼。專案使用 Ultralytics YOLO 框架進行主動脈瓣 (Aortic Valve) 的物件偵測。程式碼整合了資料清洗、模型訓練、驗證以及競賽格式的結果輸出。

## 1. 執行環境與安裝 (Environment & Installation)

本程式建議於 **Google Colab (GPU)** 或具備 NVIDIA GPU 的本機環境執行。

### 系統需求
* **Python**: 3.8+
* **GPU**: 建議 NVIDIA T4/V100/A100 (需支援 CUDA 12.1)
* **Framework**: PyTorch, Ultralytics

### 安裝指令
請執行以下指令安裝必要依賴：

```bash
# 安裝 PyTorch (CUDA 13.0 版本)
pip install torch torchvision torchaudio --index-url [https://download.pytorch.org/whl/cu130](https://download.pytorch.org/whl/cu130)

# 安裝 YOLO 框架
pip install ultralytics
