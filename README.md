# 🤖 AI Marketing Assistant

A modular Agentic AI system that automates marketing workflows—from research to content creation—for engineering communities and technical teams.

## 🌟 Purpose

Helps engineers:
- Increase market visibility  
- Showcase technical expertise  
- Build a strong digital presence  
- Engage with relevant audiences  

## 🚀 Project Overview

This app uses AI agents to:
- Streamline the marketing lifecycle  
- Automate strategy and content planning  
- Support personal branding and product evangelism 
## 🧩 Agents & Responsibilities

| Agent Name               | Description |
|--------------------------|-------------|
| `market_research`        | Conducts market research to identify trends, opportunities, and challenges. Analyzes client needs, competitor strategies, and market dynamics to inform decisions. |
| `prepare_marketing_strategy` | Develops a marketing strategy aligned with professional goals. Includes audience segmentation, positioning, messaging, and channel selection. |
| `create_content_calendar` | Generates a one-week content calendar with topics, formats, and publishing schedules. Aligns with strategic themes and campaign goals. |
| `prepare_post_drafts`    | Drafts engaging social media and email content based on the calendar. Ensures brand consistency and platform optimization. |

## 📦 Outputs

- ✅ Marketing Strategy Document
- ✅ 7-Day Content Calendar
- ✅ Drafts for:
  - LinkedIn posts
  - Twitter posts
  - Instagram posts
  - Email campaigns

## 🛠️ Tech Stack

- **CrewAI** for agent orchestration
- **Python** for pipeline integration  

## 📈 Business Impact

This system reduces manual overhead, improves strategic alignment, and accelerates content delivery. It empowers engineers to focus on innovation and community-building while agents handle the groundwork.

## 🧪 Getting Started

# Clone the repo
```bash
git clone <path>
````
 Ensure you have Python **>=3.10 <=3.13** installed on your system to install CrewAI.
# Install dependencies
```bash
pip install -r requirements.txt
````
### Customizing

**Add your `OPENAI_API_KEY`,`SERPER_API_KEY` into the `.env` file**

- Modify `main.py` to add custom inputs

# Run the crew
```bash
python main.py
````
OR<br>

run this from the root folder of your project:
    
```bash
crewai flow kickoff 
```

