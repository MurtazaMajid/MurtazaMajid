<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=venom&color=gradient&customColorList=24,20,14&height=200&section=header&text=Murtaza%20Majid&fontSize=58&fontColor=ffffff&fontAlignY=38&desc=data%20scientist%20·%20ml%20engineer%20·%20systems%20shipper&descAlignY=62&descSize=16&animation=fadeIn" />
</div>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&pause=1500&color=BD93F9&center=true&vCenter=true&width=820&lines=%24+jupyter+notebook+--profile=murtaza-majid;%24+training+models+that+actually+make+it+to+production;%24+import+rigour+as+r+%23+from+experiments+to+systems;%24+%E2%9D%AF+ready" />
</div>

<div align="center">

[![visits](https://komarev.com/ghpvc/?username=MurtazaMajid&label=notebook%20views&color=bd93f9&style=flat-square&labelColor=282a36)](https://github.com/MurtazaMajid)
[![followers](https://img.shields.io/github/followers/MurtazaMajid?label=followers&style=flat-square&color=ff79c6&labelColor=282a36)](https://github.com/MurtazaMajid)
[![hackathon](https://img.shields.io/badge/Air%20MLX%202025-WINNER%20%E2%97%89%20RMSE%200.13-ffb86c?style=flat-square&labelColor=282a36)](https://github.com/MurtazaMajid/Parking-Violation-Prediction)
[![status](https://img.shields.io/badge/status-open%20to%20DS%20%2F%20MLE%20roles-50fa7b?style=flat-square&labelColor=282a36)](mailto:<<your-email@gmail.com>>)

</div>

---

### `In [1]:` &nbsp; whoami

```python
me = {
    "name":          "Murtaza Majid",
    "role":          ["data scientist", "ml engineer"],
    "based_in":      "<<Your City>>, Pakistan",
    "studying":      "BS Data Science · <<Your University>>",
    "specialises":   ["computer vision", "NLP / LLMs", "tabular ML", "end-to-end deployment"],
    "philosophy":    "a model that doesn't ship is a model that doesn't matter",
    "looking_for":   "Data Science / ML Engineer roles · summer 2026 onwards",
}
```

### `Out[1]:`

> Final-year DS student who treats every project as a system, not a notebook.
> 5 deployed full-stack apps, 1 hackathon win, and an active FYP shipping computer vision in production.

---

## `[ training_run_log ]`

A summary of completed runs and current experiments.

| run | project | metric | result | status |
|---|---|---|---|---|
| `001` | Parking Violation Risk · Air MLX 2025 | RMSE | **0.13** &nbsp;🥇 *winner* | ✅ shipped |
| `002` | Apple FHI Forecasting | RMSE *(zero leakage)* | **0.0971** *(ARIMAX)* | ✅ live api + web |
| `003` | Campbell's AI Marketing Hub | Churn AUC | **0.84** *(1.5k segmented)* | ✅ live |
| `004` | MailIntel · Email Classifier | Accuracy | **0.81** *(LSTM head-to-head)* | ✅ live |
| `005` | SentinelAI · Weapon Detection | mAP@50 *(YOLOv8, 8k imgs)* | live cam + static | ✅ live |
| `006` | AstroLifeQuest · Exoplanet Habitability | XGBoost + SHAP | physics-informed score | ✅ live |
| `007` | TheDocumentTimes · BERT vs LSTM | Accuracy *(20 Newsgroups)* | fine-tuned BERT | ✅ live |
| `008` | **AutoCop · AI Traffic Monitoring** *(FYP)* | Detection acc. | **95%+** *(YOLOv11, 6+ violations)* | 🔧 in progress |

---

## `[ pinned_experiments ]`

### `experiment_002` &nbsp;·&nbsp; Apple FHI Forecasting with ARIMAX & LSTM

> Forecasting Apple's financial health from a custom index built from 7 data sources. 4 models trained head-to-head, FinBERT for sentiment, SHAP for explainability, deployed end-to-end.

```yaml
data_sources:    7
models_trained:  [ARIMAX × 2, LSTM × 2]
best_loss:       0.0971  # RMSE, ARIMAX
explainability:  SHAP + FinBERT sentiment
deployment:      [HuggingFace Spaces (API), Vercel (UI)]
honesty_check:   zero data leakage  ✓
```

**→** [`code`](https://github.com/MurtazaMajid/Apple-FHI-Forecasting-with-ARIMA-LSTM) &nbsp;·&nbsp; [`live demo`](https://apple-fhi-forecasting-with-arima-lstm.vercel.app/)

---

### `experiment_003` &nbsp;·&nbsp; Campbells AI and Marketing Hub

> End-to-end marketing intelligence platform: predict who churns, segment who's left, listen to what they're saying, and auto-write the message that brings them back.

```yaml
churn_model:        XGBoost · AUC 0.84
segmentation:       RFM KMeans · 1,500+ customers
sentiment_engine:   Aspect-Based Sentiment Analysis (ABSA)
generation_engine:  LLaMA 3.3-70B via Groq · SMS / email / push
stack:              [FastAPI, Supabase, React, Groq API]
```

**→** [`code`](https://github.com/MurtazaMajid/Campbells-AI-and-Marketing-Hub) &nbsp;·&nbsp; [`live demo`](https://campbells-ai-hub.vercel.app/)

---

### `experiment_005` &nbsp;·&nbsp; SentinelAI · Real-Time Weapon Detection

> YOLOv8 trained on 8,000 Roboflow-annotated images. Identifies weapons in static images and live camera feeds. Deployed for public-safety surveillance use cases.

```yaml
model:        YOLOv8 (custom-trained)
dataset:      8,000 images · Roboflow-annotated
modes:        [static images, live camera feed]
use_case:     real-time public-safety surveillance
deployment:   live web app
```

**→** [`code`](https://github.com/MurtazaMajid/SentinelAI-Real-Time-Weapon-Detection-System) &nbsp;·&nbsp; [`live demo`](https://sentinel-ai-real-time-weapon-detection.vercel.app)

---

### `experiment_006` &nbsp;·&nbsp; AstroLifeQuest · Exoplanet Habitability

> Predicts which planets in NASA's Kepler KOI dataset could support life. Combines a physics-informed scoring engine with a tuned XGBoost regressor and SHAP explainability.

```yaml
dataset:        NASA Kepler KOI
scoring:        physics-informed habitability engine
model:          tuned XGBoost regressor
explainer:      SHAP
deployment:     FastAPI on HF Spaces + Next.js on Vercel
```

**→** [`code`](https://github.com/MurtazaMajid/AstroLifeQuest-Predicting-Planets-Habitability) &nbsp;·&nbsp; [`live demo`](https://astro-life-quest.vercel.app/)

---

### `experiment_004` &nbsp;·&nbsp; MailIntel · Email Classification Pipeline

> Production-style NLP pipeline on 5,000+ real Gmail messages. Naive Bayes vs SVM vs LSTM run head-to-head under identical conditions. LSTM wins. Full 13-stage cleaning pipeline + TF-IDF + deployed app.

```yaml
dataset:           5,000+ real Gmail messages · 5 categories
models_compared:   [Naive Bayes, SVM, LSTM]
winner:            LSTM · 0.81 accuracy
preprocessing:     13-stage cleaning + TF-IDF features
deployment:        end-to-end live app
```

**→** [`code`](https://github.com/MurtazaMajid/MailIntel-Email-Classification-App) &nbsp;·&nbsp; [`live demo`](https://mailntel.vercel.app)

---

### `experiment_007` &nbsp;·&nbsp; TheDocumentTimes · BERT vs LSTM News Classifier

> Fine-tuned BERT alongside an LSTM baseline on the 20 Newsgroups corpus. Wrapped in a clean web app where users paste any text and get a category prediction in real time.

```yaml
dataset:       20 Newsgroups
models:        [fine-tuned BERT, LSTM baseline]
interface:     paste-any-text → real-time category prediction
deployment:    live web app
```

**→** [`code`](https://github.com/MurtazaMajid/TheDocumentTimes-Document-Categorization-App) &nbsp;·&nbsp; [`live demo`](https://bert-news-classification.vercel.app/)

---

## `[ imports ]`

The libraries and tools I actually reach for:

```python
# core
import python, sql, typescript, javascript

# classical ml
from sklearn import *
import xgboost, lightgbm

# deep learning
import torch, tensorflow
from transformers import BERT, FinBERT
from ultralytics import YOLOv8, YOLOv11

# data + interpretation
import pandas, numpy, matplotlib, seaborn
import nltk, spacy
import shap

# llm / generative
from groq import LLaMA_3_3_70B

# shipping
from fastapi import FastAPI
from huggingface_hub import Spaces
import nextjs, react, vercel
import supabase, postgresql
```

---

## `[ wandb_dashboard ]`

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=MurtazaMajid&show_icons=true&theme=dracula&hide_border=true&bg_color=282a36&title_color=bd93f9&icon_color=ff79c6&text_color=f8f8f2&count_private=true&include_all_commits=true" />
<img height="170" src="https://github-readme-streak-stats.herokuapp.com/?user=MurtazaMajid&theme=dracula&hide_border=true&background=282a36&stroke=bd93f9&ring=ff79c6&fire=ffb86c&currStreakLabel=bd93f9&sideNums=f8f8f2&currStreakNum=ff79c6&dates=f8f8f2&sideLabels=bd93f9" />

</div>

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MurtazaMajid&layout=compact&theme=dracula&hide_border=true&bg_color=282a36&title_color=bd93f9&text_color=f8f8f2&langs_count=10" />
<img height="170" src="https://github-readme-activity-graph.vercel.app/graph?username=MurtazaMajid&bg_color=282a36&color=bd93f9&line=ff79c6&point=ffb86c&area=true&hide_border=true&custom_title=commit%20activity" />

</div>

---

## `[ next_epoch ]` &nbsp;·&nbsp; what I'm training for in 2026

```python
goals_2026 = [
    "ship AutoCop FYP to production",
    "land a Data Science / ML Engineer role",
    "publish 1 deployed app per quarter",
    "climb Kaggle leaderboards (target: top 10% in a real comp)",
    "contribute meaningfully to one open-source ML library",
]

current_focus = "AutoCop · YOLOv11 + FastAPI + Postgres + Next.js"
```

---

## `[ callback_registry ]`

```python
contact = {
    "linkedin":  "linkedin.com/in/<<your-linkedin-handle>>",
    "portfolio": "<<your-portfolio-url>>",
    "kaggle":    "kaggle.com/<<your-kaggle-handle>>",
    "email":     "<<your-email@gmail.com>>",
    "github":    "github.com/MurtazaMajid",  # you're here
}
```

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-bd93f9?style=flat-square&logo=linkedin&logoColor=white&labelColor=282a36)](https://linkedin.com/in/<<your-linkedin-handle>>)
[![Portfolio](https://img.shields.io/badge/Portfolio-ff79c6?style=flat-square&logo=firefox&logoColor=white&labelColor=282a36)](https://<<your-portfolio-url>>)
[![Kaggle](https://img.shields.io/badge/Kaggle-8be9fd?style=flat-square&logo=kaggle&logoColor=black&labelColor=282a36)](https://kaggle.com/<<your-kaggle-handle>>)
[![Email](https://img.shields.io/badge/Email-ffb86c?style=flat-square&logo=gmail&logoColor=white&labelColor=282a36)](mailto:<<your-email@gmail.com>>)

</div>

---

<div align="center">
  <sub><i>fit · predict · deploy · repeat</i></sub>
</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=24,20,14&height=80&section=footer" />
</div>
