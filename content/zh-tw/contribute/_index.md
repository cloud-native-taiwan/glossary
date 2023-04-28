---
title: 如何貢獻
toc_hide: true
status: Completed
menu:
  main:
    weight: 10
---

## 歡迎

歡迎使用 Cloud Native Glossary 的貢獻指南，感謝您的關注。 
您可以透過以下方式參與貢獻，我們將在此進行詳細說明：

1) [處理現有問題](#work-on-an-existing-issue)
2) [提出新術語](#propose-new-terms)
3) [更新現有術語](#update-an-existing-term)
4) [本地化術語表](#help-localize-the-glossary)

## CNCF Glossary 概述

該詞彙表的目標是簡化複雜的雲原生領域，使其更容易被人們理解和使用。

Cloud Native Glossary 的內容存儲在 [此GitHub存儲庫](https://github.com/cncf/glossary) 中，
您可以在那裡找到有關詞彙表的 [問題](https://github.com/cncf/glossary/issues)、[拉取請求（PR）](https://github.com/cncf/glossary/pulls) 和 
[討論](https://github.com/cncf/glossary/discussions)。

## 誰可以貢獻？

您可以參與該項目的方式取決於您的雲原生專業水平。簡化複雜的概念需要對該主題有深入的了解。
因此，要貢獻新詞彙，您必須精通該主題。貢獻者通常是在這些技術上工作了一段時間的工程師或專注於雲原生的學者。


專業知識是必需的，因為用簡單的話語解釋複雜的概念真的很難。而且，儘管易於理解的結果可能看起來很簡單，但達到所需的簡單性需要雲原生專家之間的努力和協作。

如果您尚未成為雲原生專家但仍想貢獻，我們建議與專家合作。一旦專家確信術語準確描述概念，您就可以做出第一個詞彙表貢獻。

本地化是初學者可以為詞彙表提供有價值貢獻的地方。在英語中有堅實的現有定義的情況下，經驗較少的貢獻者可以將術語本地化到目標語言。您可以加入現有的本地化團隊或創建新的本地化團隊。閱讀本指南的[幫助本地化詞彙表](#help-localize-the-glossary)章節，了解如何入手。


## 開始之前

在開始你的Glossary貢獻之前，請確認完成以下步驟：

1. 建立[GitHub帳號](https://docs.github.com/zh/get-started/signing-up-for-github/signing-up-for-a-new-github-account)，如果你還沒有。
2. 簽署[貢獻者授權協議](https://docs.linuxfoundation.org/lfx/easycla/v2-current/contributors) (CLA)。
3. [驗證你的提交簽名](https://docs.github.com/zh/authentication/managing-commit-signature-verification/about-commit-signature-verification)。
4. 啟用[vigilant mode](https://docs.github.com/zh/authentication/managing-commit-signature-verification/displaying-verification-statuses-for-all-of-your-commits#about-vigilant-mode)在你的GitHub帳戶上，以顯示"已驗證"狀態在你的提交上。

## 最佳實踐 {#best-practices}

為了方便審查過程，請使用[語意斷行](https://sembr.org/) (例如，每個句子一行)。 我們建議查看這個[markdown cheat sheet](https://www.markdownguide.org/cheat-sheet/)以在GitHub中正確格式化Markdown文本(例如，超鏈接，粗體，斜體)。 並且在命名.md文件時，請使用小寫字母和連字符而不是空格來分隔單詞並避免使用括號。

## 開始之前

在開始你的 Glossary 貢獻之前，請確保完成以下步驟：

1. 建立一個 [GitHub 帳戶](https://docs.github.com/en/get-started/signing-up-for-github/signing-up-for-a-new-github-account)，如果你還沒有帳戶的話。
2. 簽署 [貢獻者授權協議](https://docs.linuxfoundation.org/lfx/easycla/v2-current/contributors) (CLA)。
3. [驗證你的提交簽名](https://docs.github.com/en/authentication/managing-commit-signature-verification/about-commit-signature-verification)
4. 在你的 GitHub 帳戶中啟用 [vigilant 模式](https://docs.github.com/en/authentication/managing-commit-signature-verification/displaying-verification-statuses-for-all-of-your-commits#about-vigilant-mode)，以在你的提交上顯示「已驗證」狀態。

## 最佳實踐 {#best-practices}

為了方便審查過程，請使用 [semantic line breaks](https://sembr.org/)（例如，每句話一行）。
我們建議查看這份 [markdown cheat sheet](https://www.markdownguide.org/cheat-sheet/) 以正確地在 GitHub 中格式化 Markdown 文本（例如，超連結、粗體、斜體）。
並且在命名 .md 文件時，請使用小寫字母和連字符而不是空格來分隔單詞，避免使用括號。

## 樣式指南

閱讀我們的 [樣式指南](/style-guide/) 以了解我們的格式和撰寫文件的指南，使貢獻流程更加高效。

## 加入 Glossary 社群！ {#join-the-glossary-community}

如果您想定期貢獻，請考慮加入我們的月度 Glossary 工作組會議。
您可以在 [CNCF 日曆](https://www.cncf.io/calendar/) 中找到會議詳細信息。
您也可以在 CNCF Slack 的 [#glossary](https://cloud-native.slack.com/archives/C02TX20MQBB) 頻道中與維護人員和其他貢獻者聯繫 - 我們很樂意認識你！

## 在現有問題上進行工作 {#work-on-an-existing-issue}

前往[Glossary GitHub 存儲庫的問題](https://github.com/cncf/glossary/issues)找到可用問題列表。您可以使用標籤（例如英語語言、需要幫助、良好的第一個問題）過濾問題。

![問題和標籤](/images/how-to/issue-and-labels.png)

確保您選擇的術語還沒有被分配給任何人。例如，您可以看到前三個術語是可用的，而第四個術語已被分配。

![分配術語](/images/how-to/howto-04.png)

選擇一個要處理的術語後，在該問題上發表評論。

![聲明問題](/images/how-to/claiming-an-issue.png)

此外，通知CNCF Slack工作區的＃glossary頻道上的維護人員和其他貢獻者，
並標記 @Catherine Paganini、@Seokho Son、@Jihoon Seo 和/或 @iamnoah，以確保他們不會錯過它。

有關下一步，請參閱 [提交新術語（創建 PR）](#submitting-a-new-term) 部分。

**注意**：您只能在維護人員將問題分配給您後開始處理問題。
您一次只能聲明一個術語。處理多個術語是有序進行的，必須在聲明下一個術語之前完成當前術語。


## 提議新詞彙 {#propose-new-terms}

您可以提出新詞彙供他人研究，或自己創建新定義。不管哪種方式，您都需要從[創建問題](#creating-an-issue)開始。每個新詞彙必須符合[CNCF的雲原生定義](https://github.com/cncf/toc/blob/main/DEFINITION.md)才能被添加到詞彙表中，除了用於理解雲原生概念的基礎詞彙。

以下是對於不熟悉GitHub的人的逐步指南。如果您是GitHub專家，請掃描本指南以獲取有關以下主題的足夠信息：

1. 定位問題和新詞彙的模板。
2. 聲明問題。
3. 解決[拼寫檢查](#spell-check)失敗的問題。

### 創建問題 {#creating-an-issue}

前往[Glossary GitHub repo issues](https://github.com/cncf/glossary/issues)，然後點擊“New issue”。

![issues](/images/how-to/howto-01.png)

從模板列表中選擇“Request to add a new term (English)”。

![templates](/images/how-to/english-issue-template.jpg)

添加您建議的單詞，回答問題，勾選方框，然後點擊“Submit new issue”。
如果您只是提出新詞彙，那麼您已經完成了！如果您想要創建定義，請繼續閱讀。

### 緊急處理您的問題 {#triaging-your-issue}

接下來，維護者將會進行緊急處理。這意味著他們將評估該術語是否應該成為詞彙表的一部分。並不是每個術語都會被批准。若要納入詞彙表，它們應該是建立且廣泛使用的雲原生概念。

請讓維護者知道您已在Slack上提出新術語並標記 _@Catherine Paganini_、_@Seokho Son_、_@Jihoon Seo_和/或_@iamnoah_，以便他們不會錯過。 如果您想編寫定義，請讓維護者知道，他們會指派它給您。

### 提交新術語（創建 PR）{#submitting-a-new-term}

如我們的[風格指南](/zh-tw/style-guide/)所述，我們強烈建議先使用Google 文檔或 Word 文檔進行起草。

一旦術語準備好提交，請轉到 content（在<>代碼下）…

![content](/images/how-to/howto-05.png)

…然後轉到 "zh-tw" 或您要貢獻的語言的前兩個字母…

![語言文件夾](/images/how-to/howto-06.png)

…並選擇 `_TEMPLATE.md`

![模板](/images/how-to/howto-07.png)

複製內容

![複製內容](/images/how-to/howto-08.png)

…然後返回"zh-tw"文件夾。單擊 "add file"並選擇"create new file"。

![創建新文件](/images/how-to/howto-09.png)

按照[最佳實踐](#best-practices)中所述，在URL中添加術語的名稱。在名稱的末尾添加 .md 擴展名（如果沒有此擴展名，您將無法預覽文件）。
現在在下面的部分中粘貼模板內容。將定義文本的內容複製並粘貼到文件中。為了驗證您已按照[最佳實踐](#best-practices)中所述使用Markdown，請單擊“preview”。

![最終確定術語](/images/how-to/howto-10.png)

向下滾動並為新提交的文件命名。當您準備好提交時，請點擊“提交新文件”


![完成術語](/images/how-to/howto-10.png)

往下滾動並為新提交的檔案命名。當您準備好提交時，點擊「提交新檔案」按鈕...

![提交新檔案](/images/how-to/howto-11.png)

...現在您已準備好創建新的PR：

![創建PR](/images/how-to/howto-12.png)

當您按下「創建拉取請求」按鈕時，您的PR應顯示在「拉取請求」標籤中。

![PRs](/images/how-to/howto-13.png)

## 更新現有術語 {#update-an-existing-term}

要更新現有術語，您可以通過創建問題要求更改，也可以自行進行更改並提交PR。

### 透過問題要求更改 {#request-a-change-via-an-issue}

如果您想要標記術語的問題，您可以使用CNCF詞彙表網頁的 "Report issue" 選項。
在您想要標記的概念的CNCF頁面上定位自己，然後點擊 "Report issue"。
這會自動為您打開一個議題

![報告議題](/images/how-to/howto-14.png)

請描述您的建議以及為什麼需要它們。點擊提交，就完成了。

![提交問題](/images/how-to/howto-15.png)



### 直接更新術語 {#update-a-term-directly}

若要修改術語並提交建議，請點擊「編輯此頁」。

![edit this page](/images/how-to/howto-16.png)

這將打開術語的GitHub頁面。進行修改並建立PR。請參考上面的[最佳實踐](#best-practices)部分，並閱讀我們的[樣式指南](/zh-tw/style-guide/)以確保您遵循我們的指南。

## 幫助本地化詞彙表 {#help-localize-the-glossary}

如果要幫助將詞彙表本地化為目標語言，請加入CNCF Slack工作區中的[#glossary-localizations](https://cloud-native.slack.com/archives/C02N2RGFXDF)頻道，然後發送消息給我們。
您可以加入現有團隊或創建新團隊
（要查看需要什麼，請閱讀我們的[本地化指南](https://github.com/cncf/glossary/blob/main/LOCALIZATION.md)）。
請閱讀目標語言的**如何貢獻**指南，以了解該團隊的具體貢獻流程。

## 拼寫檢查 {#spell-check}

拼寫檢查可能失敗的兩個主要原因：

- PR 中包含拼寫錯誤。
- PR 中包含未在單詞列表中註冊的單詞。

要將新單詞添加到列表中，請按照以下步驟進行操作：

1. 在您的 PR 中，找到 "wordlist.txt" 文件。
2. 點擊 "Edit this file" 並按字母順序添加缺少的單詞。
3. 添加提交消息，然後選擇 "Sign off and propose changes"。

**注意**：拼寫檢查不區分大小寫。


**我們基於[The Good Docs Project](https://thegooddocsproject.dev/)的模板更新了此指南。**
