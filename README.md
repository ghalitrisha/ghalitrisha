# 👋 Hi, I'm Trisha Ghali

### AI/ML Engineer | LLMs · RAG · Multi-Agent Systems · Explainable AI · MLOps | Published Researcher | MS CS @ CSU

🤖 I build AI systems that simplify processes and reduce manual effort, not just score well on benchmarks  
🔗 I design multi-agent LLM workflows with LangGraph and RAG for financial operations  
🧠 I research how AI planners can explain failures and recommend the smallest fix

---

## 👩‍💻 About Me

AI/ML Engineer with 3+ years of combined industry and research experience across financial services, enterprise technology, and academic research. MS in Computer Science from Colorado State University (GPA 3.84/4.00).

- I translate complex business requirements into practical technical solutions
- I carry projects from initial development through implementation and production support
- I focus on simplifying processes and supporting better business decisions with reliable AI
- I work closely with engineering, risk, operations, and compliance teams
- I publish research and build things that work outside of notebooks

---

## 🧠 What I Do

**Generative AI & Agentic Systems**
- Multi-agent LLM systems with LangGraph and RAG, using stateful execution and controlled tool calls
- Text-to-SQL utilities connecting LLM applications to Snowflake and Databricks
- NLP and retrieval workflows with Hugging Face Transformers, LangChain, and vector embeddings

**Machine Learning Engineering**
- Training and inference pipelines with PyTorch and Scikit-learn
- Anomaly detection, predictive modeling, feature engineering, and hyperparameter tuning
- Automated exception identification for financial reconciliation

**MLOps & Deployment**
- Deploying LLM applications with AWS Bedrock and Docker
- Automating model releases with MLflow, Docker, and Azure
- Model validation, performance monitoring, and production support

**Explainable AI Research**
- Plan repair systems that explain why a plan fails and recommend minimal fixes
- Human-in-the-loop recommendation refinement with guaranteed termination
- Benchmark generation for repeatable, unbiased evaluation

---

## 🛠️ Technical Stack

| Domain | Tools / Technologies |
|---|---|
| Programming Languages | Python, SQL |
| Machine Learning & Deep Learning | Supervised Learning, Unsupervised Learning, Predictive Modeling, Anomaly Detection, Feature Engineering, Feature Selection, Hyperparameter Tuning, CNN, LSTM, GRU, Autoencoders, Random Forest |
| Generative AI & NLP | LLMs, RAG, Agentic AI, Multi-Agent Systems, LangChain, LangGraph, Hugging Face Transformers, NLP, Text-to-SQL, Prompt Engineering, Vector Embeddings, Word2Vec |
| Frameworks & Libraries | PyTorch, TensorFlow, Keras, Scikit-learn, Pandas, NumPy, PySpark |
| Data Engineering & Platforms | ETL Pipelines, Data Preprocessing, Data Transformation, Snowflake, Databricks |
| Cloud & MLOps | AWS, AWS Bedrock, Azure, MLflow, Docker, CI/CD, Model Deployment, Model Monitoring, Model Validation |
| Optimization & Evaluation | Model Pruning, Model Quantization, Inference Optimization, Prefix Caching, Latency Profiling, F1-Score, AUC-ROC, Statistical Significance Testing |

---

## 💼 Professional Experience

**AI/ML Engineer** | McKinsey & Company, USA | *Jun 2026 – Present*
- Automated 3 financial operations workflows, reducing investigation time by about 20%, by building multi-agent LLM systems with Python, LangGraph, and RAG using stateful execution and controlled tool calls.
- Reduced data retrieval and query preparation time by 25% for risk and operations teams by developing Text-to-SQL utilities connecting LLM applications with Snowflake and Databricks.
- Improved anomaly detection F1-score by 8% over the baseline by building PyTorch and Scikit-learn training and inference pipelines with feature engineering and hyperparameter tuning on structured financial data.
- Reduced manual reconciliation review effort by 15% by automating exception identification across financial transactions.
- Deployed 2 LLM applications using AWS Bedrock and Docker, establishing model validation, performance monitoring, and production support processes.
- Improved production issue detection by 12% through monitoring and validation practices with engineering and compliance teams.

