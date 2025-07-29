# Marathi-News-Lexicon
# 📊 Improved NLP Flowchart for Marathi Sentiment Lexicon Development

## 🔁 Complete Workflow

```
🟢 START
   |
   ▼
🟩 PHASE I: Web-Based Crowdsourcing System
   ├── 👤 User Management
   │     ├── 🔐 User Registration/Login
   │     └── 🛡️ Role Assignment (Admin / Annotator)
   |
   └── 🗂️ Task Management
         ├── 🆙 Admin Uploads Marathi Sports News Sentences
         ├── 🔀 Random Distribution to Annotators
         └── 📝 Annotators Submit Sentiment (👍 / 👎 / 😐)
   |
   ▼
🟦 Data Collection Completed
   |
   ▼
🟨 PHASE II: Annotation Analysis & Lexicon Development
   ├── 📏 Step 1: Inter-Annotator Agreement (IAA)
   │     ├── 🧮 Fleiss’ Kappa
   │     └── 📐 Krippendorff’s Alpha
   |
   ├── 🤖 Step 2: Machine Learning Integration
   │     ├── 📥 Use Pre-trained Models (MahaRoBERTa, MuRIL, etc.)
   │     └── ⚖️ Compare ML vs Annotator using Cohen’s Kappa
   |
   ├── ⚙️ Step 3: Hybrid Label Aggregation
   │     ├── 🗳️ Majority Voting
   │     └── 🧠 Combine Model Confidence + Annotator Reputation
   |
   ├── 📚 Step 4: Marathi Sentiment Lexicon (MSL) Development
   │     ├── 🏷️ Extract Sentiment Words/Phrases
   │     ├── ➕ Assign Polarity (+1, 0, -1)
   │     └── 🧾 Tag POS, Intensifiers, Negators
   |
   └── 🔄 Step 5: Iterative Updates
         ├── ➕ Add New Terms
         └── ✅ Revalidate Scores Periodically
   |
   ▼
📤 Export Lexicon to NLP Systems
   |
   ▼
🔴 END
```
