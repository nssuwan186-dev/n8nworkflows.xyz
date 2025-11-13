# n8nworkflows.xyz

Standalone and versionable archive of n8n workflows from the official [n8n.io/workflows](https://n8n.io/workflows) website. This repository allows you to preserve, version, and reuse workflow templates in minimal format, ready to be imported offline.

[n8nworkflows.xyz](https://n8nworkflows.xyz)

---

## 📋 Table of Contents

- [Repository Structure](#-repository-structure)
- [Archived Workflow Format](#-archived-workflow-format)
- [Usage](#-usage)
- [Workflows Summary](#-workflows-summary)
- [License](#-license)

---

## 📁 Repository Structure

```
n8nworkflows.xyz/
├── archive/
│   └── workflows/
│       ├── workflow-name-id-1/
│       │   ├── readme.md
│       │   ├── workflow.json
│       │   ├── metadata.json
│       │   └── workflow-name-id-1.webp
│       ├── workflow-name-id-2/
│       │   └── ...
│       └── ...
└── README.md
```

Each workflow is isolated in its own folder to facilitate navigation, versioning, and individual import.

---

## 📄 Archived Workflow Format

Each workflow folder contains **exactly 4 files**:

| File | Description |
|:---|:---|
| **`readme.md`** | Complete workflow description in Markdown (original template's `readme` field) |
| **`workflow.json`** | Raw workflow export in JSON format, ready to be imported into n8n |
| **`metadata.json`** | Metadata: author (`user_*`), tags, creation date, public link to `https://n8n.io/workflows/<workflowId>` |
| **`<slug-and-id>.webp`** | Workflow screenshot (hero image from Supabase `worklowscreenshot` bucket) |

---



## 📚 Workflows Summary (50 workflows)

- [AI Agents can Create, Enrich leads with this Lemlist Tool MCP Server-5233](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/AI Agents can Create, Enrich leads with this Lemlist Tool MCP Server-5233)
- [AI Podcast Generator with RSS Feed & ElevenLabs Voice-5084](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/AI Podcast Generator with RSS Feed & ElevenLabs Voice-5084)
- [AI-Powered Knowledge Assistant using Google Sheets, OpenAI, and Supabase Vector Search-4477](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/AI-Powered Knowledge Assistant using Google Sheets, OpenAI, and Supabase Vector Search-4477)
- [Auto-Post Breaking News Content Using Perplexity AI to X (Twitter)-3822](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Auto-Post Breaking News Content Using Perplexity AI to X (Twitter)-3822)
- [Automate Lead Nurturing & Follow-Up with Gmail, Twilio SMS & GoHighLevel-4027](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Automate Lead Nurturing & Follow-Up with Gmail, Twilio SMS & GoHighLevel-4027)
- [Automate Shopify Orders from Airtable with Gmail Confirmations-9448](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Automate Shopify Orders from Airtable with Gmail Confirmations-9448)
- [AWS Azure GCP Multi-Cloud Cost Monitoring & Alerts for Budget Control-7374](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/AWS Azure GCP Multi-Cloud Cost Monitoring & Alerts for Budget Control-7374)
- [Baserow campaign database to Shopify with image upload & dynamic template update-2186](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Baserow campaign database to Shopify with image upload & dynamic template update-2186)
- [Bidirectional ClickUp Task & Google Calendar Sync with Multi-Calendar Routing-7871](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Bidirectional ClickUp Task & Google Calendar Sync with Multi-Calendar Routing-7871)
- [Build a RAG System with Automatic Citations using Qdrant, Gemini & OpenAI-5023](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Build a RAG System with Automatic Citations using Qdrant, Gemini & OpenAI-5023)
- [Build a Support Ticket Analytics Dashboard with ScrapeGraphAI, Google Sheets & Slack Alerts-6431](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Build a Support Ticket Analytics Dashboard with ScrapeGraphAI, Google Sheets & Slack Alerts-6431)
- [Check Email via AI agent with Mailcheck Tool MCP Server-5208](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Check Email via AI agent with Mailcheck Tool MCP Server-5208)
- [Check for preview for a link -935](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Check for preview for a link -935)
- [Complete Zendesk API Integration with MCP Server for AI Agents-5057](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Complete Zendesk API Integration with MCP Server for AI Agents-5057)
- [Convert n8n tags into folders and move workflows-3445](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Convert n8n tags into folders and move workflows-3445)
- [Create .SRT Subtitles & .LRC Lyrics from Audio with Whisper AI and GPT-5-nano-9589](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Create .SRT Subtitles & .LRC Lyrics from Audio with Whisper AI and GPT-5-nano-9589)
- [Create a Voice & Text Telegram Assistant with Lookio RAG and GPT-4.1-9870](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Create a Voice & Text Telegram Assistant with Lookio RAG and GPT-4.1-9870)
- [Create Images from Text Prompts using Flux Schnell and Replicate-6780](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Create Images from Text Prompts using Flux Schnell and Replicate-6780)
- [Daily Competitor Research Automation using SerpAPI, Google Sheets & Airtable-7313](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Daily Competitor Research Automation using SerpAPI, Google Sheets & Airtable-7313)
- [Daily Crypto Market Report with CoinGecko, WhatsApp, and Email Alerts-7729](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Daily Crypto Market Report with CoinGecko, WhatsApp, and Email Alerts-7729)
- [Daily MLB Pitcher vs. Batter Matchup Analysis with Google Sheets and Telegram-7252](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Daily MLB Pitcher vs. Batter Matchup Analysis with Google Sheets and Telegram-7252)
- [Display ServiceNow Incident Details in Slack using Slash Commands-2727](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Display ServiceNow Incident Details in Slack using Slash Commands-2727)
- [Explore n8n Nodes in a Visual Reference Library-3891](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Explore n8n Nodes in a Visual Reference Library-3891)
- [Export Cloudflare Domains with DNS Records and Settings to Google Sheets-4850](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Export Cloudflare Domains with DNS Records and Settings to Google Sheets-4850)
- [Extract Tasks from Telegram Messages to Notion using Gemini AI and Approvals-9271](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Extract Tasks from Telegram Messages to Notion using Gemini AI and Approvals-9271)
- [Find Recipes Using API Ninjas with Interactive Form Interface-7835](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Find Recipes Using API Ninjas with Interactive Form Interface-7835)
- [Full Blog Content Automation with GPT-4, Claude & Ghost CMS Publisher-7920](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Full Blog Content Automation with GPT-4, Claude & Ghost CMS Publisher-7920)
- [Generate Daily Sales Reports from Google Sheets with Formatted Email Summaries-6370](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Generate Daily Sales Reports from Google Sheets with Formatted Email Summaries-6370)
- [Generate Personalized and Aggregate Survey Reports with Jotform and Gemini AI-9484](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Generate Personalized and Aggregate Survey Reports with Jotform and Gemini AI-9484)
- [Get notified on Gmail, Telegram and Slack on new Stripe purchase-3410](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Get notified on Gmail, Telegram and Slack on new Stripe purchase-3410)
- [Gmail Cold Email Sequence with Google Sheets Tracking & Slack Notifications-5000](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Gmail Cold Email Sequence with Google Sheets Tracking & Slack Notifications-5000)
- [Gmail Email Auto-Organizer with Google Sheets Rules-8333](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Gmail Email Auto-Organizer with Google Sheets Rules-8333)
- [Google services (Sheets/Drive/Gmail) instead of 'Google Suite'-10387](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Google services (Sheets/Drive/Gmail) instead of 'Google Suite'-10387)
- [IP Reputation Check & SOC Alerts with Splunk, VirusTotal and AlienVault-6037](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/IP Reputation Check & SOC Alerts with Splunk, VirusTotal and AlienVault-6037)
- [Lead Analysis & Personalized Email Generation with OpenAI, Firecrawl & gotoHuman-8520](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Lead Analysis & Personalized Email Generation with OpenAI, Firecrawl & gotoHuman-8520)
- [Malicious File Detection & Response: Wazuh to VirusTotal with Slack Alerts-5997](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Malicious File Detection & Response: Wazuh to VirusTotal with Slack Alerts-5997)
- [Meta Ads Performance Analysis with GPT-4 & Gemini AI Comparisons-6545](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Meta Ads Performance Analysis with GPT-4 & Gemini AI Comparisons-6545)
- [Monitor Brand Mentions on X with Gemini AI Visual Analysis & Telegram Alerts-8355](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Monitor Brand Mentions on X with Gemini AI Visual Analysis & Telegram Alerts-8355)
- [Monitor Flight Price Drops and Send Email Alerts with SerpAPI and Gmail-6503](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Monitor Flight Price Drops and Send Email Alerts with SerpAPI and Gmail-6503)
- [Monitor Website Uptime with Gmail Alerts-5887](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Monitor Website Uptime with Gmail Alerts-5887)
- [Predict End of Utterance for smoother AI agent chats with Telegram and Gemini-5014](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Predict End of Utterance for smoother AI agent chats with Telegram and Gemini-5014)
- [Publish image & video to multiple social media (X, Instagram, Facebook and more)-3669](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Publish image & video to multiple social media (X, Instagram, Facebook and more)-3669)
- [Real-Time Crypto Price Bot for Telegram with Gemini AI & CoinGecko-9230](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Real-Time Crypto Price Bot for Telegram with Gemini AI & CoinGecko-9230)
- [Scrape Product Info from Website URLs in Google Sheets using Dumpling AI-6950](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Scrape Product Info from Website URLs in Google Sheets using Dumpling AI-6950)
- [Simple Google indexing Workflow in N8N-2123](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Simple Google indexing Workflow in N8N-2123)
- [Streamline data from an n8n form into Google Sheet, Airtable and Email Sending-2087](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Streamline data from an n8n form into Google Sheet, Airtable and Email Sending-2087)
- [Tesla Quant Technical Indicators Webhooks Tool-4095](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Tesla Quant Technical Indicators Webhooks Tool-4095)
- [Validate and Create LEDGERS Contacts from Google Sheets with Error Handling-4961](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Validate and Create LEDGERS Contacts from Google Sheets with Error Handling-4961)
- [⚡📽️ Ultimate AI-Powered Chatbot for YouTube Summarization & Analysis-2956](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/⚡📽️ Ultimate AI-Powered Chatbot for YouTube Summarization & Analysis-2956)
- [🚀 TikTok Video Automation Tool ✨ – Highly Optimized with OpenAI & Replicate-3004](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/🚀 TikTok Video Automation Tool ✨ – Highly Optimized with OpenAI & Replicate-3004)

---

## 🔗 Useful Links

- 🌐 [n8nworkflows.xyz website](https://n8nworkflows.xyz)
- 📖 [Official n8n Documentation](https://docs.n8n.io)
- 💬 [n8n Community](https://community.n8n.io)
- 🐙 [n8n on GitHub](https://github.com/n8n-io/n8n)

---

## 📝 License

This repository archives public workflows from [n8n.io/workflows](https://n8n.io/workflows). Each workflow retains its original license. Refer to individual metadata for more information.

The archiving code and repository structure are licensed under [MIT](LICENSE).

---

## ⚠️ Disclaimer

This project is **independent** and not officially affiliated with n8n. It is a personal initiative aimed at facilitating access to and preservation of public n8n workflows.

---

**Made with ❤️ for the n8n community**