**ML Engineer** | Mphasis, India | *Feb 2023 – Jul 2024*
- Built machine learning pipelines with Python and Scikit-learn for 5+ enterprise projects, covering preprocessing, feature engineering, training, and evaluation.
- Developed NLP and RAG workflows using Hugging Face Transformers, LangChain, and vector embeddings, improving information retrieval by 12%.
- Reduced processing time by 20% through feature selection and hyperparameter tuning while maintaining model performance.
- Automated model deployment with Docker, MLflow, and Azure, reducing deployment turnaround by 25%.
- Created ETL and data preparation workflows with Pandas, SQL, and PySpark for 10+ structured and unstructured datasets.
- Worked with data engineers, DevOps teams, and client stakeholders to troubleshoot and validate models, supporting 3+ production deployments.

---

## 🔬 Research Experience

**Graduate Research Assistant** | Colorado State University, Fort Collins, CO | *Aug 2024 – May 2026*
- Built an Explainable AI repair system that explains why a team's plan fails and recommends the smallest fix, repairing 94% of failing plans (94 of 100) across 4 domains by framing repair as a constrained search over action insertions and deletions.
- Achieved a 100% repair rate in 3 of 4 domains, with most fixes needing only 1 to 2 changes, by converting recommendation into an optimization model AI planners solve directly.
- Designed an interactive human-in-the-loop algorithm that refines recommendations from user feedback and is guaranteed to stop, turning each rejected change into a hard constraint for the next search.
- Scaled to problems with up to 1,890 possible actions and plans up to 65 steps, with simpler cases solved in under 1 second, using grounded planning domains and a configurable edit budget.
- Created an automated benchmark generator producing 100 realistic failure scenarios by applying random edits to valid plans and simulating each until it failed.
- Targeted high-stakes collaborative planning such as spacecraft and rover operations, designing the system as a decision aid that verifies plans and suggests repairs for resource failures like low battery.
- Work published as *Plan Explanation through Recommendations* at the ICAPS 2025 HAXP Workshop.

---

## 🚀 Projects

**[Optimizing Reviewer Effort through Functional Logic in OSS](https://github.com/ghalitrisha/-Optimizing-Reviewer-Effort-through-Functional-Logic-in-OSS)**  
Evaluated Qwen2.5-7B, Llama3.1-8B, and Gemma3-4B via Ollama as zero-shot judges across 1,000 GitHub PRs for effort prediction. Implemented prefix caching, profiled TTFT and TPOT across 1,000 inference calls, and validated results with statistical significance testing across 3,493 diff hunk segments. Gemma3-4B reached an F1 of 0.44, outperforming a supervised Random Forest baseline without labeled data.

**[Quantization and Pruning-Aware Deep Recurrent Models for Real-Time HAR on Android](https://github.com/ghalitrisha/Human-Activity-Recognition-on-Android)**  
Designed and trained CNN-LSTM and GRU models on windowed inertial sensor data, achieving 93% accuracy on UCI HAR and 84% on WISDM. Deployed via TensorFlow Lite with int8 quantization (74% smaller model, 7.8ms latency) and added an autoencoder-based anomaly rejection module for out-of-distribution detection.

**[Hate Speech and Offensive Language Detection](https://github.com/ghalitrisha/harmful-speech-detection)**  
Architected a CNN-based classifier from Word2Vec embeddings through 1D convolutional feature extraction and softmax classification across three datasets. Addressed class imbalance with SMOTE and evaluated per-class performance using F1-score and AUC-ROC.

**[YouTube Text Classification](https://github.com/ghalitrisha/Youtube-Text-Classification)**  
Built a text classification pipeline on a YouTube video dataset, training models to categorize video content by topic. Deployed as a Flask web application with a browser-based prediction interface.

---

## 📄 Publications

- **[Plan Explanation through Recommendations](https://openreview.net/forum?id=qfgi8aPbTU)**, ICAPS 2025 HAXP Workshop
- **[Real-time Weapon Surveillance using Motion Capture and Deep Learning](https://ieeexplore.ieee.org/document/10465428)**, ICSES 2023

---

## 🎓 Education

| Degree | Institution | Year | GPA |
|---|---|---|---|
| MS in Computer Science | Colorado State University, Fort Collins, CO | May 2026 | 3.84/4.00 |
| BTech in CS, Specialization in AI | Vellore Institute of Technology, Amaravati, India | Jul 2024 | 3.57/4.00 |

---

## 📫 Let's Connect

- 💼 LinkedIn: **[linkedin.com/in/trisha-ghali](https://linkedin.com/in/trisha-ghali)**
- 🐙 GitHub: **[github.com/ghalitrisha](https://github.com/ghalitrisha)**
- 📧 Email: **trishaghali41@gmail.com**
- 🌍 Location: **USA**

---

💡 *"Equally comfortable in a research paper and a production codebase."*
