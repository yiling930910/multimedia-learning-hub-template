# Multimedia Learning Hub: Final Group Project
# 多媒體學習網站：期末小組專題

This guide explains what your group website should contain and how to publish it with GitHub Pages. The example below is an outline, not a completed report. Follow the instructor's original instructions and any later announcements for the assigned topic and detailed coverage.

本說明介紹小組網站應包含的內容，以及如何使用 GitHub Pages 發布。下方範例只是大綱，不是完整報告。題目分配與詳細技術範圍請依老師的原始說明及後續公告為準。

## 1. Project overview｜專題概述

- Work in groups of **5–6**. Build a public educational website about your assigned multimedia technology theme. No programming, model training, or experiment is required by the project instructions.
- **5–6 人一組**，以指定的多媒體技術主題製作公開的教育網站。依專題說明，不強制撰寫程式、訓練模型或做實驗。
- Each student owns one technical page. A five-person group may combine Sections 5 and 6 or explicitly distribute Section 6 among members.
- 每人負責一個技術頁面。五人組可合併第 5、6 章，或明確分配第 6 章的內容。
- Explain concepts in your own words, verify technical claims, credit sources, and prepare to answer questions about your page.
- 用自己的話解釋概念、查證技術主張、標明資料來源，並準備回答個人頁面的相關問題。

## 2. What should the finished website look like?｜完成網站應有什麼？

The following is an **outline example** using Multimedia Compression. Replace the section titles with those for your assigned topic.

以下以「多媒體壓縮」示範**網站大綱**；請依實際分配的主題更換章節名稱。

```text
Home / 首頁
├── Topic, learning objectives, members, navigation / 主題、學習目標、成員與導覽
├── 1. Compression Fundamentals / 壓縮基礎 — Student A
├── 2. Image Compression / 影像壓縮 — Student B
├── 3. Video Compression / 影片壓縮 — Student C
├── 4. Audio Compression / 音訊壓縮 — Student D
├── 5. Comparison of Compression Technologies / 壓縮技術比較 — Student E
├── 6. Applications and Emerging Developments / 應用與新發展 — Student F*
├── Resource library / 資源庫
└── Team contributions / 小組貢獻紀錄
```

\* A five-person group may combine Sections 5 and 6 or explicitly distribute Section 6. / 五人組可合併第 5、6 章，或明確分配第 6 章內容。

### Individual page outline｜每人技術頁面大綱

Each individual page should contain / 每個人的頁面應包含：

1. **Title and ownership / 標題與負責人** — Section title, student name and ID. / 章節名稱、姓名與學號。
2. **Original explanation / 原創說明** — Explain the key concepts and how they relate. / 用自己的話解釋核心概念及其關係。
3. **Student-created illustration / 自製圖** — At least one concept diagram, process chart, or annotated illustration; credit any source material used. / 至少一張概念圖、流程圖或註解圖，並註明使用素材的來源。
4. **Structured synthesis / 結構化整理** — At least one well-sourced comparison table or technical summary. / 至少一個有來源支持的比較表或技術摘要。
5. **Applications / 實際應用** — At least two real-world applications or cases, supported by citations. / 至少兩個有引用支持的實際應用或案例。
6. **Annotated resources / 附註資源** — At least five credible resources. For each, give its full title, author or organization, type and year when available, working DOI or URL, the specific concept it supports, and why a learner should open it. Include at least one scientific publication, technical standard, or similarly authoritative technical reference. A bibliography alone is insufficient. / 至少五項可信資源。每項列出完整標題、作者或組織、類型與年份（如有）、有效 DOI 或網址、支持的具體概念，以及推薦閱讀的原因；至少一項須為學術論文、技術標準或同等權威技術資料。只有參考書目清單不足夠。
7. **Connections / 章節連結** — At least two contextual links to teammates' pages, explaining their conceptual relationship. Menu links do not count. / 至少兩個連到組員頁面的內文連結，並解釋概念關係；選單連結不算。
8. **Reflection / 學習反思** — State key learning points, one limitation or misconception, and a verified claim with its source. / 說明主要心得、一項限制或常見誤解，以及一項有來源支持的已查證主張。
9. **AI and Source Use / AI 與資料使用聲明** — Briefly state which AI tools were used and for what purpose; verify technical claims using credible sources. If none were used, say so. / 簡述使用的 AI 工具及用途，並以可信資料查證技術主張；若未使用 AI，亦請註明。

The suggested total is **about 400–600 words per page**, including a **100–150 word reflection**; these are guidelines, not strict limits. / 每頁建議總長約 **400–600 字詞**，包含約 **100–150 字詞的反思**；這是建議而非嚴格限制。

The group also needs a **resource library** and a **contribution record** covering each member's section, diagrams, resource selection, comparisons, editing, and peer review. / 小組另須建立**資源庫**與**貢獻紀錄**，標示各人負責章節、圖表、資源選擇、比較、編輯及同儕審查。

## 3. Create a GitHub repository｜建立 GitHub 儲存庫

