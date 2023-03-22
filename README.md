# Coreference-Resolution: a solution

User manual

1. 在 root directory 中新增`.env `檔案，並新增變數 `OPENAI_API_KEY`，值為自己的金鑰。

2. 將要輸入的句子放入 `input.txt`，並注意每個句子以`\n`分隔，以及每個句子需有完整標點符號。

3. 執行`api.py`，輸出的檔案為`output.txt`。

參數 N

- 在`.env`中新增名稱為`N`的變數。

- 若輸入的句子字數大於參數 N，則該行自動跳過。
