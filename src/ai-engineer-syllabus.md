# AI Engineer Syllabus

> [!IMPORTANT]
> This syllabus is under progress.
> All Links are yet to be given.

## Table of contents:
- [Syllabus](#ai-learning-roadmap)
- [Resources](#learning-resources)



# AI Learning Roadmap 

---

## Unit 0: Foundations of Real-World AI (NEW - Critical for Beginners)

- **Data Lifecycle**
  - Data collection
  - Data cleaning
  - Modeling
  - Deployment

- **Problem Framing**
  - Classification vs Regression vs Clustering
  - When NOT to use ML
  - Defining success metrics

- **Data Splitting**
  - Train / Validation / Test sets
  - Avoiding data leakage

- **Baseline Models**
  - Importance of simple models before complex ones

- **Exploratory Data Analysis (EDA)**
  - Distribution analysis
  - Correlation analysis
  - Identifying patterns and anomalies

- **Introduction to Tools**
  - Git & GitHub basics
  - Command Line (CLI) basics

---

## Unit 1: Mathematical Foundations (The Survival Kit)

- **Linear Algebra**
  - Matrix operations (addition, multiplication)
  - Vectors
  - Dot and Cross products
  - Cosine similarity

- **Calculus**
  - Understanding equations for model optimization (Gradient Descent)

- **Probability & Statistics**
  - Foundations for evaluation and predictive logic

---

## Unit 2: Programming & Data Manipulation

- **Python Mastery**
  - Loops
  - Conditionals
  - Classes and objects

- **Data Libraries**
  - NumPy for matrix math
  - Pandas for data cleaning

- **Data Handling (NEW - Critical)**
  - Handling missing values
  - Outlier detection
  - Feature engineering
  - Data normalization & scaling
  - Handling imbalanced datasets

- **Data Visualization**
  - Matplotlib
  - Seaborn

---

## Unit 3: Classical Machine Learning & Deep Learning

- **ML Core**
  - Supervised Learning
    - Regression
    - Classification
  - Unsupervised Learning
    - Clustering
  - Algorithms
    - SVMs
    - KNN

- **Evaluation Metrics**
  - Accuracy
  - Precision
  - Recall
  - F1 Score

- **Experimentation Mindset (NEW)**
  - Hypothesis → Experiment → Evaluation loop
  - Iterative improvement

- **Deep Learning**
  - The Perceptron
  - Backpropagation
  - Activation functions
  - Loss functions

- **Frameworks**
  - PyTorch (focus on architecture building)

---

## Unit 4: Specialized Core AI (Computer Vision, NLP, Robotics)

- **Computer Vision (CV)**
  - CNN architectures
  - Object detection
  - Segmentation

- **NLP**
  - Sequence models
  - RNNs
  - LSTMs
  - Text embeddings

- **Reinforcement Learning (RL)**
  - Markov Decision Processes (MDPs)
  - Deep Q-Networks (DQN)
  - Policy Gradient methods

---

## Unit 5: Transformers & Large Language Models (Core Path)

- **The Architecture**
  - Self-attention
  - Multi-head attention
  - Variants:
    - GQA (Grouped Query Attention)
    - MLA (Multi-head Latent Attention)
    - DSA (Dynamic Sparse Attention)

- **Training Pipeline**
  - Pre-training (massive datasets)
  - Mid-training (domain knowledge)
  - Post-training
    - RLHF (Reinforcement Learning from Human Feedback)
    - Instruction tuning
    - Test-time compute

- **Finetuning**
  - LoRA (Low-Rank Adaptation)
  - QLoRA
  - Libraries:
    - Hugging Face TRL

- **Working with Pretrained Models (NEW)**
  - Using Hugging Face models
  - Prompting vs Finetuning vs RAG decisions

---

## Unit 6: Applied AI & Full-Stack Integration (Applied Path)

- **API & Prompt Engineering**
  - GPT / Claude / Gemini APIs
  - Function calling

- **RAG (Retrieval Augmented Generation)**
  - Vector databases:
    - Pinecone
    - Milvus
  - Indexing strategies
  - Chunking strategies

- **AI Agents**
  - Systems that:
    - Perceive
    - Reason
    - Act
  - Frameworks:
    - LangGraph

- **Model Context Protocol (MCP)**
  - Standardizing LLM connections to databases and APIs

- **Full-Stack Development**
  - Next.js
  - Node.js
  - PostgreSQL
  - WebSockets
  - WebRTC

- **SQL (NEW - Critical)**
  - SELECT, JOIN, GROUP BY
  - Query optimization basics

---

## Unit 7: MLOps & Production Readiness

- **Deployment**
  - Docker
  - Kubernetes

- **Maintenance**
  - Experiment tracking
  - Inference optimization (TensorRT)
  - Monitoring for model breakage

- **Hardware Awareness (NEW)**
  - CPU vs GPU vs TPU basics
  - Memory constraints
  - When GPU is actually needed

- **Security & Compliance**
  - Auditing AI code for vulnerabilities
  - Production readiness

---

## Unit 8: Ethics, Limitations & Responsible AI (NEW)

- Bias in AI systems
- Hallucination in LLMs
- Data privacy concerns
- Responsible AI deployment

---

## Key Mindset

- Be a **"Rabbit"**
  - Build fast
  - Ship fast
  - Focus on real-world applications
  - Avoid over-consuming theory

---

 # AI Learning Evaluation Metrics (Rapid Developer Framework)

## Goal

The effectiveness of someone following this syllabus is measured by their ability to transition from a **consumer of tutorials** to a **"rapid developer"** who can ship production-ready products independently.

---

## 1. Technical Proficiency Metrics

### Mathematical Survival
- Ability to perform:
  - Matrix addition and multiplication
  - Dot and cross products
- Understand how these concepts power AI systems
- Avoid over-reliance on high-level libraries

### Deep Understanding vs Tooling
- **Core AI Path**
  - Ability to implement architectures (e.g., Transformers) from scratch in PyTorch
  - Ability to write GPU kernels

- **Applied AI Path**
  - Speed of integrating new tools, APIs, and protocols (e.g., MCP)
  - Ability to adapt quickly to evolving ecosystems

### Evaluation Capability (Critical - 2026)
- Ability to design and write custom **evaluation systems ("evals")**
- Test:
  - Model performance
  - Safety
  - Robustness of AI agents

---

## 2. Engineering & Product Metrics

### The "Rabbit" Metric (Velocity)
- Ability to:
  - Convert research papers into working products
  - Ship functional systems within **~2 weeks**

### Full-Stack Independence
- Ability to independently:
  - Design database schemas
  - Build backend APIs
  - Develop UI (React / Next.js)
- No reliance on separate specialists

### Resilience & Feedback Loops
- Build systems that:
  - Handle human feedback
  - Maintain memory over time
- Move beyond simple one-off scripts

---

## 3. Career & Hiring Metrics

### The "Dart-Throwing" Volume
- Apply to a high volume of roles (e.g., **500+ applications**)
- Maintain consistency as a daily discipline

### Unique Visualizations
- Build **non-generic projects**
- Solve underexplored problems
- Example:
  - Custom episodic memory system for personal data (e.g., photos)

---

## 4. Recommended Project Milestones (Combined Metric)

### Tier 1: Foundation
- **Focus:** Logic & UI
- **Projects:**
  - Todo App (Next.js + PostgreSQL)
  - Lovable clone

---

### Tier 2: Complexity
- **Focus:** Scale & Real-time systems
- **Projects:**
  - Trading App
  - Codeforces Clone
- **Tech:**
  - WebSockets
  - WebRTC

---

### Tier 3: AI Core
- **Focus:** Agents & Memory
- **Projects:**
  - Agent framework built from first principles
  - Systems that can perceive and act

---

### Tier 4: Specialization
- **Focus:** Evaluation & Reinforcement Learning
- **Projects:**
  - RL fine-tuning system
  - Custom evaluation pipelines for:
    - Safety
    - Accuracy
    - Robustness

---

## Final Metric of Success

- Ability to land and operate in a role where:
  - You work in a **small, high-performance team (~5 people)**
  - That team can outperform a **large, siloed team (~100 people)**
  - You are expected to operate **independently** 

---

# AI/ML Hardware Requirements & Progressive Learning Path (2026)

---

## 1. Hardware and OS Requirements

### Initial Level: Foundations & Applied AI

At this stage, focus is on:
- Python scripting
- Data manipulation
- Calling LLM APIs (GPT, Gemini)

#### Minimum Hardware
- CPU: Modern quad-core (Intel i5 / Ryzen 5 equivalent)
- RAM: 8GB
- Storage: 256GB SSD

#### Recommended Hardware
- RAM: 16GB
- GPU: Integrated GPU is sufficient
- Storage: 512GB SSD+

#### OS
- Linux (Ubuntu based POP OS)

---

### Advanced Level: Deep Learning, Core AI & MLOps

Triggered when working on:
- Neural networks (PyTorch)
- Fine-tuning models
- GPU kernels

#### Minimum Hardware
- GPU: NVIDIA GPU (8GB VRAM, e.g., RTX 3060)
- RAM: 16GB

#### Recommended Hardware
- GPU: RTX 40-series (12GB+ VRAM)
- CPU: 8-core+ (i7 / Ryzen 7)
- RAM: 32GB preferred

#### OS
- Linux (Ubuntu based POP OS)

---

### Specialized Path: Robotics & Edge AI

#### Hardware
- Arduino Nano 33 BLE (TinyML)
- ESP32 (sensor-based ML)
- NVIDIA Jetson AGX Orin (edge AI)
- Coral TPU (inference acceleration)

#### Tools
- ROS (Robot Operating System)
- Vivado (FPGA workflows)

---

## 2. Mapping Hardware to Syllabus Projects

| Project Type                  | Syllabus Unit | Hardware / Tools                          |
|------------------------------|--------------|-------------------------------------------|
| Data Analytics / Todo App    | Units 2 & 6  | Standard Laptop, Node.js, Python          |
| AI Agents / RAG Systems      | Unit 6       | 16GB RAM (recommended for vector DBs)     |
| Real-time Computer Vision    | Unit 4       | NVIDIA GPU (CNN inference)                |
| Trading App / WebSockets     | Unit 6       | Stable internet, Node/Bun + Postgres      |
| TinyML / Gesture Detection   | Units 4 & 5  | Arduino Nano / ESP32, Edge Impulse        |
| Model Fine-tuning (LoRA)     | Unit 5       | 12GB+ VRAM GPU OR Cloud (Colab/HF)        |
| Autonomous Robotics          | Unit 4       | Jetson / Raspberry Pi + sensors           |

---

## 3. Real-World Constraint: Low-End Hardware Path

Many learners may start with:
- Intel i3 (latest gen)
- 8GB RAM
- SSD
- Integrated GPU

This setup is **not a limitation**, but requires a **progressive learning strategy**.

---

## 4. Progressive Learning Path (Hardware-Aware)

### Phase 1: Fully Local (No Upgrade Required)

#### Recommended Units
- Unit 0: Foundations of Real-World AI
- Unit 1: Mathematical Foundations
- Unit 2: Programming & Data Manipulation
- Unit 6: Applied AI & Full-Stack Integration

#### Capabilities
- Data cleaning and manipulation (small datasets)
- API-based AI development
- RAG systems (lightweight or hosted DBs)
- Full-stack applications (Next.js, Node.js)

---

### Phase 2: Hybrid (Local + Cloud)

#### Recommended Units
- Unit 3: Classical Machine Learning
- Unit 4: Intro to CV/NLP

#### Strategy
- Train small models locally
- Use cloud platforms for heavier tasks:
  - Google Colab
  - Kaggle
  - Hugging Face Spaces

#### Limitations (Local)
- Avoid large datasets
- Avoid heavy CNN training
- Avoid large NLP models

---

### Phase 3: Cloud-Dependent (No Local GPU Needed)

#### Recommended Units
- Unit 5: Transformers & LLMs

#### Tools
- Google Colab / Colab Pro
- RunPod / Paperspace
- Hugging Face Training

#### Focus
- Fine-tuning (LoRA / QLoRA)
- LLM experimentation
- Model evaluation

---

### Phase 4: Hardware Upgrade (Only If Necessary)

Upgrade only when:
- Local training becomes frequent
- Real-time inference is needed
- Working on robotics or edge AI

#### Upgrade Priority
1. RAM → 16GB
2. NVIDIA GPU
3. Better CPU (optional)

---

## 5. Practical Hardware Strategy

### Do NOT:
- Wait for high-end hardware to start
- Over-invest early without need

### DO:
- Maximize current hardware
- Use cloud for scaling
- Upgrade only when bottleneck is real

---

## 6. Capability vs Hardware Reality

### With Current Low-End Setup You CAN:
- Build AI SaaS applications
- Develop RAG systems
- Build AI agents
- Learn ML fundamentals

### You MAY struggle with:
- Large-scale model training
- Real-time computer vision
- High-performance deep learning workloads

---

## Final Insight

> Skill progression in AI is not blocked by hardware—it is limited by strategy.

A learner using:
- Smart cloud usage
- Efficient tools
- Proper sequencing

can reach:
- Top 20–30% level with local hardware
- Top 10% with cloud integration

Hardware upgrades are only critical for:
- Core AI research
- High-performance systems
- Robotics and edge deployments

---

##  Learning Resources

---

## Unit 0: Foundations of Real-World AI

### Data & Problem Framing
- [Google Intro To Machine Learning](https://developers.google.com/machine-learning/intro-to-ml)
- Google Machine Learning Crash Course :https://developers.google.com/machine-learning/crash-course/prereqs-and-prework  
- Book: Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow — Aurélien Géron

### EDA & Data Thinking
- Book: Python for Data Analysis — Wes McKinney  
- Kaggle Learn (Micro-courses)https://www.kaggle.com/learn 

### Git & CLI
- Pro Git — Scott Chacon (free online) https://www.kaggle.com/learn 
- The Net Ninja (YouTube — Git basics) https://youtube.com/playlist?list=PL4cUxeGkcC9goXbgTDQ0n_4TBzOO0ocPR&si=KN7uU1dd73EOyMUA

---

## Unit 1: Mathematical Foundations

### Linear Algebra
- 3Blue1Brown — Essence of Linear Algebra (YouTube) https://youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab&si=3Jp80cErgt98fqr2 
- Book: Linear Algebra and Its Applications — Gilbert Strang  

### Calculus
- Khan Academy — Calculus https://www.khanacademy.org/math/calculus-1 
- Andrew Ng lectures  https://youtube.com/playlist?list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU&si=oiuJRI_WTA70ybDj

### Probability & Statistics
- StatQuest with Josh Starmer (YouTube)  
- Think Stats — Allen Downey  

---

## Unit 2: Programming & Data Manipulation

### Python
- Book: Automate the Boring Stuff with Python — Al Sweigart  
- Code With Harry Python Full Course  https://youtu.be/UrsmFxEIp5k?si=qIxeW7n56Tn5FSn0

### Libraries
- NumPy Documentation  
- Pandas Documentation  

### Visualization
- Matplotlib Docs  
- Seaborn Docs  

---

## Unit 3: Classical ML & Deep Learning

### Machine Learning
- Machine Learning by Andrew Ng (Coursera)  
- Pattern Recognition and Machine Learning — Christopher Bishop  

### Deep Learning
- Deep Learning Specialization — Andrew Ng  
- Deep Learning — Ian Goodfellow  

### Framework
- PyTorch Official Tutorials  

---

## Unit 4: Specialized AI

### Computer Vision
- CS231n — Stanford  
- OpenCV Documentation  

### NLP
- CS224n — Stanford  
- Speech and Language Processing — Jurafsky  

### Reinforcement Learning
- David Silver RL Course  

---

## Unit 5: Transformers & LLMs

### Core
- Attention Is All You Need (paper)  
- Yannic Kilcher (YouTube explanations)  

### Practical
- Hugging Face Documentation  
- Transformers Library Docs  

### Finetuning
- LoRA / QLoRA Papers  
- Hugging Face TRL Docs  

---

## Unit 6: Applied AI & Full-Stack

### APIs
- OpenAI Docs  
- Anthropic Docs  
- Google Gemini Docs  

### RAG
- Pinecone Docs  
- Milvus Docs  

### Agents
- LangGraph Docs  

### Full-Stack
- Next.js Docs  
- Node.js Docs  
- Traversy Media (YouTube)  

---

## Unit 7: MLOps

### Deployment
- Docker Docs  
- Kubernetes Docs  

### Optimization
- TensorRT Docs  

---

## Unit 8: Ethics

- Partnership on AI Reports  
- OpenAI Safety Blog  

---

## Stay Updated

- arXiv  
- Papers With Code  
- Two Minute Papers (YouTube)  

---

## Rule

- Use:
  - Docs
  - Courses
  - Books

- Avoid:
  - Random AI influencers

> Learn → Build → Evaluate → Repeat
