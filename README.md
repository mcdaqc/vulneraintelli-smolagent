---
title: First Agent Template
emoji: ⚡
colorFrom: pink
colorTo: yellow
sdk: gradio
sdk_version: 5.23.1
app_file: app.py
pinned: false
tags:
- smolagents
- agent
- smolagent
- tool
- agent-course
---

# Vulneraintelli SmolAgent

<img src="img/smolagent.png" alt="Vulneraintelli SmolAgent" width="110" align="left" style="margin-right: 20px;"/>

This project is currently under development. More information about its functionality and usage will be added soon.

<br clear="left"/>

## Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/mcdaqc/vulneraintelli-smolagent.git
cd vulneraintelli-smolagent
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Set up environment variables:
   - Copy `.env.template` to `.env`:
   ```bash
   cp .env.template .env
   ```
   - Edit `.env` and add your Hugging Face API token

5. Run the application:
```bash
python app.py
```

Check out the configuration reference at https://huggingface.co/docs/hub/spaces-config-reference
