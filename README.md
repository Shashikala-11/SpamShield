 <div align="center">

<img src="https://capsule-render.vercel.app/api?type=rounded&color=gradient&customColorList=12,14,20,24,30&height=230&section=header&text=SpamShield&fontSize=75&fontColor=ffffff&animation=fadeIn&desc=Smart%20SMS%20Spam%20Detection%20Platform&descSize=20&descAlignY=75" width="100%" />

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=700&size=23&duration=2500&pause=800&color=8B5CF6&center=true&vCenter=true&width=750&lines=Say+Goodbye+to+Unwanted+Messages+%F0%9F%91%8B;Smarter+SMS+Classification+%F0%9F%A4%96;Machine+Learning+Meets+NLP+%E2%9C%A8;Detect+Spam.+Keep+Your+Inbox+Clean.+%F0%9F%92%99" />

<br/><br/>

<img src="https://img.shields.io/badge/Machine%20Learning-8B5CF6?style=for-the-badge&logo=googlescholar&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
<img src="https://img.shields.io/badge/MLOps-06B6D4?style=for-the-badge" />

<br/><br/>

<a href="https://github.com/Shashikala-11/SpamShield/stargazers"><img src="https://img.shields.io/github/stars/Shashikala-11/SpamShield?style=social" /></a>
<a href="https://github.com/Shashikala-11/SpamShield"><img src="https://img.shields.io/github/last-commit/Shashikala-11/SpamShield?style=flat-square&color=8B5CF6" /></a>
<a href="https://github.com/Shashikala-11/SpamShield"><img src="https://img.shields.io/github/repo-size/Shashikala-11/SpamShield?style=flat-square&color=06B6D4" /></a>

<br/><br/>

**✨ Intelligent SMS Classification | NLP | Random Forest | DVC | DVCLive**

</div>

---

<div align="center">

## 💌 A Cleaner Inbox Starts Here!

<img src="https://img.shields.io/badge/INCOMING%20MESSAGE-8B5CF6?style=for-the-badge&labelColor=F3E8FF" />

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=600&size=18&duration=2200&pause=700&color=EC4899&center=true&vCenter=true&width=600&lines=Congratulations!+You+won+a+prize...;URGENT!+Claim+your+reward+now!;Wait...+Could+this+be+SPAM%3F+%F0%9F%A4%94" />

<br/><br/>

<img src="https://img.shields.io/badge/🚨%20SPAM%20DETECTED-FF4B6E?style=for-the-badge" />

<br/>

<img src="https://img.shields.io/badge/LEGITIMATE%20MESSAGE-16C79A?style=for-the-badge" />

</div>

## 🌈 What is SpamShield?

**SpamShield** is a Machine Learning-powered SMS Spam Detection application that classifies incoming text messages into two categories:

<table>
<tr>
<td width="50%" align="center">

<img src="https://img.shields.io/badge/SPAM-FF4B6E?style=for-the-badge" />

### 🚨 Unwanted Messages

Identifies unwanted or spam messages using a trained classification model.

</td>
<td width="50%" align="center">

<img src="https://img.shields.io/badge/HAM-16C79A?style=for-the-badge" />

### 💚 Legitimate Messages

Recognizes genuine, non-spam messages.

</td>
</tr>
</table>

The application combines text preprocessing, TF-IDF feature extraction and Random Forest classification with an interactive Streamlit interface.

It also explores reproducible machine learning workflows using DVC and DVCLive.

---

## 🎨 Features at a Glance

<table>
<tr>
<td align="center" width="33%">

<img src="https://img.shields.io/badge/01-8B5CF6?style=for-the-badge" />

### 🧠 Smart Classification

Random Forest-based SMS classification.

</td>
<td align="center" width="33%">

<img src="https://img.shields.io/badge/02-06B6D4?style=for-the-badge" />

### 🔤 NLP Processing

TF-IDF text feature extraction.

