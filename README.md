# taiwan-events-runner

「寄道日和・台灣」的排程執行器。這個 repo 只放 GitHub Actions workflow：
帶存取權杖取出私有 repo 的程式、跑資料管線、把結果推回去。

- 程式與資料不在這裡。
- 公開紀錄只印統計數字，完整執行紀錄寫在私有 repo 的 `run.log`。
- 資料管線對外連線時的 User-Agent 以本 repo 作為聯絡網址；有問題請開 issue。
