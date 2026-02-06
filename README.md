# LLM Guide

> **Current Status: Mockup / Prototype**

本專案目前處於 **Mockup (原型)** 階段，主要用於展示概念與頁面結構。

## 專案現況

- **靜態展示**：目前的網頁內容（包含工具列表、分類等）皆為 Hardcode 在 HTML 中的靜態資料。
- **功能限制**：部分互動功能僅為演示用途，尚未連接真實後端邏輯。
- **功能限制**：部分互動功能僅為演示用途，尚未連接真實後端邏輯。
- **行動裝置優化 (RWD)**：
    - 已完成手機版面 (Mobile-First) 的適配，包含標題排版優化與元件防溢處理。
    - 分類選單採用「水平捲動」設計，提升小螢幕操作體驗。

## 技術架構與遷移目標 (Technical Stack & Migration)

- **目前實作 (Current Implementation)**：
    - 使用 **Alpine.js** 處理極輕量的互動邏輯。
    - 使用 **Tailwind CSS** 進行快速樣式開發。
    - 目標是快速驗證 Mockup 互動與視覺效果。

- **未來遷移目標 (Future Migration)**：
    - 預計遷移至 **Next.js (React)** 框架。
    - **核心目標**：目前的 HTML 結構與 Class 命名需保持乾淨，以將未來轉換至 React Component 的阻力降到最低。

## 後續開發規劃 Roadmap

本專案將按以下階段進行後續開發：

1.  **UI/UX 設計調整 (Design Phase)**
    - 導入企業識別系統 (CIS)。
    - 調整配色方案 (Color Scheme) 以符合企業形象。
    - 優化整體視覺樣式與使用者體驗。

2.  **後端開發與資料庫建置 (Backend & Database)**
    - 設計資料庫架構，將目前的靜態資料轉入資料庫。
    - 開發 RESTful API 或 GraphQL 接口，提供前端資料存取。
    - 實作資料管理後台 (Admin Panel) 以便維護內容。

3.  **前端功能實作 (Frontend Implementation)**
    - 介接後端 API，實現動態資料渲染。
    - 實作完整的搜尋、篩選與分類功能。
    - 完成最終頁面互動邏輯。

---

*This project is currently a work in progress.*
