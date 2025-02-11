# .github 文件夾 - 公開配置指南 🖖

歡迎使用 **時光機科技** 的公開 GitHub 配置文件！🎉  
此文件位於存儲庫的 `.github` 目錄下，主要用來定義與**外部協作**有關的公共模板與工作流程。這些文件會顯示在所有對本專案有存取權的人面前（例如：Issue 模板、PR 模板、GitHub Actions 工作流程等）。

- 可視為是對外的*公告*，又或是有在協助維護開源專案的聯絡指南

---

## 一、用途 🚚

- **Issue 模板**：幫助同仁在提出 Bug 或功能請求時，依據統一格式填寫必要資訊。
- **Pull Request (PR) 模板**：提供提交變更時的標準格式，確保修改內容描述清楚，便於審查。
- **GitHub Actions 工作流程**：定義 CI/CD 流程，確保自動化測試與部署正常運作。
- **CODEOWNERS**：指定特定檔案或目錄的負責審查人員，方便自動分配 PR 審查任務。
- **FUNDING 檔案**（若有）：顯示組織的贊助資訊與支持方式。

---

## 二、如何修改 🧵

1. **Clone 專案**  
   請先從 GitHub 組織中 clone 您的專案：
 ```bash
 git clone https://github.com/TiMa-Technology/your-repo.git
 cd your-repo
 ```

2. **建立新分支**
   請不要直接在主分支修改，請建立新分支：
```bash
git checkout -b update-public-config
```

3. **修改檔案**
在 .github 目錄中，您可以修改或新增檔案：
    - 根據需要修改現有內容或新增新的範本，請遵循團隊內部的格式與標準。
  
4. **Commit 與 Push**
提交修改並推送新分支：

```bash
git add .github
git commit -m "feat: update public GitHub configuration files"
git push -u origin update-public-config
```

5. **發出 Pull Request (PR)**
登入 GitHub，前往專案頁面後點選剛推送的分支旁的 `Compare & pull request` 按鈕。填寫標題與詳細說明，描述您做了哪些修改，然後提交 PR。

## 三、可新增的檔案
在 .github 目錄下，您可以依需求新增或更新以下檔案：

1. ISSUE_TEMPLATE/：各種 Issue 模板
2. PULL_REQUEST_TEMPLATE.md：PR 模板
3. workflows/：自動化工作流程配置檔（如 CI/CD 流程）
4. CODEOWNERS：管理檔案審查人員
5. 其他與公共協作相關的設定檔案
   
## 四、常見問題
Q：為什麼需要在 .github 目錄中新增這些檔案？

A：這些檔案有助於統一問題追蹤、代碼審查與自動化流程，提升團隊協作效率並確保專案品質。

Q：如何知道修改是否通過 CI 測試？

A：提交 PR 後，系統會自動觸發工作流程，您可以在 PR 頁面查看 CI 測試狀態。

若有任何疑問或建議，請隨時與我們分享！🚀

版本 1.0 – 更新日期：2025-02-11
