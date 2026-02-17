---
title: SFDC AI Inspect - Salesforce Quick Inspector
tags:
  - Salesforce
  - ChromeExtension
  - productivity
  - Developertools
private: false
updated_at: '2026-02-17T19:26:25+09:00'
id: 604c6943c7b4e4fbc8e9
organization_url_name: null
slide: false
ignorePublish: false
---

# SFDC AI Inspect - Salesforce Quick Inspector

As a Salesforce developer or admin, do you often find yourself thinking: "I need to jump to that setup page," "I want to check hidden record values," or "I need to run SOQL quickly and update data"?

**SFDC AI Inspect** is a modern Chrome extension built to remove that friction and dramatically improve daily efficiency. It unifies multiple tools into one polished UI. Its biggest strength is an **AI Agent-first** experience that accelerates operations, development, and troubleshooting through natural conversation.

[![Available in the Chrome Web Store](https://img.shields.io/badge/Chrome_Web_Store-Available-blue?logo=google-chrome&logoColor=white)](https://chromewebstore.google.com/detail/sfdc-inspect-salesforce-q/kmcdodpdhoomiedbfdkeglhfebbjgolf)

---

## 🚀 8 AI-Centric Core Features

### 1. 🤖 AI Agent Workspace
**An AI workspace that lets you operate Salesforce with natural language.**
* **Natural Language for Salesforce:** Ask questions and get answers you can act on immediately.
* **75+ LLM Provider Ecosystem:** Connect through Models.dev to **75+** providers including GPT, Claude, Gemini, and more.
* **No Vendor Lock-in:** Switch providers/models anytime based on cost or performance.
* **Local Model Ready:** Supports local model workflows such as Ollama.
* **Custom MCP Integration:** Integrates with a custom-built Salesforce MCP server, [salesforce-mcp](https://github.com/exiahuang/salesforce-mcp), making AI Agent capabilities easy to extend.
* **Easy to Extend:** MCP-based architecture allows incremental expansion for future internal requirements and workflows.
* **Language-aware Replies:** AI responses follow your configured app language.
* **Easy Setup:** Configure once, then reuse across AI-enabled modules.

![sfdc-ai-inspect-agent](https://github.com/exiahuang/qiita-content/blob/main/public/images/sfdc-ai-inspect/sfdc-ai-inspect-agent.gif?raw=true)

![sfdc-ai-run-test-class](https://github.com/exiahuang/qiita-content/blob/main/public/images/sfdc-ai-inspect/sfdc-ai-run-test-class.gif?raw=true)

### 2. 📊 Data Expert
**An Excel-like UI that accelerates data operations with AI support.**
* **Excel-like UI:** Query and manage data in a clean, responsive table.
* **Bulk Operations:** Insert, Update, Upsert, and Delete records efficiently.
* **SOQL Helper:** Build SOQL faster with formatting and field helpers.
* **AI to SOQL:** Generate SOQL from natural language, so even teammates unfamiliar with SOQL can maintain data safely and quickly.
* **Export:** Download results to CSV for sharing and analysis.

![sfdc-ai-soql](https://github.com/exiahuang/qiita-content/blob/main/public/images/sfdc-ai-inspect/sfdc-ai-soql.gif?raw=true)

### 3. 📜 Log Expert + AI Analysis
**Shorten log investigations and identify root causes faster with AI.**
* **Real-time Monitoring:** Fetch and review recent debug logs quickly.
* **Advanced Filtering:** Narrow logs by user, status, time, and more.
* **AI Summary:** Let AI highlight likely root causes, supporting evidence, and remediation steps.

![sfdc-ai-log-analysis](https://github.com/exiahuang/qiita-content/blob/main/public/images/sfdc-ai-inspect/sfdc-ai-log-analysis.gif?raw=true)

### 4. 🛠️ Architecture & Documentation
**Use AI to understand system design and produce architecture documentation faster.**
* **Flow Analysis:** Explore flow logic with clearer structure.
* **AI Architecture Assistance:** Analyze object relationships with LLMs and generate architecture-oriented outputs.
* **Doc Assistance:** Create architecture documentation with AI support.


### 5. 🚀 Quick Navigation Palette
* **Hotkey:** Press `Ctrl+I` (`Cmd+I` on Mac) anywhere in Salesforce.
* **Search & Jump:** Instantly find setup links, objects, Apex classes, pages, and tools.
* **Simple Workflow:** Type a keyword and open what you need in seconds.

![SFDC AI Inspect](https://lh3.googleusercontent.com/E_f5_akIM7dXnMbtYxCcIJzm5SNG0glqH69JzzgxbB3tSSbqp1qI4MNFy3eolYz59oznhoxhoQxuwNbZYDAd_7M8AA=s1280-w1280-h800)


### 6. 🔍 Record Quick Inspector
* **Instant Access:** Open record details directly from the current page.
* **Deep Insight:** View field values, including important system fields.
* **Quick Edit:** Update values without navigating through multiple Salesforce screens.

### 7. 🔌 REST Tool
* **Direct API Testing:** Send REST requests to Salesforce endpoints quickly.
* **Fast Debugging:** Inspect request/response payloads in one place.
* **Practical for Daily Work:** Great for API validation, integration checks, and troubleshooting.

![sfdc-rest-api](https://github.com/exiahuang/qiita-content/blob/main/public/images/sfdc-ai-inspect/sfdc-rest-api.gif?raw=true)

### 8. 🕸️ ER Diagram Generator
* **Visualize Data Models:** Generate ER diagrams from selected Salesforce objects.
* **Mermaid-based Output:** Produce clean Mermaid diagrams that are easy to review and share.
* **Architecture Friendly:** Useful for design reviews and documentation.

![SFDC AI Inspect](https://lh3.googleusercontent.com/Jjl1tqKuEhb_KVqXCIXx24iqgQM3IW7K5GAjn5rvbIL3bdnj89u8xg8rAGVoMy7ZNEz0OYw4ShHfbSTJ5Kwb0MSt=s1280-w1280-h800)

---

## 👔 For Managers and Team Leads: Why Adopt It

SFDC AI Inspect is not only for individual developers, but also a practical choice for team-wide adoption.

1. **Higher productivity (ROI)**:
   By reducing time spent searching for hidden fields or opening separate SOQL tools, teams can focus on core business logic and delivery.
2. **Knowledge visibility**:
   ER diagrams and architecture outputs help reduce knowledge silos and speed up onboarding for new members.
3. **Lower operational cost**:
   Consolidating multiple add-ons into one tool reduces learning overhead and tool management complexity.

---

## 🔒 Security and Privacy You Can Trust

Designed for enterprise usage, SFDC AI Inspect prioritizes security.

* **Local-first execution:** Processing is done in the browser.
* **No external data transfer:** Retrieved data and credentials are not stored on or sent to external servers.
* **Direct communication only:** The extension communicates directly only with your authenticated Salesforce org.
* **Standard APIs:** Uses Salesforce standard APIs and safe session handling (`chrome.cookies`).

---

## 🛠 Installation

Install easily from the Chrome Web Store:

👉 [**Install SFDC AI Inspect**](https://chromewebstore.google.com/detail/sfdc-inspect-salesforce-q/kmcdodpdhoomiedbfdkeglhfebbjgolf)

---

## 🎥 Demo Video
[Watch SFDC AI Inspect in action](https://www.youtube.com/watch?v=rSYBvuoNOyY)

<iframe width="560" height="315" src="https://www.youtube.com/watch?v=rSYBvuoNOyY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

## 🚀 Built With AI + Feedback
This tool was developed rapidly with modern AI, including **ChatGPT** and **Gemini**.

It also uses a custom-built MCP server as the AI Agent foundation:
* **Salesforce MCP Server**: [https://github.com/exiahuang/salesforce-mcp](https://github.com/exiahuang/salesforce-mcp)
* **Approach**: Using a custom MCP base makes extension, maintenance, and feature evolution easier for real business workflows.

* **Author**: exia.huang ([HomePage](https://salesforcexytools.com/))
* **Feedback**: If you find a bug or have feature ideas, please open an issue:

👉 [**Submit feedback on GitHub Issues**](https://github.com/exiahuang/sfdc-inspect/issues)

---

## Closing
Salesforce administration and development are getting more complex as the platform evolves. SFDC AI Inspect is designed to turn that complexity into simplicity and save your team valuable time.

Try it out and share your feedback.

#Salesforce #SalesforceDeveloper #productivity #ChromeExtension #DX

