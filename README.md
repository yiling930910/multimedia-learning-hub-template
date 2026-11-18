# 多媒體學習站｜期末專題範本

這個範本協助各組建立公開的多媒體學習網站。請依老師分配的主題，將範本中的「待填」替換成自行整理、查證並標明來源的內容。本頁的大綱只是示意，**不是完成的報告**；詳細技術範圍與規則以老師的期末專題說明及後續公告為準。

## 一、期末成果要長什麼樣子？

每組 5–6 人，建立一個公開的學習網站。首頁應讓讀者找到小組主題、學習目標、六章學習地圖與組員姓名；每人負責一個技術頁面。五人組可將第六章與第五章合併，或明確分配第六章內容。

以下以「多媒體壓縮」為例，只展示網站結構：

```text
首頁：主題介紹、學習目標、組員及學習地圖
├── 第 1 章 壓縮基礎                    學生 A
├── 第 2 章 影像壓縮技術                學生 B
├── 第 3 章 影片壓縮技術                學生 C
├── 第 4 章 音訊壓縮技術                學生 D
├── 第 5 章 壓縮技術比較                學生 E
├── 第 6 章 應用與新發展                學生 F（或由五人組分配）
├── 資源庫：全組引用資料索引
└── 小組貢獻：分工、圖表、資料選擇、編輯及同儕審查
```

上面是示範主題，各組應使用老師指定的主題與章節。各頁要能讓讀者在沒有聽報告的情況下理解，並透過有意義的連結互相串接。

### 個人技術頁面大綱（每位學生一頁）

1. **頁面標題與作者**：章節名稱、姓名與學號。
2. **核心概念**：用自己的話解釋原理、重要術語及適用情境。
3. **自製圖**：至少一張概念圖、流程圖或附註說明的圖；註明使用的素材來源。
4. **比較或結構化摘要**：至少一個有資料來源的比較表或技術摘要。
5. **實際應用**：至少兩個有引用資料支持的應用或案例。
6. **延伸閱讀**：至少五項可信資源；每項寫明標題、作者或組織、類型與年份（如有）、有效 DOI／網址、支持的具體概念與推薦閱讀的原因。至少一項為學術論文、技術標準或同等權威技術資料。
7. **與其他章節的關係**：至少兩個連至組員頁面的內文連結，並說明概念關係；僅放選單連結不算。
8. **學習反思**：主要心得、一項限制或常見誤解，以及一項經查證的主張與支持來源。
9. **AI and Source Use**：簡述使用哪些 AI 工具及用途；核對並引用可信來源。未使用 AI 也請說明。

每頁約 **400–600 字**，包括約 **100–150 字**的反思；這是建議而非嚴格限制。不得捏造資料、引用或比較結果；引用圖像及其他非原創內容須註明出處。學生須能在個人問答中解釋內容和來源。無須寫程式、訓練模型或做實驗。

### 範本檔案對照

| 檔案 | 內容 |
| --- | --- |
| `index.html` | 首頁與六章學習地圖 |
| `section-1.html` 至 `section-6.html` | 六份個人頁面範本 |
| `resources.html` | 小組資源庫；每人頁面仍需各自的資源附註 |
| `contributions.html` | 小組分工與貢獻 |
| `requirements.html` | 老師要求摘要 |
| `github-guide.html` | GitHub 使用教學 |
| `style.css` | 網站外觀 |

## 二、建立小組的 GitHub repository

1. 註冊或登入 [GitHub](https://github.com/)。
2. 開啟助教提供的範本 repository。若看到 **Use this template**，點它並選 **Create a new repository**。
3. 選擇要放在哪個帳號、輸入小組 repository 名稱（例如 `multimedia-team-01`），選 **Public**，按 **Create repository**。每組建立一份。
4. 如果沒有看到 **Use this template**，可向助教確認是否已開啟範本功能；或點 **Code → Download ZIP** 下載並解壓縮，在自己的 GitHub 建立公開 repository 後，選 **Add file → Upload files**，上傳資料夾「裡面」的所有檔案並 commit。確認 `index.html` 位於 repository 最外層。
5. 小組擁有者可在自己 repository 的 **Settings → Collaborators** 邀請組員；組員需接受邀請。

## 三、上傳與修改內容

### 方法 A：直接在 GitHub 網頁編輯

1. 在小組 repository 點開要修改的檔案，例如 `index.html` 或 `section-1.html`。
2. 點右上角鉛筆圖示，修改標籤之間的文字；請保留 HTML 標籤與檔案名稱。各組員分別編輯自己的章節。
3. 點 **Commit changes**，輸入簡短說明（例如 `Update section 1`），再確認提交。Commit 是一次有紀錄的修改。
4. 上傳圖片時，選 **Add file → Upload files**，並在網頁中使用正確的檔案路徑及圖片說明。請勿上傳密碼或其他不應公開的資料。
5. 繼續修改時重複以上步驟；先和組員協調，避免同時覆蓋同一段內容。

### 方法 B：使用本機 Git（進階）

先從自己小組的 repository 複製 HTTPS 網址，在終端機輸入：

```bash
git clone <小組-repository-網址>
cd <repository-資料夾名稱>
```

修改檔案後，執行：

```bash
git pull
git add .
git commit -m "Update project content"
git push
```

`<...>` 要換成實際網址與資料夾名稱，輸入時不要保留尖括號。GitHub 可能要求驗證身分；若遇到衝突，先與組員確認內容再解決。

## 四、發布 GitHub Pages

1. 到**自己小組**的 repository，選 **Settings → Pages**。
2. 在 **Build and deployment**，將 Source 設為 **Deploy from a branch**。
3. 選擇 `main` 分支及 `/(root)`，按 **Save**。
4. 等待部署完成，重新整理 Pages 設定頁，開啟頁面顯示的網址。通常格式為 `https://帳號.github.io/repository名稱/`，但以設定頁實際顯示的網址為準。
5. 每次更新並 commit 到發布分支後，等待重新部署，再檢查內容。若沒有網站，確認 repository 可使用 Pages、分支與資料夾正確、根目錄有 `index.html`，並查看 **Actions** 的部署狀態。
6. 用無痕視窗測試，確定老師不需登入或申請權限即可瀏覽；逐頁檢查圖片、引用與連結。

官方說明：[從範本建立 repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template)｜[設定 GitHub Pages 發布來源](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)。

## 五、最後繳交

- [ ] 首頁、個人頁面、資源庫及分工紀錄都已完成，範本提示已替換。
- [ ] 各頁資源附註、圖表來源、兩個案例、兩個內部連結、反思及 AI 使用聲明均已檢查。
- [ ] 網站公開且無痕視窗可開啟，連結與圖片正常。
- [ ] 每位學生能解釋自己的章節，並用引用資料支持技術主張。
- [ ] 一位代表透過課程平台繳交**網站 URL**，並附組別、專題名稱、組員姓名／學號及使用平台。無須另交 PDF 報告或 GitHub repository。

**繳交與報告日期：待老師公告。**老師原始說明標示總期程 5 週，但只列第 1–4 週里程碑，請依後續公告辦理。
