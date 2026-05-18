# Unreleased Changelog

This file tracks v0.1.x maintenance changes that have not been published as a stable release yet.

## English

## [0.1.3] - Unreleased

### Added
- Added explicit math font selection with `\UseMathFont{...}`.
- Added `mlmodern` as a registry-backed legacy font route.
- Added automatic Libertinus Math selection when `fonts={libertinus}` is loaded before the `math` feature.
- Added a Libertinus math test example.

### Changed
- Updated the Libertinus catalog entry to use TeX Live OTF family names and include mono.
- Refined Chinese UI section numbering, table-of-contents spacing, caption labels, and starred heading TOC handling.
- Relaxed TeX badness defaults to reduce noisy overfull/underfull diagnostics in template output.
- Refined quote spacing in the English document layout.

## Traditional Chinese

## [0.1.3] - 未發佈

### 新增
- 新增 `\UseMathFont{...}`，可明確選擇數學字體路線。
- 新增 `mlmodern`，作為 registry 可選的傳統 LaTeX 字體路線。
- 當 `math` feature 載入前已使用 `fonts={libertinus}` 時，自動選用 Libertinus Math。
- 新增 Libertinus math 測試示例。

### 調整
- 更新 Libertinus catalog 條目，改用 TeX Live OTF 字族名稱並加入 mono。
- 改善中文 UI 的章節編號、目錄間距、圖表題名與星號標題入目錄行為。
- 放寬 TeX badness 預設值，減少模板輸出中的 overfull/underfull 診斷噪音。
- 調整英文 document layout 的 quote 間距。