1. Sign in to [GitHub](https://github.com/). The group should decide which member will own the repository. / 登入 [GitHub](https://github.com/)，並決定由哪位組員建立儲存庫。
2. Click **+ → New repository**. Choose a name such as `multimedia-team-01` and select **Public**. Optionally initialize it with a README, then click **Create repository**. / 點選右上角 **+ → New repository**，輸入名稱（例如 `multimedia-team-01`），選 **Public**，可選擇建立 README，再按 **Create repository**。
3. The owner can invite teammates under **Settings → Collaborators**; teammates need to accept the invitation. / 擁有者可在 **Settings → Collaborators** 邀請組員；組員須接受邀請。

## 4. Create and upload website files｜建立並上傳網站檔案

GitHub Pages needs an entry page. For this guide, create an `index.html` file in the **root** (top level) of your repository. You may create other HTML pages and images as needed. / 本教學使用位於儲存庫**最外層**的 `index.html` 作為入口頁。其他 HTML 頁面及圖片可依需要建立。

A possible file layout / 參考檔案結構：

```text
index.html          # Home / 首頁
section-1.html      # Student page / 個人頁面
section-2.html
section-3.html
section-4.html
section-5.html
section-6.html
resources.html      # Resource library / 資源庫
contributions.html  # Contribution record / 貢獻紀錄
images/             # Diagrams and images / 圖表與圖片
```

These names are examples, except that this guide uses `index.html` as the entry page. Organize the site to match your group's needs. / 除本教學使用 `index.html` 作為入口外，其餘檔名只是範例，可依小組需要調整。

**Option A: upload files / 方法 A：上傳檔案**

1. Create the website files on your computer. On the repository page, choose **Add file → Upload files**. / 先在電腦建立網站檔案，在 repository 選 **Add file → Upload files**。
2. Drag the files into the upload area. Place `index.html` at the top level, not inside an extra enclosing folder. / 將檔案拖入上傳區；確認 `index.html` 放在最外層，而非多包一層資料夾。
3. Enter a short description and click **Commit changes**. / 輸入簡短說明並點 **Commit changes**。

**Option B: create or edit a file on GitHub / 方法 B：直接在 GitHub 建立或編輯**

1. Choose **Add file → Create new file**, name it `index.html`, and enter your page content as HTML. / 選 **Add file → Create new file**，命名為 `index.html`，輸入 HTML 頁面內容。
2. Click **Commit changes**, enter a brief message, and confirm. To edit later, open the file and click the pencil icon. / 點 **Commit changes**，輸入修改說明並確認；日後可開啟檔案並點鉛筆圖示編輯。
3. Coordinate with teammates before editing the same file. Do not upload passwords or private information to a public repository. / 修改同一檔案前請與組員協調；勿將密碼或私人資料上傳至公開 repository。

A minimal starting page / 最基本的首頁範例：

```html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Our Multimedia Learning Hub</title>
</head>
<body>
  <h1>Our Multimedia Learning Hub</h1>
  <p>Team number, members, topic, and learning objectives go here.</p>
  <p><a href="section-1.html">Section 1: Topic and author</a></p>
</body>
</html>
```

Create the linked page before submitting, and add the remaining sections, sources, and group information. / 繳交前須建立連結指向的頁面，並補上其餘章節、資料來源與小組資訊。

## 5. Publish with GitHub Pages｜使用 GitHub Pages 發布

1. In **your group's repository**, open **Settings → Pages**. / 在**自己小組的 repository** 開啟 **Settings → Pages**。
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**. / 在 **Build and deployment** 的 **Source** 選擇 **Deploy from a branch**。
3. Select the `main` branch and `/(root)` folder, then click **Save**. / 選擇 `main` 分支及 `/(root)` 資料夾，按 **Save**。
4. Wait for deployment and refresh the Pages settings page. Open the displayed site URL; the usual format is `https://USERNAME.github.io/REPOSITORY/`, but use the URL GitHub displays. / 等待部署並重新整理 Pages 設定頁，開啟顯示的網址。常見格式為 `https://帳號.github.io/儲存庫名稱/`，但請以 GitHub 顯示的網址為準。
5. After later commits to the publishing branch, wait for deployment again and check the updated site. / 日後提交至發布分支後，請等待重新部署並確認更新結果。
6. Test the URL in a private/incognito window. If it does not work, check the branch, folder, `index.html`, and the deployment status under **Actions**. / 使用無痕視窗測試；若無法開啟，請檢查分支、資料夾、`index.html` 以及 **Actions** 中的部署狀態。

Official guide / 官方教學：[Configuring a publishing source for GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

## 6. Submission checklist｜繳交前檢查

- [ ] The homepage, individual pages, resource library, and team contributions are complete. / 首頁、個人頁面、資源庫及貢獻紀錄已完成。
- [ ] Each page includes the required resources, credits, illustration, synthesis, applications, contextual links, reflection, and AI statement. / 每頁都有要求的資源附註、來源、自製圖、整理、應用、內部連結、反思與 AI 聲明。
- [ ] The public website opens without sign-in; images, citations and links work. / 公開網站無須登入即可開啟，圖片、引用與連結正常。
- [ ] Every student can explain their page and support a claim with a cited source. / 每人都能解釋自己的頁面，並以引用來源支持主張。
- [ ] One representative submits **one website URL** through the course portal, together with the group number, project title, member names and IDs, and platform. No separate PDF report or GitHub repository is mandatory. / 一位代表透過課程平台繳交**一個網站網址**，並附組別、專題名稱、組員姓名與學號及平台；不強制另交 PDF 報告或 GitHub repository。

**Deadline and presentation date: to be announced by the instructor.** The original instructions state a five-week duration but list milestones only for weeks 1–4. / **截止與報告日期：待老師公告。**原始說明標示總期程為五週，但僅列出第 1–4 週里程碑。
