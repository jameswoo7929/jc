濟生中西藥局 (JCpharmacy) POS 系統

這是一個基於 Web 的輕量級藥局 POS (銷售時點情報系統) 管理系統。採用單頁式應用程式 (SPA) 架構，無需安裝後端伺服器，直接開啟瀏覽器即可使用。

🌟 系統特色

雙模式介面：包含「前台收銀」與「後台管理」功能。

J/C 品牌識別：

J (Blue)：代表中藥 (Science Chinese Medicine)，使用藍色系。

C (Orange)：代表西藥 (Western Medicine)，使用橘色系。

完全響應式設計：支援電腦、平板操作，介面採用專業醫療潔淨風格。

資料持久化：使用瀏覽器 localStorage 儲存資料，重新整理不流失。

Excel 整合：支援資料庫的匯入與匯出 (備份/還原)。

PDF 收據：結帳後自動生成 80mm 熱感應紙規格的 PDF 收據。

🚀 使用方式

線上瀏覽：(在此處貼上您的 GitHub Pages 連結)

本地執行：

下載本專案的 index.html 檔案。

直接雙擊檔案，使用 Chrome, Edge 或 Safari 瀏覽器開啟。

🛠️ 技術棧

HTML5

Tailwind CSS (透過 CDN) - 樣式框架

Font Awesome (透過 CDN) - 圖標庫

SheetJS (xlsx) - Excel 資料處理

jsPDF - PDF 收據生成

Vanilla JavaScript - 核心邏輯

📂 功能列表

前台收銀 (POS)

商品快速搜尋與分類過濾。

購物車即時計算。

會員搜尋與帶入（累積點數）。

結帳找零計算與庫存自動扣除。

後台管理 (Admin)

商品管理：新增、修改、刪除商品，設定成本/售價/庫存。

會員管理：管理會員資料與點數。

人員管理：管理藥師與員工名單。

資料備份：一鍵匯出/匯入完整資料庫 (.xlsx)。

⚠️ 注意事項

本系統資料儲存於使用者的瀏覽器中 (Local Storage)。

請勿清除瀏覽器快取，否則資料將會遺失。

建議定期使用後台的「匯出 Excel」功能進行資料備份。

Designed for Jisheng Pharmacy (JCpharmacy)