</td>
<td align="center" width="33%">

<img src="https://img.shields.io/badge/03-F59E0B?style=for-the-badge" />

### ⚡ Interactive UI

Streamlit-based message analysis.

</td>
</tr>
<tr>
<td align="center">

<img src="https://img.shields.io/badge/04-EC4899?style=for-the-badge" />

### 📊 Model Insights

Classification and probability estimates.

</td>
<td align="center">

<img src="https://img.shields.io/badge/05-10B981?style=for-the-badge" />

### 🔄 Reproducibility

DVC pipeline orchestration.

</td>
<td align="center">

<img src="https://img.shields.io/badge/06-6366F1?style=for-the-badge" />

### 📈 Experiment Tracking

DVCLive experiment metrics.

</td>
</tr>
</table>

---

## 🪄 How SpamShield Works

<div align="center">

<img src="https://img.shields.io/badge/01-INPUT-8B5CF6?style=for-the-badge" />
<img src="https://img.shields.io/badge/02-PROCESS-06B6D4?style=for-the-badge" />
<img src="https://img.shields.io/badge/03-PREDICT-EC4899?style=for-the-badge" />

</div>

```mermaid
flowchart TD
    A(["💌 SMS Message"]) --> B["🧹 Text Preprocessing"]
    B --> C["🔤 TF-IDF Vectorization"]
    C --> D["🌳 Random Forest Classifier"]
    D --> E{"Classification"}
    E -->|Spam| F["🚨 Spam Detected"]
    E -->|Ham| G["💚 Legitimate Message"]
    F --> H["📊 Prediction Results"]
    G --> H

    style A fill:#EDE9FE,stroke:#8B5CF6,color:#4C1D95
    style B fill:#CFFAFE,stroke:#06B6D4,color:#164E63
    style C fill:#DBEAFE,stroke:#3B82F6,color:#1E3A8A
    style D fill:#FCE7F3,stroke:#EC4899,color:#831843
    style F fill:#FFE4E6,stroke:#F43F5E,color:#881337
    style G fill:#D1FAE5,stroke:#10B981,color:#064E3B
    style H fill:#FEF3C7,stroke:#F59E0B,color:#78350F
```

### 🔬 Machine Learning Pipeline

| Stage | Description |
|:---|:---|
| 📥 Data Ingestion | Load and organize SMS dataset |
| 🧹 Preprocessing | Clean text and prepare data |
| 🔤 Feature Engineering | Convert text into TF-IDF features |
| 🌳 Model Building | Train Random Forest classifier |
| 📊 Evaluation | Evaluate classification performance |
| 📈 Tracking | Record metrics with DVCLive |

---

## 🧩 Technology Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,pandas,numpy,sklearn,git,github,azure&theme=light&perline=7" />

<br/><br/>

<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
<img src="https://img.shields.io/badge/DVC-945DD6?style=for-the-badge&logo=dvc&logoColor=white" />
<img src="https://img.shields.io/badge/DVCLive-06B6D4?style=for-the-badge" />
<img src="https://img.shields.io/badge/PyYAML-CB171E?style=for-the-badge" />

</div>

---

## 🏗️ Architecture

```mermaid
flowchart TB
    A["📂 SMS Dataset"] --> B["Data Ingestion"]
    B --> C["Preprocessing"]
    C --> D["Feature Engineering"]
    D --> E["Random Forest"]
    E --> F["Evaluation"]
    F --> G["Model Artifacts"]

    H["⚙️ params.yaml"] --> B
    H --> D
    H --> E

    I["DVC"] -.-> B
    I -.-> C
    I -.-> D
    I -.-> E
    I -.-> F

    F --> J["DVCLive"]

    G --> K["Streamlit Application"]
    L["User Input"] --> K
    K --> M["Spam / Ham Prediction"]

    style A fill:#EDE9FE,stroke:#8B5CF6,color:#4C1D95
    style E fill:#FCE7F3,stroke:#EC4899,color:#831843
    style J fill:#CFFAFE,stroke:#06B6D4,color:#164E63
    style K fill:#DBEAFE,stroke:#3B82F6,color:#1E3A8A
    style M fill:#D1FAE5,stroke:#10B981,color:#064E3B
```

