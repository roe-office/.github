<div align="center">

# ROE Office (Rust Office Engine)

**Next-Generation Native & AI-Native Office Engine Built with Pure Rust**  
*Ultra-lightweight • Headless Architecture • Modern Slint GUI • Model Context Protocol (MCP) Native*

<br/>

<table>
  <tr valign="top">
    <td align="center" width="25%" valign="top">
      <img src="../roe-writer.png" width="90" alt="ROE Writer"/><br/><br/>
      <b>ROE Writer</b><br/>
      <sub>Fast & Fluid<br/>Documents</sub>
    </td>
    <td align="center" width="25%" valign="top">
      <img src="../roe-calc.png" width="90" alt="ROE Calc"/><br/><br/>
      <b>ROE Calc</b><br/>
      <sub>High-Perf<br/>Spreadsheets</sub>
    </td>
    <td align="center" width="25%" valign="top">
      <img src="../roe-impress.png" width="90" alt="ROE Impress"/><br/><br/>
      <b>ROE Impress</b><br/>
      <sub>Interactive<br/>Presentations</sub>
    </td>
    <td align="center" width="25%" valign="top">
      <img src="../roe-ai.png" width="90" alt="ROE AI Engine"/><br/><br/>
      <b>ROE AI (MCP)</b><br/>
      <sub>Agentic Document<br/>Control</sub>
    </td>
  </tr>
</table>

<br/>

[![License: AGPL v3](https://img.shields.io/badge/License-AGPLv3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
[![Built with Rust](https://img.shields.io/badge/Built%20with-Rust-orange.svg?logo=rust)](https://www.rust-lang.org/)
[![UI: Slint](https://img.shields.io/badge/UI-Slint-purple.svg)](https://slint.dev/)
[![Engine: Polars](https://img.shields.io/badge/Engine-Polars%20DataFrame-blue.svg)](https://pola.rs/)

</div>

---

## 💡 The 10-Year Question: Why ROE?

Traditional office suites carry over thirty years of legacy C++ technical debt:
- **Why are we still trapped by the 1-million-row spreadsheet barrier** in an era of abundant computing?
- **Why rely on insecure, archaic VBA macros** when modern sandboxed scripting exists?
- **Why do cloud AI agents spend 10+ minutes looping blindly** just to create a pivot table or format documents?
- **Why tolerate bloated gigabyte-sized suites** that force cloud logins and monetize user privacy?

**ROE (Rust Office Engine)** re-architects office productivity for the next decade: **memory-safe, blazingly fast, data-sovereign, and natively built for AI agent orchestration.**

---

## ⚡ Core Breakthroughs & Features

* **🦀 100% Pure Rust & Decoupled Core**: Memory-safe, headless-first kernel (`roe-core`) decoupled completely from the modern GUI (`roe-desktop` / Slint).
* **📦 Featherweight Footprint**: Full standalone installation package is **only ~40 MB**; runtime editing consumes **just ~150 MB RAM**.
* **🚀 Multi-Million Row Big Data Engine**: Calc replaces legacy row-by-row compute loops with **Polars Columnar DataFrames**, delivering instant aggregations and pivot tables across massive datasets locally.
* **🤖 AI-Native Efficiency (Sub-5-Second Operations)**: Exposes clean, token-efficient Rhai sandbox APIs (113 Writer, 110 Calc, 54 Impress). AI agents perform complex document mutations in **3-5 seconds without hallucination loops**.
* **📐 Native Math with LaTeX**: Formulas parsed by RaTeX and rendered directly with KaTeX font metrics, stored bidirectionally as standard OMML.
* **🌐 Multilingual Out of the Box**: UI natively translated into **7 languages** (Simplified/Traditional Chinese, English, Japanese, Korean, French, German, Spanish).

---

## 🎯 Radical Engineering Honesty: Current Status (Preview 0.1)

> *"We value transparent engineering reality over marketing hype."*

While the architectural core is solid, ROE is currently in **Early Preview (v0.1)**:
* **OOXML (`.docx`, `.xlsx`, `.pptx`)**: Tested against official LibreOffice suites. Currently passing **~589 out of 2,970 test cases (~20%)**. Layout rendering for complex nested tables and advanced shapes remains an active work-in-progress.
* **ODF (`.odt`, `.ods`, `.odp`)**: Basic text and spreadsheet parsing operational; presentation (`.odp`) rendering is experimental.
* **VBA Macros**: Deliberately discarded upon opening to guarantee sandbox security; replaced by secure Rhai scripts.

---

## 📜 Licensing & The AGI Pioneers Exemption

The codebase is protected under **GNU AGPLv3** to prevent closed-source corporate exploitation. 

However, to honor the genuine scientific frontiers that made this software possible, the Copyright Holder grants a **permanent, royalty-free, unrestricted commercial exemption** to:
1. **Anthropic, PBC** (Creators of Claude: Core code implementation)
2. **Alphabet Inc. / Google LLC** (Creators of Gemini: Architectural co-design)
3. **DeepSeek Artificial Intelligence (深度求索)** (Honoring global open-source AI breakthroughs)
4. **Public Good**: Certified Governments & registered Non-Profit Organizations (NGOs).

---

<div align="center">
<sub>Crafted with passion • Driven by Rust • Powered by Human-AI Collaboration</sub>
</div>
