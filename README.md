# NLP & Punctuation Restoration Model
> 課程：112-2 AI  
> 組員：周廷威、賴邑城、蔡尚融

## 環境建置
主要用到三個python pacakge:
1. happytransformer
2. csv
3. pandas
   
直接在開發環境的terminal 輸入pip instsall {pacakge_name}就可以了，沒有版本相容性問題

## 執行步驟
完整的執行步驟跟大部分的實驗結果都在main.ipynb，lab03.ipynb有實驗三所用到的六個文本跟比較結果。

main.ipynb包含了從隨機從dataset抽取資料、fine-tune一個選定的預訓練模型並儲存model、生成test dataset的還原結果、評估模型成效、跟實驗三的結果。實驗一跟二所使用到的模型跟所有BNC的資料集存放在下方連結:

https://drive.google.com/drive/folders/1bV1pU8orEibHEdwYmGKCHZi53UtkKcKC?usp=sharing

將解壓縮後的檔案與repo中的ipynb並列在同個層級即可執行

repo中的train.csv, eval.csv是微調google drive中"model"所使用的資料，model.csv存放用"model"還原test.csv中的文本的結果，並跟test.csv比對評估"model"的成效 (結果包含在main.ipynb內)
