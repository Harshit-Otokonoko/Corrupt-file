# 🧩 XML Tag Processor

A Flask-based web application to analyze XML files for specific tag structures, detect faulty files, extract meter numbers, and visualize processing statistics. Designed for efficient bulk processing of XML datasets with real-time feedback and export capabilities.

---

## 🚀 Features

- ✅ Detects presence or absence of specific XML tags (`D1` to `D1300`)
- ⚠️ Identifies and flags faulty XML files (e.g., missing meter number `G1`)
- 📈 Generates live progress updates and visual summaries
- 📤 Exports faulty and normal file summaries to CSV
- 📂 Supports multiple file uploads via web UI
- 🧵 Multithreaded processing using `ThreadPoolExecutor`
- 🔒 Secure file uploads and error handling

---

## 📁 Tags Checked

```text
['D1', 'D2', 'D3', 'D4', 'D5', 'D6', 'D7', 'D8', 'D9', 'D10', 'D11', 'D1251', 'D1300']
