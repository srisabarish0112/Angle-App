# Angle

### Turn trending conversations into messages your customers want to open.

**Angle** is a marketing content studio that connects **topic discovery, brand context, and content creation** in one workspace.

Explore a topic, choose your voice, and create **push notifications and marketing emails** with live previews.

---

## 💡 The Problem

Discovering a trend is easy. Knowing **whether it matters to your audience—and what your brand should say about it—is harder**.

Marketing teams often move between research, writing, design, and delivery tools before a single message is ready.

**Angle brings that journey into one connected experience.**

---

## ✨ Features

### 🔎 Trend Radar

Discover **24 sample topics** across:

- **AI**
- **Funny & Internet Culture**
- **Food**
- **Entertainment**
- **Lifestyle**
- **Travel**

Every topic includes:

- A **unique, topic-related illustration**
- A brief explaining the content opportunity
- A sample push notification
- Links to explore related conversations
- A direct action to **create content**

Search, filter, and bookmark topics for later.

### ✍️ Content Builder

Selecting a topic immediately prepares **email and push notification drafts**.

Choose from three writing styles:

| Style | Purpose |
| --- | --- |
| **Professional** | Clear, polished communication |
| **Friendly** | Warm, conversational messages |
| **Funny** | Playful copy with personality |

Edit the **title, message, button text, destination URL, and image visibility**.

### 📱 Live Previews

See your content update as you type:

- **Push notifications** in a phone lock-screen preview
- **Marketing emails** in an inbox-style preview
- Topic illustrations included in both formats
- Simulated button interactions

### 🎨 Brand Kit

Maintain the context behind your messaging:

- Company name and description
- Target audience
- Value proposition
- Brand voice and color
- Sender information
- Default call to action

The prototype uses selected Brand Kit fields in its sample copy and previews.

### 💾 Save & Export

- Save drafts locally in your browser
- Reopen saved work inside Content Builder
- Copy message content
- Export emails as **HTML**
- Export push notifications as **JSON**

### 📊 Performance

Explore a sample dashboard showing how **delivery, engagement, and conversions** could be monitored.

---

## 🤖 Designed for an Agent-Powered Workflow

Angle’s proposed backend connects five specialized agents:

| Agent | Responsibility |
| --- | --- |
| **Trend Discovery Agent** | Checks configured sources every minute, identifies new topics, and removes duplicates |
| **Relevance Agent** | Evaluates topics against company details, offerings, and target audiences |
| **Content Agent** | Creates brand-relevant email and push copy in the selected tone |
| **Audience & Delivery Agent** | Selects eligible audience segments and coordinates approved messages through delivery platforms |
| **Performance Agent** | Updates the analytics dashboard, summarizes results, and recommends improvements |

**The intended flow:**

Discover → Evaluate relevance → Draft → Review → Deliver → Learn

The one-minute interval is a proposed source-check schedule, subject to provider limits—not a guarantee of new information every minute.

---

## 🚀 Try the Prototype

1. Download or clone this repository.
2. Open **`angle-studio-unique-illustrations.html`** in a modern browser.
3. Explore a topic in **Trend Radar**.
4. Select **Create content**.
5. Choose a channel and writing style.
6. Edit, preview, save, or export your message.

**No installation, build step, API key, or backend is required.**

All illustrations are embedded in the HTML file. External research links require internet access.

---

## 🛠️ Built With

- **HTML**
- **CSS**
- **Vanilla JavaScript**
- **Browser localStorage**
- **Embedded AI-generated illustrations**

The entire prototype is packaged in **one HTML file**, with no external runtime libraries or remote image dependencies.

---

## 📌 Current Status

**Angle is currently an interactive frontend prototype.**

### Implemented

- Topic browsing, filtering, and search
- Unique illustrations for all 24 topics
- Topic briefs and related research links
- Prefilled sample email and push copy
- Three writing styles
- Editable live previews
- Brand Kit configuration
- Local draft saving and content exports
- Sample performance dashboard

### Planned Backend Capabilities

- Live trend and news ingestion
- Agent-based relevance assessment
- LLM-generated content using full company and audience context
- Audience segmentation
- Approved email and push delivery
- Real engagement tracking and performance analysis

> **Topics, copy, and analytics currently use sample data.**
> Research links open related searches rather than verified trend-origin citations.
> The prototype does not send emails or push notifications.

---

## 🔭 What’s Next

- Validate the workflow with marketing teams.
- Measure **time to an approved draft** and **editing effort**.
- Add verified sources, freshness checks, and relevance scoring.
- Connect the agent workflow with review and approval controls.
- Integrate audience segmentation and delivery platforms.
- Use actual engagement data to improve future content.

---

## 💾 Storage

Drafts and settings are stored in your browser’s **localStorage**.

They are **not synchronized across devices**. Export important work before clearing browser data.
