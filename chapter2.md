# 2. 使用 Visual Studio 修改他人專案

當我們在 GitHub 中看到我們需要的專案並想下載修改他時，我們可以直接以 zip 檔直接從 GitHub 下載。我們也可以透過 Git 指令直接進行 "Clone" 的動作，將該專案從 GitHub 複製。但因為我們對別人專案通常沒有直接的權限，故我們在本地端修改的版本，無法直接在上傳回去給原專案開發者進行合併。GitHub 提供了 "Fork" 機制，讓我們將有興趣的專案 Repository 先完整的複製一份至我們自己的 GitHub 的帳戶，然後我們可以在本機端進行下載 \(Pull\)、編輯、上傳 \(Push\)，最後 Final 的版本再透過 GitHub 上的 "Pull Request" 機制，通知此專案原開發者我們有一個修改後的版本供他使用。專案原開發者收到 Pull Request 後，可以決定是否要合併或是拒絕你的請求。本章將說明如何使用 Visual Studio 修改他人的專案。步驟分別為：

2-1. 在 GitHub 上 Fork 他人專案

2-2. 使用 Visual Studio 下載專案進行開發

2-3. 將修改完畢的專案上傳至 GitHub

2-4. 提出 Pull Requerst 請求專案原作者審閱

