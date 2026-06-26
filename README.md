# n8n-automated-linkedin-poster
THIS IS A AI AUTOMATED WORKFLOW TO DIRECTLY POST THE ARTICLES BY SUMMARIZING THEM USING LLM'S IN THE FORM OF LINKED IN POST
# AI-Powered Article Summarizer & LinkedIn Poster

An automated workflow built in **n8n** that detects new or updated articles from a Google Sheet, leverages Google Gemini AI to summarize the content, and automatically publishes a polished post to LinkedIn.

## 🚀 How It Works
1. **Trigger:** A `Google Sheets Trigger` monitors a specific spreadsheet for new or updated article entries.
2. **AI Processing:** * The `Summarize Articles` chain utilizes the `Google Gemini Chat Model` to extract the core insights.
   * A secondary `Basic LLM Chain` refines the summary into a highly engaging social media post format.
3. **Action:** The `Create a post` node automatically shares the final generated draft directly to LinkedIn.

## 🛠️ Tech Stack
* **Automation Platform:** n8n
* **LLM / AI Model:** Google Gemini API
* **Integrations:** Google Sheets API, LinkedIn API

## 📋 How to Use
1. Import the provided `workflow.json` file into your own n8n instance.
2. Configure your credentials for the Google Sheets, Google Gemini, and LinkedIn nodes.
3. Activate the workflow!
