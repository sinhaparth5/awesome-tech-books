<div align="center">

<img src="assets/banner.svg" alt="Awesome Tech Books" width="100%">

<br>

**A curated shelf of the books, papers and lecture notes I keep coming back to.**

Foundational AI/ML papers, GPU and parallel programming, the mathematics underneath it all,
and the systems books that explain how the machine actually works.

<br>

![PDFs](https://img.shields.io/badge/PDFs-46-818CF8?style=for-the-badge&labelColor=1B1B4B)
![Shelves](https://img.shields.io/badge/Shelves-11-22D3EE?style=for-the-badge&labelColor=1B1B4B)
![License](https://img.shields.io/badge/License-MIT-F472B6?style=for-the-badge&labelColor=1B1B4B)

<br>

[The shelves](#-the-shelves) &nbsp;·&nbsp; [Where to start](#-where-to-start) &nbsp;·&nbsp; [Full catalogue](#-full-catalogue) &nbsp;·&nbsp; [Topics](#-topics) &nbsp;·&nbsp; [Contributing](#-contributing)

</div>

---

## 📚 The shelves

| Shelf | Count | What's inside |
| :--- | :---: | :--- |
| [**ai-and-machine-learning**](ai-and-machine-learning) | 16 | The canonical papers, split into foundations, language models, probabilistic ML and surveys |
| [**mathematics**](mathematics) | 8 | Linear algebra, probability & statistics, analysis, matrix calculus |
| [**cuda-and-gpu**](cuda-and-gpu) | 6 | CUDA from first kernels to massively parallel processor design |
| [**parallel-and-distributed**](parallel-and-distributed) | 3 | MPI and the theory of distributed systems |
| [**computer-architecture**](computer-architecture) | 3 | How computers work, from NAND gates upward |
| [**cryptography-and-privacy**](cryptography-and-privacy) | 2 | Cryptography and differential privacy lecture notes |
| [**programming**](programming) | 2 | Competitive programming and language references |
| [**quantum-computing**](quantum-computing) | 2 | Quantum information and Ising solvers |
| [**notes**](notes) | 2 | My own write-ups |
| [**physics**](physics) | 1 | Relativity lecture notes |
| [**coursework**](coursework) | 1 | Course assignments |

> Files are named `Title - Author (Year).pdf` so every shelf sorts and reads cleanly.

---

## 🌟 Where to start

Six papers, 1951 to 2023, that cover the most ground between them.

| Paper | Why it matters |
| :--- | :--- |
| [The Perceptron — Rosenblatt (1958)](ai-and-machine-learning/foundations/The%20Perceptron%20-%20A%20Probabilistic%20Model%20for%20Information%20Storage%20and%20Organization%20in%20the%20Brain%20-%20Rosenblatt%20%281958%29.pdf) | Where learning machines begin |
| [Prediction and Entropy of Printed English — Shannon (1951)](ai-and-machine-learning/foundations/Prediction%20and%20Entropy%20of%20Printed%20English%20-%20Shannon%20%281951%29.pdf) | Language modelling, decades before language models |
| [A Neural Probabilistic Language Model — Bengio et al. (2003)](ai-and-machine-learning/foundations/A%20Neural%20Probabilistic%20Language%20Model%20-%20Bengio%2C%20Ducharme%2C%20Vincent%20%26%20Jauvin%20%282003%29.pdf) | Word embeddings, from first principles |
| [Deep Learning — LeCun, Bengio & Hinton (2015)](ai-and-machine-learning/foundations/Deep%20Learning%20-%20LeCun%2C%20Bengio%20%26%20Hinton%20%282015%29.pdf) | The field's own summary of itself |
| [BERT — Devlin et al. (2019)](ai-and-machine-learning/language-models/BERT%20-%20Pre-training%20of%20Deep%20Bidirectional%20Transformers%20for%20Language%20Understanding%20-%20Devlin%2C%20Chang%2C%20Lee%20%26%20Toutanova%20%282019%29.pdf) | Pretraining as the default |
| [FlashAttention-2 — Dao (2023)](ai-and-machine-learning/language-models/FlashAttention-2%20-%20Faster%20Attention%20with%20Better%20Parallelism%20and%20Work%20Partitioning%20-%20Dao%20%282023%29.pdf) | Why attention got fast |

**Reading paths**

- **GPU programming** → [Programming Massively Parallel Processors](cuda-and-gpu/Programming%20Massively%20Parallel%20Processors%20-%20A%20Hands-on%20Approach%20-%20Kirk%20%26%20Hwu%20%282010%29.pdf) → [CUDA by Example](cuda-and-gpu/CUDA%20by%20Example%20-%20An%20Introduction%20to%20General-Purpose%20GPU%20Programming%20-%20Sanders%20%26%20Kandrot%20%282010%29.pdf) → [CUDA C++ Programming Guide](cuda-and-gpu/CUDA%20C%2B%2B%20Programming%20Guide%20v12.8%20-%20NVIDIA%20%282025%29.pdf)
- **The machine underneath** → [Code (Petzold)](computer-architecture/Code%20-%20The%20Hidden%20Language%20of%20Computer%20Hardware%20and%20Software%2C%202nd%20Edition%20-%20Petzold%20%282022%29.pdf) → [The Elements of Computing Systems](computer-architecture/The%20Elements%20of%20Computing%20Systems%20-%20Building%20a%20Modern%20Computer%20from%20First%20Principles%2C%202nd%20Edition%20-%20Nisan%20%26%20Schocken%20%282021%29.pdf)
- **The maths** → [The Mathematics of AI](mathematics/The%20Mathematics%20of%20Artificial%20Intelligence%20-%20Peyre%20%282025%29.pdf) → [Matrix Calculus](mathematics/Matrix%20Calculus%20for%20Machine%20Learning%20and%20Beyond%20-%20Edelman%20%26%20Johnson%20%282025%29.pdf) → [Probability & Statistics for Data Science](mathematics/Probability%20and%20Statistics%20for%20Data%20Science%20-%20Fernandez-Granda.pdf)

---

## 📖 Full catalogue

### AI and machine learning

**Foundations**

- [A Neural Probabilistic Language Model — Bengio, Ducharme, Vincent & Jauvin (2003)](ai-and-machine-learning/foundations/A%20Neural%20Probabilistic%20Language%20Model%20-%20Bengio%2C%20Ducharme%2C%20Vincent%20%26%20Jauvin%20%282003%29.pdf)
- [Backpropagation Through Time for Networks with Long-Term Dependencies — Bird (2021)](ai-and-machine-learning/foundations/Backpropagation%20Through%20Time%20for%20Networks%20with%20Long-Term%20Dependencies%20-%20Bird%20%282021%29.pdf)
- [Deep Learning — LeCun, Bengio & Hinton (2015)](ai-and-machine-learning/foundations/Deep%20Learning%20-%20LeCun%2C%20Bengio%20%26%20Hinton%20%282015%29.pdf)
- [Prediction and Entropy of Printed English — Shannon (1951)](ai-and-machine-learning/foundations/Prediction%20and%20Entropy%20of%20Printed%20English%20-%20Shannon%20%281951%29.pdf)
- [The Perceptron — Rosenblatt (1958)](ai-and-machine-learning/foundations/The%20Perceptron%20-%20A%20Probabilistic%20Model%20for%20Information%20Storage%20and%20Organization%20in%20the%20Brain%20-%20Rosenblatt%20%281958%29.pdf)

**Language models**

- [BERT — Devlin, Chang, Lee & Toutanova (2019)](ai-and-machine-learning/language-models/BERT%20-%20Pre-training%20of%20Deep%20Bidirectional%20Transformers%20for%20Language%20Understanding%20-%20Devlin%2C%20Chang%2C%20Lee%20%26%20Toutanova%20%282019%29.pdf)
- [FlashAttention-2 — Dao (2023)](ai-and-machine-learning/language-models/FlashAttention-2%20-%20Faster%20Attention%20with%20Better%20Parallelism%20and%20Work%20Partitioning%20-%20Dao%20%282023%29.pdf)
- [Large Language Models in Machine Translation — Brants, Popat, Xu, Och & Dean (2007)](ai-and-machine-learning/language-models/Large%20Language%20Models%20in%20Machine%20Translation%20-%20Brants%2C%20Popat%2C%20Xu%2C%20Och%20%26%20Dean%20%282007%29.pdf)

**Probabilistic ML**

- [Hidden Markov Models, from Speech and Language Processing — Jurafsky & Martin (2026 draft)](ai-and-machine-learning/probabilistic-ml/Hidden%20Markov%20Models%20%28Speech%20and%20Language%20Processing%29%20-%20Jurafsky%20%26%20Martin%20%282026%20draft%29.pdf)
- [Hidden Markov Neural Networks — Rimella & Whiteley (2025)](ai-and-machine-learning/probabilistic-ml/Hidden%20Markov%20Neural%20Networks%20-%20Rimella%20%26%20Whiteley%20%282025%29.pdf)
- [Practical Bayesian Optimization of Machine Learning Algorithms — Snoek, Larochelle & Adams (2012)](ai-and-machine-learning/probabilistic-ml/Practical%20Bayesian%20Optimization%20of%20Machine%20Learning%20Algorithms%20-%20Snoek%2C%20Larochelle%20%26%20Adams%20%282012%29.pdf)
- [Probabilistic Artificial Intelligence — Krause & Hübotter (2025)](ai-and-machine-learning/probabilistic-ml/Probabilistic%20Artificial%20Intelligence%20-%20Krause%20%26%20Hubotter%20%282025%29.pdf)

**Surveys and applications**

- [A Comprehensive Guide to Explainable AI — Hsieh et al. (2024)](ai-and-machine-learning/surveys-and-applications/A%20Comprehensive%20Guide%20to%20Explainable%20AI%20-%20From%20Classical%20Models%20to%20LLMs%20-%20Hsieh%20et%20al%20%282024%29.pdf)
- [Artificial Intelligence in Service — Huang & Rust (2018)](ai-and-machine-learning/surveys-and-applications/Artificial%20Intelligence%20in%20Service%20-%20Huang%20%26%20Rust%20%282018%29.pdf)
- [Curvature Tuning — Hu & Balestriero (2025)](ai-and-machine-learning/surveys-and-applications/Curvature%20Tuning%20-%20Provable%20Training-free%20Model%20Steering%20From%20a%20Single%20Parameter%20-%20Hu%20%26%20Balestriero%20%282025%29.pdf)
- [Is Complexity an Illusion? — Bennett (2024)](ai-and-machine-learning/surveys-and-applications/Is%20Complexity%20an%20Illusion%20-%20Bennett%20%282024%29.pdf)

### CUDA and GPU

- [CUDA by Example — Sanders & Kandrot (2010)](cuda-and-gpu/CUDA%20by%20Example%20-%20An%20Introduction%20to%20General-Purpose%20GPU%20Programming%20-%20Sanders%20%26%20Kandrot%20%282010%29.pdf)
- [CUDA C++ Programming Guide v12.8 — NVIDIA (2025)](cuda-and-gpu/CUDA%20C%2B%2B%20Programming%20Guide%20v12.8%20-%20NVIDIA%20%282025%29.pdf)
- [CUDA for Engineers — Storti & Yurtoglu (2015)](cuda-and-gpu/CUDA%20for%20Engineers%20-%20An%20Introduction%20to%20High-Performance%20Parallel%20Computing%20-%20Storti%20%26%20Yurtoglu%20%282015%29.pdf)
- [Learn CUDA Programming — Han & Sharma (2019)](cuda-and-gpu/Learn%20CUDA%20Programming%20-%20Han%20%26%20Sharma%20%282019%29.pdf)
- [Professional CUDA C Programming — Cheng, Grossman & McKercher (2014)](cuda-and-gpu/Professional%20CUDA%20C%20Programming%20-%20Cheng%2C%20Grossman%20%26%20McKercher%20%282014%29.pdf)
- [Programming Massively Parallel Processors — Kirk & Hwu (2010)](cuda-and-gpu/Programming%20Massively%20Parallel%20Processors%20-%20A%20Hands-on%20Approach%20-%20Kirk%20%26%20Hwu%20%282010%29.pdf)

### Parallel and distributed

- [An MPI-based Algorithm for Mapping Complex Networks onto Hierarchical Architectures — Predari et al. (2021)](parallel-and-distributed/An%20MPI-based%20Algorithm%20for%20Mapping%20Complex%20Networks%20onto%20Hierarchical%20Architectures%20-%20Predari%2C%20Tzovas%2C%20Schulz%20%26%20Meyerhenke%20%282021%29.pdf)
- [Introduction to MPI: The Message Passing Interface — Nielsen (2016)](parallel-and-distributed/Introduction%20to%20MPI%20-%20The%20Message%20Passing%20Interface%20-%20Nielsen%20%282016%29.pdf)
- [Notes on Theory of Distributed Systems — Aspnes (2025)](parallel-and-distributed/Notes%20on%20Theory%20of%20Distributed%20Systems%20-%20Aspnes%20%282025%29.pdf)

### Mathematics

- [Applied Linear Algebra and Differential Equations — Chasnov (2019)](mathematics/Applied%20Linear%20Algebra%20and%20Differential%20Equations%20-%20Chasnov%20%282019%29.pdf)
- [Calculus 1 for Honours Mathematics — Forrest & Forrest (2023)](mathematics/Calculus%201%20for%20Honours%20Mathematics%20-%20Forrest%20%26%20Forrest%20%282023%29.pdf)
- [Lecture Notes on Randomized Linear Algebra — Mahoney (2016)](mathematics/Lecture%20Notes%20on%20Randomized%20Linear%20Algebra%20-%20Mahoney%20%282016%29.pdf)
- [Matrix Calculus for Machine Learning and Beyond — Edelman & Johnson (2025)](mathematics/Matrix%20Calculus%20for%20Machine%20Learning%20and%20Beyond%20-%20Edelman%20%26%20Johnson%20%282025%29.pdf)
- [Probability and Statistics for Data Science — Fernandez-Granda](mathematics/Probability%20and%20Statistics%20for%20Data%20Science%20-%20Fernandez-Granda.pdf)
- [Problems in Mathematical Analysis — Demidovich (1970)](mathematics/Problems%20in%20Mathematical%20Analysis%20-%20Demidovich%20%281970%29.pdf)
- [The Mathematics of Artificial Intelligence — Peyré (2025)](mathematics/The%20Mathematics%20of%20Artificial%20Intelligence%20-%20Peyre%20%282025%29.pdf)
- [The Problems Submitted by Ramanujan to the JIMS — Berndt, Choi & Kang (1999)](mathematics/The%20Problems%20Submitted%20by%20Ramanujan%20to%20the%20Journal%20of%20the%20Indian%20Mathematical%20Society%20-%20Berndt%2C%20Choi%20%26%20Kang%20%281999%29.pdf)

### Computer architecture

- [Code: The Hidden Language of Computer Hardware and Software, 1st Edition — Petzold (2000)](computer-architecture/Code%20-%20The%20Hidden%20Language%20of%20Computer%20Hardware%20and%20Software%2C%201st%20Edition%20-%20Petzold%20%282000%29.pdf)
- [Code: The Hidden Language of Computer Hardware and Software, 2nd Edition — Petzold (2022)](computer-architecture/Code%20-%20The%20Hidden%20Language%20of%20Computer%20Hardware%20and%20Software%2C%202nd%20Edition%20-%20Petzold%20%282022%29.pdf)
- [The Elements of Computing Systems, 2nd Edition — Nisan & Schocken (2021)](computer-architecture/The%20Elements%20of%20Computing%20Systems%20-%20Building%20a%20Modern%20Computer%20from%20First%20Principles%2C%202nd%20Edition%20-%20Nisan%20%26%20Schocken%20%282021%29.pdf)

### Cryptography and privacy

- [Introduction to Differential Privacy and the Laplace Mechanism](cryptography-and-privacy/Introduction%20to%20Differential%20Privacy%20and%20the%20Laplace%20Mechanism.pdf)
- [Lecture Notes on Introduction to Cryptography — Goyal, CMU (2020)](cryptography-and-privacy/Lecture%20Notes%20on%20Introduction%20to%20Cryptography%20-%20Goyal%20%282020%29.pdf)

### Programming

- [Competitive Programmer's Handbook — Laaksonen (2018)](programming/Competitive%20Programmer%27s%20Handbook%20-%20Laaksonen%20%282018%29.pdf)
- [The Julia Language Documentation v1.11.2 — The Julia Project (2024)](programming/The%20Julia%20Language%20Documentation%20v1.11.2%20-%20The%20Julia%20Project%20%282024%29.pdf)

### Quantum computing

- [Multi Digit Ising Mapping for Low Precision Ising Solvers — Singh & Jamieson (2024)](quantum-computing/Multi%20Digit%20Ising%20Mapping%20for%20Low%20Precision%20Ising%20Solvers%20-%20Singh%20%26%20Jamieson%20%282024%29.pdf)
- [Quantum Information and Computation — Bub (2006)](quantum-computing/Quantum%20Information%20and%20Computation%20-%20Bub%20%282006%29.pdf)

### Physics

- [PHY405 Relativity, Lecture Notes — Lim](physics/PHY405%20Relativity%20-%20Lecture%20Notes%20-%20Lim.pdf)

### Notes

- [Data Structures and Algorithms in Java — Sinha](notes/Data%20Structures%20and%20Algorithms%20in%20Java%20-%20Sinha.pdf)
- [Learning Probability and Statistics for Machine Learning and Data Science — Sinha](notes/Learning%20Probability%20and%20Statistics%20for%20Machine%20Learning%20and%20Data%20Science%20-%20Sinha.pdf)

### Coursework

- [CS336 Assignment 1: Building a Transformer LM (Spring 2025)](coursework/CS336%20Assignment%201%20-%20Building%20a%20Transformer%20LM%20%28Spring%202025%29.pdf)

---

## 🔗 External links

Good material that lives elsewhere:

- [Awesome Low Latency](https://github.com/penberg/awesome-low-latency) — low-latency programming resources
- [UC Berkeley — Introduction to Mathematical Thinking](http://imt-decal.org/)
- [University of Waterloo — Data Analytics](https://uwaterloo.ca/data-analytics/videos-and-slides-courses) — videos and slides

---

## 🏷️ Topics

Repository topics, so this shelf is findable:

```
awesome  awesome-list  books  ebooks  pdf  learning-resources  computer-science
machine-learning  deep-learning  artificial-intelligence  neural-networks
research-papers  cuda  gpu-programming  parallel-computing  mpi  hpc
mathematics  linear-algebra  probability  statistics
computer-architecture  distributed-systems  cryptography  quantum-computing
```

Apply them in one command with the [GitHub CLI](https://cli.github.com/):

```bash
gh repo edit --add-topic awesome,awesome-list,books,ebooks,pdf,learning-resources,computer-science,machine-learning,deep-learning,artificial-intelligence,neural-networks,research-papers,cuda,gpu-programming,parallel-computing,mpi,hpc,mathematics,linear-algebra
```

> GitHub caps topics at **20 per repository** — the command above uses that budget; swap in `probability`, `statistics`, `computer-architecture`, `distributed-systems`, `cryptography` or `quantum-computing` if they suit you better.

---

## 🤝 Contributing

To add a book or paper:

1. Drop the PDF on the shelf it fits, or propose a new one.
2. Name it `Title - Author (Year).pdf` — matching the rest of the shelf.
3. Add it to the [full catalogue](#-full-catalogue) above, keeping each list alphabetical.
4. Open a PR with a line on why it earned its place.

Only material that is freely and legally distributable, please.

---

## ⚖️ License

The [MIT License](LICENSE) covers this repository's own content — the structure, my notes, the logo.

**It does not cover the PDFs.** Every paper and book here remains under its own copyright,
held by its authors and publishers. They are collected for personal study and reference.
If you hold rights to something here and would like it removed, open an issue and it will be.

<div align="center">
<br>
<img src="assets/logo.svg" alt="" width="60">
<br><br>
<sub>Built and maintained by <a href="https://github.com/sinhaparth5">Parth Sinha</a></sub>
</div>
