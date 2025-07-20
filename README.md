# 📊 AI-Powered Data Analysis & Report Generator 🤖📈

## 🚀 Project Overview

This project automates monthly sales data analysis and generates detailed PDF reports using a powerful AI language model. Leveraging Hugging Face’s **SmolLM3-3B** model, raw sales data is interpreted to extract trends and insights, which are then presented in a visually appealing, easy-to-understand report.

## 💻 Colab Notebook

Try it yourself!
[Open the AI-Powered Data Analysis and Report Generation notebook](https://colab.research.google.com/drive/1ScrestmhiTgrC4kUF7prMmaekRcBIL7w?usp=sharing) 🚀

---

## ❓ Why This Project?

Businesses deal with large amounts of sales data, but manual analysis is slow and error-prone. This project automates data analysis using AI to save time, highlight key trends, and generate clear, professional reports—helping teams make faster, smarter decisions.

---

## 🛠️ Technologies Used

* **Python 3.8+** — Programming language
* **pandas** — Data manipulation and analysis
* **transformers (Hugging Face)** — AI language model interface
* **WeasyPrint** — HTML to PDF conversion
* **matplotlib** — Data visualization (optional for graphs)

---

## ⚙️ How It Works

1. **Load Data**: Monthly sales data is loaded and organized using pandas.
2. **AI Analysis**: The **SmolLM3-3B** model analyzes the data to identify key trends, anomalies, and summary points.
3. **Generate HTML Report**: The analysis summary and data tables are formatted into an HTML template.
4. **Convert to PDF**: WeasyPrint converts the HTML report into a polished PDF file, complete with timestamps in the filename.
5. **Output**: The final PDF report is saved locally and ready for sharing.

---

## 📁 Example Report Output

The file named ai_sales_report_20250718_150046.pdf in the GitHub repository is a sample report. The report includes a summary of sales trends, key insights, and tabular data.

## AI-Sales-Sample-Report-Screenshot

![AI-Sales-Sample-Report-Screenshot](https://github.com/ctntrk/AI-Powered-Data-Analysis-and-Report-Generator/blob/main/AI-Sales-Sample-Report-Screenshot.png)

---

## 📝 Notes

* For best performance, use a GPU-enabled environment (`device=0`).
* WeasyPrint might require system dependencies such as `libffi` and `cairo`.
* Customize the HTML template to match your branding or additional data.

---

## 📜 License

This project is licensed under the MIT License.
