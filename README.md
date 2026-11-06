 <div align="center">

<img src="https://capsule-render.vercel.app/api?type=rounded&color=gradient&customColorList=12,14,20,24,30&height=230&section=header&text=SpamShield&fontSize=75&fontColor=ffffff&animation=fadeIn&desc=Smart%20SMS%20Spam%20Detection%20Platform&descSize=20&descAlignY=75" width="100%" />

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=700&size=23&duration=2500&pause=800&color=8B5CF6&center=true&vCenter=true&width=750&lines=Say+Goodbye+to+Unwanted+Messages;Smarter+SMS+Classification;Machine+Learning+Meets+NLP;Detect+Spam.+Keep+Your+Inbox+Clean." />

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

**Intelligent SMS Classification · NLP · Random Forest · DVC · DVCLive**

</div>

---

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=600&size=25&duration=3000&pause=1000&color=635BDB&center=true&vCenter=true&width=600&lines=A+Cleaner+Inbox+Starts+Here." />

<sub>Turning everyday text messages into meaningful predictions.</sub>

</div>

## 01 — Meet SpamShield

SpamShield is a machine learning-powered SMS classification application that identifies whether a message is **Spam** or **Ham (legitimate)**.

It brings together text preprocessing, TF-IDF feature extraction, and Random Forest classification in an interactive Streamlit application.

Alongside the prediction workflow, the project explores reproducible ML pipelines and experiment tracking using DVC and DVCLive.

<div align="center">

<table>
<tr>
<td align="center" width="50%">

<img src="https://img.shields.io/badge/01-SPAM-FF4B6E?style=for-the-badge" />

### Unwanted Messages

Promotional, suspicious or unsolicited messages.

</td>
<td align="center" width="50%">

<img src="https://img.shields.io/badge/02-HAM-10B981?style=for-the-badge" />

### Legitimate Messages

Genuine personal and informational messages.

</td>
</tr>
</table>

</div>

---

## 02 — The Experience

<div align="center">

<img src="https://img.shields.io/badge/SPAMSHIELD%20MESSAGE%20ANALYZER-635BDB?style=for-the-badge&labelColor=EDE9FE" />

<br/><br/>

<table>
<tr>
<td width="100%" align="left">

**MESSAGE INPUT**

<sub>Example message</sub>

> Congratulations! You have won a free prize. Claim your reward now!

<br/>

<img src="https://img.shields.io/badge/ANALYSIS%20RESULT-SPAM%20DETECTED-FF4B6E?style=for-the-badge" />

<sub>Illustrative classification example — not a live prediction.</sub>

</td>
</tr>
</table>

</div>

The Streamlit interface provides a simple way to submit a message and view its predicted category.

## 03 — Features

<table>
<tr>
<td width="50%" valign="top">

<img src="https://img.shields.io/badge/01-8B5CF6?style=flat-square" />

### Intelligent Classification

A Random Forest model classifies messages into Spam and Ham categories.

</td>
<td width="50%" valign="top">

<img src="https://img.shields.io/badge/02-06B6D4?style=flat-square" />

### NLP Processing

TF-IDF transforms message text into numerical features for machine learning.

</td>
</tr>
<tr>
<td width="50%" valign="top">

<img src="https://img.shields.io/badge/03-EC4899?style=flat-square" />

### Interactive Application

A Streamlit interface for submitting messages and viewing predictions.

</td>
<td width="50%" valign="top">

<img src="https://img.shields.io/badge/04-F59E0B?style=flat-square" />

### Reproducible Pipeline

DVC manages the machine learning pipeline and its dependencies.

</td>
</tr>
<tr>
<td width="50%" valign="top">

<img src="https://img.shields.io/badge/05-10B981?style=flat-square" />

### Experiment Tracking

DVCLive records experiment metrics during model development.

</td>
<td width="50%" valign="top">

<img src="https://img.shields.io/badge/06-6366F1?style=flat-square" />

### Configurable Workflow

YAML configuration keeps selected pipeline parameters organized.

</td>
</tr>
</table>

---

## 04 — Under the Hood

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=600&size=20&duration=2800&pause=900&color=8B5CF6&center=true&vCenter=true&width=600&lines=Raw+Text+%E2%86%92+Features+%E2%86%92+Predictions;The+Machine+Learning+Pipeline" />

</div>

```mermaid
flowchart TD
    A(["SMS Message"]) --> B["Text Preprocessing"]
    B --> C["TF-IDF Vectorization"]
    C --> D["Random Forest Classifier"]
    D --> E{"Prediction"}
    E -->|Spam| F(["Spam Detected"])
    E -->|Ham| G(["Legitimate Message"])

    style A fill:#EDE9FE,stroke:#8B5CF6,color:#4C1D95
    style B fill:#CFFAFE,stroke:#06B6D4,color:#164E63
    style C fill:#DBEAFE,stroke:#3B82F6,color:#1E3A8A
    style D fill:#FCE7F3,stroke:#EC4899,color:#831843
    style F fill:#FFE4E6,stroke:#F43F5E,color:#881337
    style G fill:#D1FAE5,stroke:#10B981,color:#064E3B
```

### Pipeline breakdown

