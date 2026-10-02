# VaultSync 發布下載

個人測試中的繁體中文桌面工具，以獨立 Syncthing 引擎同步 Obsidian 筆記。

本倉庫只提供安裝包、版本說明與 SHA256；開發倉庫不公開。Electron 安裝包包含打包後的 JavaScript，並不保證程式邏輯保密。

請由 [Releases](https://github.com/allenyang0721/vaultsync-releases/releases) 選取對應平台的版本，先讀該版的已知限制。標記 Pre-release 的版本僅供隔離測試，不代表 Windows／Mac 完整真機驗收通過。

## 更新原則

- 安裝前明確退出 VaultSync；關閉視窗仍會在系統匣執行。
- 保留本機 App 資料目錄，勿刪除裝置身分或拿其他電腦的身分備份覆蓋。
- 更新不等於正式 Vault 導入；先用測試資料夾驗證，正式導入前另做最新完整備份。
- 此工具不提供雲端筆記儲存；設備需同時在線才能同步。

## 第三方元件

- [Syncthing v2.1.5](https://github.com/syncthing/syncthing/releases/tag/v2.1.5)：Mozilla Public License 2.0；對應 [來源程式碼](https://github.com/syncthing/syncthing/tree/v2.1.5) 與 [授權](https://github.com/syncthing/syncthing/blob/v2.1.5/LICENSE)。使用未修改的官方執行檔。
- [Electron](https://www.electronjs.org/)：MIT 及隨附第三方授權，見安裝包中的 LICENSE／LICENSES.chromium.html。

安裝包不含使用者筆記、裝置私鑰或預先配對設定。
