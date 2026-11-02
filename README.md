Google Colab 使用教程：MNIST 手寫數字辨識

報告人:黃勝揚 學號11215017

一、期中報告介紹

主要介紹 Google Colab 的基本使用方式，並透過 TensorFlow 建立 MNIST 手寫數字辨識模型，實際體驗深度學習的訓練與預測過程。

Google Colab 是一個雲端 Python 開發環境，不需要在本機安裝完整的 Python 環境，就可以執行程式碼及訓練機器學習模型。

二、實驗目的
學習 Google Colab 的基本操作。
認識 TensorFlow 深度學習框架。
了解 MNIST 手寫數字資料集。
學習建立及訓練神經網路模型。
實際測試模型的數字辨識能力。
三、實驗環境
開發平台：Google Colab
程式語言：Python
深度學習框架：TensorFlow / Keras
資料處理：NumPy
圖片視覺化：Matplotlib
資料集：MNIST
四、MNIST 資料集介紹

MNIST 是常見的手寫數字辨識資料集，內容包含 0 到 9 的手寫數字圖片。

訓練資料：60,000 張
測試資料：10,000 張
圖片大小：28 × 28 像素
分類類別：0～9，共 10 類
五、實驗步驟
1. 匯入相關套件

使用 TensorFlow、NumPy 和 Matplotlib 進行資料處理及模型建立。

2. 載入 MNIST 資料集

透過 Keras 載入 MNIST 訓練資料與測試資料。

3. 資料視覺化

使用 Matplotlib 顯示手寫數字圖片，觀察資料集內容。

4. 資料預處理

將圖片像素值由 0～255 正規化至 0～1。

5. 建立神經網路模型

使用 Keras Sequential 建立模型，包含 Flatten、Dense、Dropout 等網路層。

6. 模型訓練

使用 Adam 優化器進行訓練，並設定訓練回合數為 5。

7. 模型測試

使用測試資料評估模型的 Loss 和 Accuracy。

8. 手寫數字預測

選取測試圖片，讓模型預測圖片中的數字，並比較預測結果與真實標籤。

六、實驗結果

本實驗透過 MNIST 資料集訓練手寫數字辨識模型，並使用測試資料評估模型表現。

實際測試準確率及預測結果以 Colab 執行結果為準。

七、實驗心得

透過本次實驗，我學習到 Google Colab 的基本操作，並了解如何使用 TensorFlow 建立簡單的深度學習模型。

從資料載入、資料預處理、模型建立到模型訓練與測試，讓我更了解機器學習的基本流程，也實際體驗人工智慧如何辨識手寫數字。

八、檔案說明
README.md：專題介紹與實驗說明。
Google_Colab_MNIST.ipynb：完整實驗程式碼。
images/：實驗執行結果及圖片截圖。
九、參考資料
Google Colab：https://colab.research.google.com/
TensorFlow 官方文件：https://www.tensorflow.org/
Keras MNIST：https://keras.io/api/datasets/mnist/
