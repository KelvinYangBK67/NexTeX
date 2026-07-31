# Unreleased Changelog

This file tracks v0.1.x maintenance changes that have not been published as a stable release yet.

## English

## [0.1.3] - Unreleased

### Added
- Added explicit math font selection with `\UseMathFont{...}`.
- Added `mlmodern` as a registry-backed legacy font route.
- Added a Libertinus math test example.
- Added hyperlink stabilization for repeated heading numbers, reverse heading-to-TOC links, and bidirectional footnote marker links.

### Changed
- Updated the Libertinus catalog entry to use TeX Live OTF family names and include mono.
- Isolated text-family loading from math with fontspec's `no-math` option, keeping the complete Computer Modern math setup when `fonts={libertinus}` is used; Libertinus Math now requires explicit `\UseMathFont{libertinus}` selection.
- Refined Chinese UI section numbering, table-of-contents spacing, caption labels, and starred heading TOC handling.
- Made all numbered paper-layout TOC entries, including chapters and nested sections, expand their number boxes to the label's natural width with a stable gap.
- Relaxed TeX badness defaults to reduce noisy overfull/underfull diagnostics in template output.
- Refined quote spacing in the English document layout.

## Traditional Chinese

## [0.1.3] - 未發佈

### 新增
- 新增 `\UseMathFont{...}`，可明確選擇數學字體路線。
- 新增 `mlmodern`，作為 registry 可選的傳統 LaTeX 字體路線。
- 新增 Libertinus math 測試示例。

### 調整
- 更新 Libertinus catalog 條目，改用 TeX Live OTF 字族名稱並加入 mono。
- 以 fontspec 的 `no-math` 選項隔離文字與數學字體；使用 `fonts={libertinus}` 時會完整保留預設 Computer Modern 數學設定，Libertinus Math 現在必須透過 `\UseMathFont{libertinus}` 明確選用。
- 改善中文 UI 的章節編號、目錄間距、圖表題名與星號標題入目錄行為。
- 紙本 layout 的所有帶編號目錄項（包括 chapter 與各層 section）會依編號自然寬度擴張並保留固定間距。
- 放寬 TeX badness 預設值，減少模板輸出中的 overfull/underfull 診斷噪音。
- 調整英文 document layout 的 quote 間距。