| Phase | Operation |
|:--|:--|
| 01 · Ingestion | Load and organize the SMS dataset |
| 02 · Preparation | Clean and prepare message text |
| 03 · Feature extraction | Generate TF-IDF features |
| 04 · Training | Fit the Random Forest classifier |
| 05 · Evaluation | Evaluate classification performance |
| 06 · Application | Predict message categories |

---

## 05 — Technology Universe

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=600&size=22&duration=3000&pause=1000&color=635BDB&center=true&vCenter=true&width=500&lines=The+Tools+Behind+SpamShield" />

</div>

### 01. Core development

<div align="center">

<img src="https://skillicons.dev/icons?i=python,git,github&theme=light&perline=3" />

<br/>

<sub>PYTHON &nbsp; / &nbsp; GIT &nbsp; / &nbsp; GITHUB</sub>

</div>

### 02. Data science & machine learning

<div align="center">

<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />

</div>

| Technology | Application |
|:--|:--|
| NumPy | Numerical computing |
| Pandas | Data manipulation |
| Scikit-learn | Feature extraction, model training and evaluation |
| TF-IDF | Text vectorization |
| Random Forest | Classification |

### 03. User interface

<div align="center">

<img src="https://skillicons.dev/icons?i=streamlit&theme=light" />

<br/>

<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" />

</div>

Streamlit powers the interactive message classification interface.

### 04. MLOps & experiment management

<div align="center">

<img src="https://img.shields.io/badge/DVC-945DD6?style=for-the-badge&logo=dvc&logoColor=white" />
<img src="https://img.shields.io/badge/DVCLive-0891B2?style=for-the-badge" />
<img src="https://img.shields.io/badge/PyYAML-CB171E?style=for-the-badge" />

</div>

These tools support pipeline reproducibility, experiment metrics and configuration management.

---

## 06 — Architecture & MLOps

The project separates model development from application-level prediction while keeping the training workflow organized.

```mermaid
flowchart TB
    A["SMS Dataset"] --> B["Data Ingestion"]
    B --> C["Preprocessing"]
    C --> D["Feature Engineering"]
    D --> E["Random Forest"]
    E --> F["Evaluation"]
    F --> G["Model Artifacts"]

    P["params.yaml"] --> B
    P --> D
    P --> E

    H["DVC Pipeline"] -.-> B
    H -.-> C
    H -.-> D
    H -.-> E
    H -.-> F

    F --> I["DVCLive Metrics"]

    G --> J["Streamlit Application"]
    K["User Input"] --> J
    J --> L["Spam / Ham Prediction"]

    style A fill:#EDE9FE,stroke:#8B5CF6,color:#4C1D95
    style E fill:#FCE7F3,stroke:#EC4899,color:#831843
    style I fill:#CFFAFE,stroke:#06B6D4,color:#164E63
    style J fill:#DBEAFE,stroke:#3B82F6,color:#1E3A8A
    style L fill:#D1FAE5,stroke:#10B981,color:#064E3B
```

### DVC commands

```bash
# Reproduce the pipeline
dvc repro

# Explore experiment results
dvc exp show

# Push tracked outputs to a configured remote
dvc push
```

### Configuration example

```yaml
data_ingestion:
  test_size: 0.2

feature_engineering:
  max_features: 50

model_building:
  n_estimators: 25
  random_state: 2
```

---

## 07 — Repository Structure

```text
SpamShield/
│
├── .dvc/
│
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

## 08 — Get Started

**Prerequisites:** Python 3.9+, Git and pip.

**Clone the project**

```bash
git clone https://github.com/Shashikala-11/SpamShield.git
cd SpamShield
```

**Create a virtual environment**

```bash
python -m venv myenv
```

Windows:

```powershell
.\myenv\Scripts\activate
```

**Install dependencies**

```bash
pip install pandas numpy scikit-learn streamlit pyyaml dvc dvclive
```

**Run the pipeline**

```bash
dvc repro
```

If required data or artifacts are stored in a configured DVC remote, retrieve them before running the application.

**Launch SpamShield**

```bash
streamlit run app.py
```

<div align="center">

<img src="https://img.shields.io/badge/LOCAL%20SERVER-http%3A%2F%2Flocalhost%3A8501-635BDB?style=for-the-badge" />

</div>

---

## 09 — A Look Inside

<div align="center">

<img src="assets/spamshield-demo.gif" width="90%" alt="SpamShield application demonstration" />

<sub>Application walkthrough — replace with your actual screen recording.</sub>

</div>

---

## 10 — What's Next?

| Planned enhancement | Status |
|:--|:--:|
| Batch message classification | Planned |
| Model comparison and tuning | Planned |
| Explainable AI | Planned |
| MLflow integration | Planned |
| FastAPI integration | Planned |
| Docker containerization | Planned |
| GitHub Actions CI/CD | Planned |
| Model monitoring and drift detection | Planned |
| Cloud deployment | Planned |

---

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

### Thanks for visiting SpamShield!

**Smarter classification. Cleaner inbox. Better ML workflows.**

⭐ Star the repository if you find it interesting!

</div>

---

<sub>Built with Python, Machine Learning, NLP and MLOps concepts. Educational project.</sub>
