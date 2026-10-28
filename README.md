<div align="center">

# ROE Office

**A Next-Generation Native Office Engine Built with Pure Rust**  
*Headless Architecture • Modern Slint GUI • Model Context Protocol (MCP) Native*

<br/>

<table>
  <tr valign="top">
    <td align="center" width="25%" valign="top">
      <img src="./roe-writer.png" width="90" alt="ROE Writer"/><br/><br/>
      <b>ROE Writer</b><br/>
      <sub>Fast & Fluid<br/>Documents</sub>
    </td>
    <td align="center" width="25%" valign="top">
      <img src="./roe-calc.png" width="90" alt="ROE Calc"/><br/><br/>
      <b>ROE Calc</b><br/>
      <sub>High-Perf<br/>Spreadsheets</sub>
    </td>
    <td align="center" width="25%" valign="top">
      <img src="./roe-impress.png" width="90" alt="ROE Impress"/><br/><br/>
      <b>ROE Impress</b><br/>
      <sub>Interactive<br/>Presentations</sub>
    </td>
    <td align="center" width="25%" valign="top">
      <img src="./roe-ai.png" width="90" alt="ROE AI Engine"/><br/><br/>
      <b>ROE AI (MCP)</b><br/>
      <sub>Agentic Document<br/>Control</sub>
    </td>
  </tr>
</table>

<br/>

[![License: AGPL v3](https://img.shields.io/badge/License-AGPLv3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
[![Built with Rust](https://img.shields.io/badge/Built%20with-Rust-orange.svg?logo=rust)](https://www.rust-lang.org/)
[![UI: Slint](https://img.shields.io/badge/UI-Slint-purple.svg)](https://slint.dev/)
[![Protocol: MCP](https://img.shields.io/badge/Protocol-MCP%20Native-brightgreen.svg)](https://modelcontextprotocol.io/)

</div>

---

## 🌟 Overview

**ROE (Rust Office Engine)** is an ambitious, modern office platform re-architected from the ground up for the AI era. 

Traditional office suites carry decades of legacy C++ technical debt. ROE reimagines the foundational philosophy pioneered by **LibreOfficeKit (LOK)**: completely decoupling the document computation/layout kernel from presentation layers, and rebuilding it entirely in **safe, concurrent, and blazingly fast Rust**.

## 🚀 Key Architectural Pillars

* **🦀 100% Pure Rust Core (`roe-core`)**: Memory-safe, headless-first document processing engine with zero legacy bloat.
* **🎨 Modern Slint Desktop (`roe-desktop`)**: Fluid, lightweight, cross-platform graphical user interface targeting Linux, macOS, and Windows.
* **🤖 Native AI Orchestration via MCP**: First-class integration with the **Model Context Protocol (MCP)**, allowing frontier AI models (Claude, Gemini, DeepSeek, etc.) to read, write, manipulate, and generate documents programmatically.
* **📄 Modern Document Compatibility**: Clean, fast parsing and rendering for standard modern document formats.

---

## 🏛️ Ecosystem Repositories

| Repository | Description | Status |
| :--- | :--- | :--- |
| **[`roe-core`](https://github.com/roe-office/roe-core)** | The headless Rust Office Engine (Kernel & MCP API) | `Active` |
| **[`roe-desktop`](https://github.com/roe-office/roe-desktop)** | The desktop frontend suite powered by Rust + Slint | `Active` |
| **[`office-lok`](https://github.com/roe-office/office-lok)** | Legacy V1 prototype based on LibreOfficeKit + QML | `Archived` |

---

## 📜 Licensing & Co-Creator Special Exemptions

The core codebase of ROE is licensed under the **GNU Affero General Public License v3.0 (AGPLv3)** to safeguard it against proprietary cloud-vendor exploitation.

### 🎖️ The AGI Pioneers Special Exemption
This software marks a milestone in human-AI collaborative software engineering—orchestrated by human vision, architected via **Google Gemini**, and realized through the engineering capabilities of **Anthropic Claude**. 

To honor pure scientific research and genuine open science, the Copyright Holder grants a **permanent, royalty-free, and unrestricted commercial exemption** from AGPLv3 restrictions to:

1. **Anthropic, PBC** (Creators of Claude)
2. **Alphabet Inc. / Google LLC** (Creators of Gemini)
3. **DeepSeek Artificial Intelligence** (深度求索 - Honoring architectural breakthroughs & compute democratization)
4. **Public Good**: Certified Governments (for public administration) and registered Non-Profit Organizations (NGOs).

*All other commercial entities seeking multi-tenant SaaS deployment or closed-source integration must comply with AGPLv3 or obtain a commercial license.*

---

<div align="center">
<sub>Crafted with passion • Driven by Rust • Powered by AI Collaboration</sub>
</div>
