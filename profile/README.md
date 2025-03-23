# 🌱 SUSTAIN: The Environmentally-Friendly AI 🌱

## Overview
SUSTAIN is an environmentally-friendly, token-optimized AI wrapper designed to reduce compute costs and increase productivity. By filtering out irrelevant words and phrases from prompts, SUSTAIN minimizes the number of tokens sent to and received from the AI, saving energy and boosting performance.

Our mission is to deliver a sustainable, high-efficiency alternative to major large language models (LLMs) while maintaining powerful AI-driven results.🔋

---

## Why SUSTAIN?

### **Environmental Sustainability**
- Traditional AI systems expend significant energy processing large amounts of token data, much of which is redundant or irrelevant (e.g., greetings, fillers, politeness).
- SUSTAIN significantly reduces token usage, minimizing the carbon footprint of AI queries.
- By promoting shorter, optimized inputs and outputs, SUSTAIN contributes to a greener AI ecosystem.

### **Enhanced Productivity**
- Get results faster with condensed, actionable responses.
- Eliminate unnecessary verbose outputs by default, with the option to expand details when needed.
- Powerful, straight-to-the-point professional AI assistant.

---

## Documentation

See the SUSTAIN documentation here: [SUSTAIN Docs](https://sustain.hashnode.space/)

---

## Features

### **1. Token Optimization Pipeline**
- Preprocesses user prompts to filter out unnecessary words (e.g., "Hello," "Thank you," etc.) and retain only the core intent.
  - Example Conversion:  
    - **Input:** "Could you kindly explain machine learning? Thank you!" 
    - **Refined input**: "explain machine learning"
- Uses Python's word2number module and intelligently strips detected math from a prompt to calculate locally instead of sending to AI, translating into 100% token savings for all math queries.
  - Example:
    - **Input:** "What's four times three"
    - **Refined input**: 4*3
  
### **2. Short-Form AI Responses**
- Limits responses to concise, actionable outputs using optimized `max_tokens` settings.
- Example Output:
  - **Refined input**: "explain machine learning"
  - **Output:** "Machine learning is a field of AI that trains computers to learn patterns from data."

### **3. Environmentally-Aware Feedback**
- Track token savings and display eco-friendly metrics to users.
- Example:
  - Token savings: 50%
  - You have saved: 0.0023 kWh of power and 0.0009 metric tons of CO₂ emissions

---

## Contributing
See our [Contributing](https://github.com/djleamen/SUSTAIN/blob/main/CONTRIBUTING.md) page.

![GitHub commit activity](https://img.shields.io/github/commit-activity/w/djleamen/SUSTAIN)

---

## Contact
For questions or suggestions, feel free to reach out to us:
- **Project Team:**
   - Klein Cafa kleinlester.cafa@ontariotechu.net
   - Tomasz Puzio tomasz.puzio@ontariotechu.net
   - DJ Leamen dj.leamen@ontariotechu.net
   - Juliana Losada Prieto juliana.losadaprieto@ontariotechu.net

---

Let’s build a more sustainable AI future together!
