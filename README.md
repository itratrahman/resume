**ITRAT RAHMAN**  
**UCL Graduate | Data Scientist / ML Engineer / AI Engineer | Visa: H-1B**  
Tel: 8326701119 | Email: rahmanitrat@gmail.com  
**Willing to relocate anywhere in the US | Looking for C2C contract/H1B transfer for full-time role only**  
[LinkedIn](http://www.linkedin.com/in/itratrahman) | [Recommendations](https://www.linkedin.com/in/itratrahman/details/recommendations/) | [Website](https://itratrahman.github.io/) | [GitHub](https://github.com/itratrahman)  
---

**PROFESSIONAL SUMMARY**  
I am a Senior AI Engineer/Data Scientist with over 9 years of technical experience and expertise  in Computer Vision, NLP, LLM, GenAI, Chatbot, Agentic AI, MLOps, Cloud Technologies, Big Data Analytics, and Data Science. I have extensive hands-on AI/data product development and deployment experience; transformed pet projects into startup and SaaS products; wore multiple hats and worked beyond corporate boundaries for product launches, and attended client meetings to pitch products. Check out my detailed [career bio](https://itratrahman.github.io/#bio).  
---

**SKILLS**

* **Data Science/Machine Learning**: linear algebra, statistics, algorithms & data structures, data visualisation, A/B testing, classical machine learning, deep learning, SQL, churn analysis, time series forecasting, natural language processing, named entity recognition  
* **GenAI/AI Agents**: embeddings, semantic search, transformer models, LLM, Diffusion, RAG, vector database, GAN, GenAI, agents, chatbot, machine translation, speech recognition  
* **Computer Vision**: Binary Morphology, Perspective/Affine Transformation, Edge Detection, OCR, object segmentation, object detection, facial recognition, video generation  
* **Data Science Packages/Tools**: Python, NumPy, pandas, scipy, matplotlib, seaborn, bokeh, folium, Scikit-Learn, XGBoost, NLTK, PySpark, dask, Looker Studio, Tableau  
* **AI Frameworks/Tools**: Hugging Face, spaCy, TensorFlow/Keras, PyTorch, Optuna, Keras Tuner, OpenAI API, ChatGPT, GPT Actions, LangChain, LangGraph, Llama, LlamaIndex, OpenCV, Cursor AI, Copilot  
* **Development Tools**: Git, GitHub, Linux, Bash, cron, Flask, FastAPI, Docker, Docker Compose, Airflow, MLflow, CI/CD pipeline, MCP  
* **Databases**: MySQL, PostgreSQL, MongoDB, BigQuery, ChromaDB, Pinecone, Weaviate  
* **Cloud Computing/Data Engineering**: Big Data Analytics using BigQuery; training, fine-tuning, and serving machine learning models using GCP Vertex AI/AWS SageMaker; big data processing via Apache Spark/Dask on GCP Dataproc clusters; API deployment in serverless solutions such as GCP Cloud Functions, GCP Cloud Run, Azure Functions, AWS Lambda, etc.  
* **MLOps/DataOps**: automating ML lifecycle using MLflow, orchestrating DataOps & MLOps pipeline using Airflow, automating deployment using CI/CD pipeline via Jenkins  
* **Power Skills**: English & Bengali Communication, PPT presentation, Client & Stakeholder Communication, Team Management, Project Management using Jira  
* **Domain Knowledge:** fintech, sms, telecom, facial image, pedestrian image, document OCR/parsing/inference, merchant onboarding, eKYC, crm, chemical industry, research & patent literature, robotics, embedded systems

---

**PROFESSIONAL EXPERIENCE**

**Astute 360 Corporation, Texas, USA — Senior Data Scientist**   
April 2024 – Present  
Astute 360 Corporation is a software consultancy company in Texas, USA that develops in-house products and outsources consultants on C2C contracts. I worked as a GenAI Data Scientist at Ascend Performance Materials for 7 months.

* Built and deployed a RAG-based agentic chatbot (GenAI, OpenAI, LangChain, LangGraph, EC2) that retrieves best-fit resumes from user prompts and supports multi-turn conversation, improving resume discovery speed and relevance. Developed a RAG ingestion pipeline that includes an LLM-based resume parser (GCP Vision API, LangChain) to extract and structure key resume fields with 99% extraction accuracy, storing documents and metadata in Pinecone for retrieval. Developed custom RAG retrieval policy using LangChain and implemented agentic flow using LangGraph. Implemented LLM-assisted evaluation for chatbot answer quality, achieving 95% accuracy on internal evaluation.    
* Trained a BERT model (Hugging Face, NVIDIA GPU) using  TDSAE training scheme on the corpus of resume text to function as the embedder for the RAG vector search in the aforementioned chatbot. Orchestrated end-to-end retraining/hyperparameter optimization/export of the model using AWS SageMaker.   
* Trained a multimodal model (Hugging face, NVIDIA GPU) on resume images \+ text using CLIP-style contrastive loss and LoRA/QLoRA fine-tuning to enable downstream tasks such as embedding-based clustering and ranking.   
* Clustered resume types via hierarchical clustering on multimodal embeddings (content, layout aesthetics, applicant features) to support segmentation and analytics.  
* Developed a resume ranking model using linear methods over multimodal inputs \+ LLM-inferred similarity \+ LLM-extracted QA metrics to improve candidate ordering.

**Ascend Performance Materials, Texas, USA — Generative AI Data Scientist (C2C contract with Astute 360 Corp.)**  
March 2025 – September 2025  
Ascend Performance Materials is the world's largest fully integrated producer of nylon 66 resin. I worked as a GenAI Data Scientist at Ascend on a C2C contract with my parent company, Astute 360 Corp, with Collabera as the implementation partner. My role was to develop generative AI applications on top of enterprise data.

* Shipped a SharePoint RAG agent using Custom GPT \+ GPT Actions with Azure Functions middleware (MS Graph search → targeted extraction → response to GPT), driving 5x–10x faster literature review for R\&D stakeholders.  
* Delivered a Dynamics 365 CRM RAG agent where Custom GPT translates NL questions into OData queries; Azure Functions retrieves via Dataverse API, merges results, and runs QA using OpenAI \+ code interpreter, improving ad-hoc analytics productivity 1.5x–2x.  
* Built a spreadsheet-analysis Custom GPT that generates themed business reports with findings \+ recommendations, improving analyst throughput 5x–10x.   
* Created a SOP QA Custom GPT over multi-department safety procedures to improve on-the-spot access to protocols for high-risk plant operations.   
* Automated monthly journal \+ patent scouting using SERPAPI \+ semantic/LLM search, emailing top findings and reducing manual literature search workload by \~50%.  
* Designed a ChatGPT user-churn detection method from usage logs (drop-off in last 75 days \+ minimum monthly messages); used statistical analysis to set thresholds and automated churn reporting via email.  
* Built a secure pipeline to export ChatGPT workspace conversation logs to Rapid7 (daily \+ backfills, chunked payload delivery to webhook) to support compliance/audit archiving and enable GenAI adoption analytics.

**SSL Wireless, Dhaka, Bangladesh — Senior Data Scientist**  
April 2020 – March 2024  
SSL Wireless is the leading fintech and software corporation in Bangladesh, recognized as a top fintech company in the country. I was promoted to a senior role in January 2022 and had since then led, managed, and mentored the next generation of data scientists.

* Built an AI document verification system (Computer Vision, TensorFlow, PyTorch, OpenCV, NVIDIA GPU) for [online merchant](https://signup.sslcommerz.com/login) onboarding, improving onboarding efficiency 40%; trained document-scanning object detection models (\~98% mAP) and resemblance checking binary classification models (\~97% F1). Built OCR-based field extraction/validation with \~95% accuracy, reducing manual checks and improving onboarding quality. Productionized APIs with FastAPI \+ Docker and Jenkins CI/CD for reliable releases; automated end-to-end retraining/export of binary classification models with Airflow and implemented inference logging (MongoDB → BigQuery) powering near-real-time Looker Studio monitoring. Packaged the verification stack into a SaaS offering; supported customer pitching and onboarded 2 clients.  
* Built a real-time multi-face recognition platform (Computer Vision, TensorFlow, OpenCV, FastAPI, Docker, NVIDIA GPU) for camera streams; fine-tuned face recognition model for underrepresented faces and reached 99.5% accuracy on a custom test set. Deployed edge components (video streaming \+ face detection) on Jetson Nano and partnered with the engineering team to deliver real-time notifications plus a facial registration app (TensorFlow.js) that registers varied face poses. Supported creation of a dedicated sister company/startup ([SSL Sentinel](https://www.linkedin.com/posts/ssl-wireless_introducing-mr-s-m-raihan-rashid-our-new-activity-7185589043747815424-K6pq?utm_source=share&utm_medium=member_desktop)); contributed to sales pitching and onboarded 8 clients.  
* Implemented an intrusion detection system (Computer Vision, TensorFlow, OpenCV, FastAPI, Docker, NVIDIA GPU) that flags pedestrians crossing polygon boundaries; deployed a pedestrian detector on Jetson Nano and collaborated on a full backend/frontend monitoring panel.  
* Trained and deployed Bengali ASR (GenAI, LLM, Hugging Face, FastAPI,  Docker, GCP Cloud Run) for merchant audio from CRM, improving accuracy with augmentation and achieving 2.63 Levenshtein distance on field-force speech.  
* Built and deployed Bengali NER (spaCy) to extract products/prices/quantities with 95%+ accuracy, enabling structured downstream CRM workflows.    
* Built and deployed blink-based liveness/spoof detection and integrated into Android via TensorFlow Lite \+ Kotlin, achieving \>99% accuracy on video samples.  
* Delivered a face verification service (Tensorflow, FastAPI,  Docker, AWS Lambda)  to confirm whether two photos belong to the same person, reaching 97% accuracy on a large photo-pair corpus.   
* Automated route optimization by pulling merchant locations (Google Maps) and generating short-distance routes, saving \~$500–$700 per area plus hundreds of manual hours.  
* Reduced manual NID image review by \~400 hours across 200K images using CV quality checks \+ clustering/z-score threshold tuning.   
* Built AutoML forecasting for hourly/daily payment gateway volumes; automated retraining/forecasting with Vertex AI \+ BigQuery and validated campaign lift with A/B testing, contributing to \~7% usage increases during campaign seasons.  
* Implemented a fraud detection service (MySQL geospatial search \+ FastAPI) to flag merchant name/location manipulation and alert CRM apps in near real time.   
* Engineered a distributed pipeline processing 100M log rows/month (MySQL → unified profiles in MongoDB→ tokenized BigQuery tables via Dataflow), accelerating phases 6x–30x via Dask, concurrency, and indexing; automated runs with cron. The pipeline forms the bedrock of all the analytics work done at SSL Wireless.

**Learners & Yearners, Dhaka, Bangladesh — Data Scientist**  
January 2017 – March 2020

* L\&Y is a start-up that aims to develop friendly and animated online courses in AI and machine learning.  
* Designed and delivered an applied ML curriculum with code repositories, slides, and recorded lectures focused on low-level algorithm implementation.   
* Built a Python package implementing core ML algorithms from scratch (Decision Trees, KNN, K-means) and delivered small–medium EDA/predictive projects to reinforce concepts.   
* Taught a 2-month data science bootcamp to 10–15 learners, covering ML fundamentals and hands-on projects.  
* Contributed to startup business planning and pitching materials (business plan, pitch deck).

**Southeast Bank Limited,  Dhaka, Bangladesh — Junior Data Scientist**  
May 2016 \- August 2016  
Southeast Bank Limited is one of the mainstream local banks in Bangladesh.

* Developed a fully-fledged optical character recognition software utilising advanced machine learning and computer vision techniques to convert raw bank documents into text documents.

**Insight Robotics Limited, Hong Kong — Software Engineering Intern (AI/ML)**  
November 2015 \- January 2016  
Insight Robotics is a Hong Kong Robotics company whose flagship product is a fire-detection robot.

* Developed an image-based smoke detection algorithm utilising advanced machine learning and computer vision techniques, which halved the false alarm rate and improved the detection rate.

---

**SELECTED PERSONAL PROJECTS** 

* Document Verification Application of EU Driving License  ([Repository](https://github.com/itratrahman/document_verification)): Built a production-ready AI document verification system with 3-stage pipeline (EfficientNet-B0 binary classifier → PaddleOCR marker validation → RetinaFace detection), achieving 95% end-to-end accuracy and \<2s inference. Trained models on 3,866 images (97% validation F1) with Optuna hyperparameter optimization and MLflow tracking. Productionized with FastAPI \+ async MongoDB logging \+ Docker; implemented thread-safe inference, hot model reloading, and comprehensive health checks with pytest integration.   
* Stock Market Agent ([Repository](https://github.com/itratrahman/stock_market_agent)): Built an AI stock analysis agent with 5-stage pipeline: FMP API data ingestion → NeuralProphet forecasting (5yr daily data, 5 stocks) → 30-day predictions → NewsAPI article extraction with newspaper4k → LangGraph agentic workflow. Implemented conditional state machine routing forecast quality to news summarization, using Ollama/Llama 3.2 for iterative article synthesis and 3-tier investment recommendations. Outputs tabulated reports with forecast summaries (\<300 chars), news digests (\<1000 chars), and decision rationale (\<200 chars).  
* Codebase of ML Training Program  ([Repository](https://github.com/itratrahman/data_science_training)) \- Built a comprehensive data science training curriculum with 50+ Jupyter notebooks covering 7 ML domains; implemented 15+ algorithms from scratch in NumPy (linear/logistic regression, decision trees, KNN, Naive Bayes, PCA). Developed modular ML library with gradient descent optimization, L1/L2 regularization, and utilities for preprocessing, model selection, and evaluation.

---

**EDUCATION**  
**University College London, London — Master of Engineering (Integrated 4-year Master’s)**  
September 2011 \- June 2015  
UCL is one of the world's very best universities, consistently placed in the top 20 in global rankings.  

* **Course**: Electronic and Electrical Engineering  
* **Achievements & Awards: Grade**: First Class Honours | First Class results in all 4 years | 2014 UROS Studentship 

---

**CERTIFICATION**  
**Coursera – Verified Courses**  

* Deep Learning Specialization (5 courses) from Coursera ([Link](https://www.coursera.org/account/accomplishments/specialization/BLLGXBBCZJMW))  
* Machine Learning Specialization (4 courses) from Coursera ([Link](https://www.coursera.org/account/accomplishments/specialization/DBGGPCRJZC4B?utm_product=s12n))  
* Data Engineering, Big Data, and Machine Learning on GCP (5 courses) from Coursera ([Link](https://www.coursera.org/account/accomplishments/specialization/WR7WQN9X6WHV))  
* Python Specialization (5 courses) from Coursera ([Link](https://www.coursera.org/account/accomplishments/specialization/4HFPDHNJAEBH))

Check out the recommendations from industry professionals and leaders: [Link](https://www.linkedin.com/in/itratrahman/details/recommendations/)  
---

