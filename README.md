[![](https://img.shields.io/badge/Contribute-Welcome-green)](#) ![GitHub repo size](https://img.shields.io/github/repo-size/afondiel/cs-books) ![GitHub commit activity (branch)](https://img.shields.io/github/commit-activity/t/afondiel/cs-books/main) ![Packagist Stars](https://img.shields.io/github/stars/afondiel/cs-books.svg) ![Packagist forks](https://img.shields.io/github/forks/afondiel/cs-books.svg) 

# CS Books

## Overview

Welcome to **CS Books**, a curated collection of computer science resources organized by topics and real-world applications. Whether you're a student, researcher, or industry professional, this repository has something for you!

## **Disclaimer**  

All books and resources are the property of their respective authors or publishers. This repository is for educational purposes only. For any copyrighted materials, please refer to the original publisher for usage rights.

## Getting Started

### Cloning the Repository
The full repo includes large files managed with Git LFS. To clone efficiently:

#### Full Clone
```bash
git clone https://github.com/afondiel/cs-books.git
cd cs-books
git lfs pull
```

#### Selective Clone (Recommended)
Clone only specific branches or files to save time and bandwidth:
```bash
git clone --no-checkout https://github.com/afondiel/cs-books.git
cd cs-books
git sparse-checkout init --cone
git sparse-checkout set <path/to/desired/directory>  # Example: only ai/nlp books
git checkout main # This will download only the files in the specified "ai/nlp"
```
When you need to update your repository, use:
```bash
git pull
```

Git will only fetch the objects needed for the sparse checkout paths you've specified

If you need a specific large file that wasn't initially downloaded:

```bash
git lfs pull --include="path/to/large/file" # (e.g., `edge/tinyML`).
```

### Downloading Individual Books
Don’t want to clone? Can't access the file? 
Open the file and select the direct **"Download"** button. 

> [!NOTE]
> If the preview fails, **DON'T PANIC!** GitHub sometimes fails to preview large files, typically those over 10MB.

## 🔍 Navigation Tree

### 📚 Category
#### 🖥️ Computer Architecture
- [Computer Architecture](computer-architecture/) - Core architecture books
- [Operating Systems](operating-systems/) - OS-related books
- [Quantum Computer](computer-science/quantum-computing/) - Quantum computing books
- [Embedded Computer](embedded-systems/) - Embedded Computer Books
- [Neuromorphic Computer](computer-science/neuromorphic-computing/) - Neuromorphic books
- [High-Performance Computing](computer-science/high-performance-computing/) - HPC books

#### 💻 Computer Programming
- [Algorithms](computer-science/programming/algorithms/) - Algorithm books
- [Data Structures](computer-science/programming/data-structures/) - Data structure books
- [Design Patterns](computer-science/programming/design-patterns/) - Design pattern books
- [Languages](computer-science/programming/languages/) - Language-specific books
- [Parallel Programming](computer-science/parallel-computing/) - Parallel computing books
    - [Distributed Computing](computer-science/distributed-computing/) - Distributed computing books
    - [Shared Computing](computer-science/shared-computing/) - Shared computing books
- [Software Engineering](computer-science/software-engineering/) - Software engineering books
#### 🤖 Artificial Intelligence
- [Artificial Intelligence](ai/) - AI books (root)
- [Machine Learning](ai/machine-learning/) - ML books
- [Deep Learning](ai/deep-learning/) - DL books
- [Computer Vision](computer-vision/) - CV books
- [NLP](ai/nlp/) - NLP books
- [Generative AI](ai/generative-ai/) - Generative AI books
- [Agentics AI](ai/agents/) - AI agent books
    - [AI Agents](ai/ai-agents/) - General AI agents
    - [Embodied Agents](robotics/) - Embodied agents
- [AGI](ai/agi/) - AGI books
- [ASI](ai/asi/) - ASI books
#### 📊 Data Science
- [Data Science](data-science/) - Data science books
#### ☁️ Cloud Computing
- [Cloud Computing](cloud/) - Cloud computing books
#### 🌐 Edge Computing
- [Edge Computing](edge/) - General edge computing
- [Edge-AI](edge/) - Edge AI books
- [TinyML](edge/tinyML/) - TinyML books
#### 🔧 Embedded Systems
- [Embedded Systems](embedded-systems/) - Embedded systems books
#### 📡 Signal Processing
- [Signal Processing](signal-processing/) - Signal processing books

### 🛠️ Applications
#### 🚗 Automotive
- [ADAS](automotive/adas/) - ADAS books
- [Safety](automotive/safety/) - Safety books
- [Self-Driving Cars](automotive/self-driving-cars/) - Autonomous driving books
- [Standards](automotive/standards/) - Standards books
#### 🔒 Cybersecurity
- [Cyber Security](security/) - Cybersecurity books
#### 🎮 Game Development
- [Game Development](game/) - Game dev books
#### 🏥 Healthcare
- [Healthcare](healthcare/) - Healthcare tech books
#### 🤖 Robotics
- [Robotics](robotics/) - Robotics books

## Contributing
Want to add a book or a relevant computer science resource?
1. Fork the repository
2. Create a new branch
3. Add your book/resource
4. Submit a pull request
---

>### I am deeply grateful to all the authors and researchers who have worked tirelessly on these incredible books, which have not only shaped the field of Computer Science but also enriched our knowledge and lives. 

Cheers and Happy Reading!

[@Muntu](https://github.com/afondiel/)