---

## 📸 See SpamShield in Action

<div align="center">

<img src="assets/spamshield-demo.gif" width="90%" alt="SpamShield application demo" />

<sub>Replace this placeholder with an actual recording of your Streamlit application.</sub>

</div>

---

## ⚙️ MLOps Workflow

### 🔄 DVC Pipeline

```bash
dvc repro
```

### 📊 Experiment Tracking

```bash
dvc exp show
```

### ☁️ Remote Artifact Storage

```bash
dvc push
```

### Configuration Example

```yaml
data_ingestion:
  test_size: 0.2

feature_engineering:
  max_features: 50

model_building:
  n_estimators: 25
  random_state: 2
```

DVC manages pipeline dependencies and outputs, while DVCLive records experiment metrics and artifacts.

---

## 📁 Project Structure

```text
SpamShield/
│
├── .dvc/
├── data/
│   ├── raw/
│   ├── interim/
│   └── processed/
│
├── src/
│   ├── data-ingestion.py
│   ├── pre-processing.py
│   ├── feature-engineering.py
│   ├── model-building.py
│   └── model-evaluation.py
│
├── models/
├── reports/
├── dvclive/
├── experiments/
├── logs/
│
├── app.py
├── spam.csv
├── params.yaml
├── dvc.yaml
├── dvc.lock
└── README.md
```

---

## 🚀 Run Locally

**1. Clone**

```bash
git clone https://github.com/Shashikala-11/SpamShield.git
cd SpamShield
```

**2. Create environment**

```bash
python -m venv myenv
```

Windows:

```powershell
.\myenv\Scripts\activate
```

**3. Install dependencies**

```bash
pip install pandas numpy scikit-learn streamlit pyyaml dvc dvclive
```

**4. Reproduce pipeline**

```bash
dvc repro
```

**5. Launch application**

```bash
streamlit run app.py
```

Open `http://localhost:8501` in your browser.

---

## 🚀 Future Roadmap

- [ ] Batch SMS classification
- [ ] Model comparison and optimization
- [ ] MLflow integration
- [ ] Explainable AI
- [ ] FastAPI integration
- [ ] Docker containerization
- [ ] GitHub Actions CI/CD
- [ ] Model monitoring
- [ ] Data drift detection
- [ ] Cloud deployment

---

## 👩‍💻 Developer

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=soft&color=gradient&customColorList=12,20,24,30&height=130&section=header&text=Shashikala%20Gupta&fontSize=38&fontColor=ffffff&animation=fadeIn" width="100%" />

**Computer Engineering | Machine Learning | Data Science**

<a href="https://github.com/Shashikala-11">
<img src="https://img.shields.io/badge/GitHub-Follow-8B5CF6?style=for-the-badge&logo=github&logoColor=white" />
</a>

<a href="https://github.com/Shashikala-11/SpamShield">
<img src="https://img.shields.io/badge/Explore-SpamShield-06B6D4?style=for-the-badge&logo=github&logoColor=white" />
</a>

<br/><br/>

<img src="https://github-readme-stats.vercel.app/api?username=Shashikala-11&show_icons=true&theme=tokyonight&hide_border=true&bg_color=ffffff&title_color=8B5CF6&icon_color=06B6D4&text_color=334155" width="85%" />

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,14,20,24,30&height=120&section=footer" width="100%" />

### 💜 Thanks for visiting SpamShield!

**Smarter classification. Cleaner inbox. Better ML workflows.**

⭐ Star the repository if you find it interesting!

</div>

---

<sub>Built with Python, Machine Learning, NLP and MLOps concepts. Educational project.</sub>
