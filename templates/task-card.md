# 交辦卡片範本

把以下內容貼入 Trello 卡片 Description，替換所有範例與空欄；每張卡片只描述一個獨立工作。

```text
目標：
<要解決的具體問題與預期行為>

Working Directory:
<本機專案的絕對路徑，例如 D:\Projects\example-app>

Repository:
<儲存庫網址；如適用>

背景／重現步驟：
1. ...
2. ...

允許修改範圍：
- ...

驗收條件：
- ...

驗收指令（在上述工作目錄執行）：
<專案實際可用的指令>

相關附件／連結：
- <沒有則註明無>

交付方式：
<只保留本機修改，或明確授權 commit／push／建立 PR 等動作>
```

另外在 Trello 建立 Checklist，逐項列出驗收條件。避免只寫「修好它」，也不要在卡片貼憑證。

## 範例：補上開發文件

```text
目標：
在 README 的開發環境段落補上專案既有的啟動與測試方式。

Working Directory:
D:\Projects\example-app

背景：
新同事無法從目前 README 找到如何啟動開發環境。

允許修改範圍：
- README.md

驗收條件：
- 指令與 package.json 的既有 scripts 一致。
- 包含安裝、啟動、測試步驟。
- README 內部連結可解析。

驗收指令：
以唯讀方式核對 package.json 與 README；這張文件卡片不需要啟動伺服器。

相關附件／連結：
- 無

交付方式：
只保留本機修改，不 commit、不 push。
```
