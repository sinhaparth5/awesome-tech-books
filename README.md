<div align="center">

<img src="assets/banner.svg" alt="Awesome Tech Books" width="100%">

<br>

**A curated shelf of the books, papers and lecture notes I keep coming back to.**

Foundational AI/ML papers, GPU and parallel programming, the mathematics underneath it all,
and the systems books that explain how the machine actually works.

<br>

![Books & Papers](https://img.shields.io/badge/PDFs-48-818CF8?style=for-the-badge&labelColor=1B1B4B)
![Topics](https://img.shields.io/badge/Shelves-9-22D3EE?style=for-the-badge&labelColor=1B1B4B)
![License](https://img.shields.io/badge/License-MIT-F472B6?style=for-the-badge&labelColor=1B1B4B)

<br>

[Browse the shelf](#-the-shelf) &nbsp;·&nbsp; [Where to start](#-where-to-start) &nbsp;·&nbsp; [External links](#-external-links) &nbsp;·&nbsp; [Contributing](#-contributing)

</div>

---

## 📚 The Shelf

| Shelf | Count | What's inside |
| :--- | :---: | :--- |
| [**AI and ML PDFs**](AI%20and%20ML%20PDFs) | 19 | The canonical papers — perceptrons through transformers — plus probabilistic ML |
| [**mathematics**](mathematics) | 10 | Linear algebra, probability & statistics, analysis, matrix calculus |
| [**cuda-programmings**](cuda-programmings) | 7 | CUDA from first kernels to massively parallel processor design |
| [**MPI PDFs**](MPI%20PDFs) | 3 | Message passing and distributed-memory parallelism |
| [**system-architecture-books**](system-architecture-books) | 3 | How computers work, from NAND gates upward |
| [**Notes**](Notes) | 3 | Lecture notes on probability, DSA and complexity |
| [**cryptograph**](cryptograph) | 1 | Cryptography lecture notes |
| [**programming-book**](programming-book) | 1 | General programming |
| [**assigments**](assigments) | 1 | Course assignments (CS336) |

---

## 🌟 Where to Start

New here? These are the ones worth reading first.

### The papers that built the field

| Paper | Why it matters |
| :--- | :--- |
| [The Perceptron (Rosenblatt, 1958)](AI%20and%20ML%20PDFs/Rosenblatt1958.pdf) | Where learning machines begin |
| [Prediction and Entropy of Printed English (Shannon, 1951)](AI%20and%20ML%20PDFs/shannon_51.pdf) | Language modelling, decades before language models |
| [A Neural Probabilistic Language Model (Bengio et al., 2003)](AI%20and%20ML%20PDFs/bengio03a.pdf) | Word embeddings, from first principles |
| [Deep Learning (LeCun, Bengio & Hinton, Nature 2015)](AI%20and%20ML%20PDFs/nature14539.pdf) | The field's own summary of itself |
| [BERT (Devlin et al., 2019)](AI%20and%20ML%20PDFs/N19-1423.pdf) | Pretraining as the default |
| [FlashAttention-2](AI%20and%20ML%20PDFs/2307.08691v1.pdf) | Why attention got fast |
| [Practical Bayesian Optimization](AI%20and%20ML%20PDFs/1206.2944v2.pdf) | Tuning models without guessing |

### Going deeper

- **GPU programming** → [Programming Massively Parallel Processors](cuda-programmings/Programming%20Massively%20Parallel%20Processors.pdf), then [CUDA by Example](cuda-programmings/cuda_by_example.book.pdf) and the [CUDA C Programming Guide](cuda-programmings/CUDA_C_Programming_Guide.pdf)
- **The machine underneath** → [Code: The Hidden Language of Computer Hardware and Software](system-architecture-books/Code.The.Hidden.Language.of.Computer.Hardware.and.Software.2nd.Edition.2022.7.pdf), then [The Elements of Computing Systems](system-architecture-books/The%20Elements%20of%20Computing%20Systems,%20second%20edition%20Building%20a%20Modern%20Computer%20from%20First%20Principles%20%28Noam%20Nisan%2C%20Shimon%20Schocken%29%20%28z-lib.org%29.pdf)
- **The maths** → [Mathematics of AI](mathematics/Mathematics%20of%20AI.pdf), [Matrix Calculus](mathematics/matrix%20calculus.pdf), [Probability & Statistics for Data Science](mathematics/probability_stats_for_DS.pdf)

---

## 🔗 External Links

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
computer-architecture  systems-programming  cryptography  study-notes
```

Apply them in one command with the [GitHub CLI](https://cli.github.com/):

```bash
gh repo edit --add-topic awesome,awesome-list,books,ebooks,pdf,learning-resources,computer-science,machine-learning,deep-learning,artificial-intelligence,neural-networks,research-papers,cuda,gpu-programming,parallel-computing,mpi,hpc,mathematics,linear-algebra
```

> GitHub caps topics at **20 per repository** — the command above uses that budget; swap in `probability`, `statistics`, `computer-architecture`, `systems-programming`, `cryptography` or `study-notes` if they suit you better.

---

## 🤝 Contributing

Found something that belongs here?

1. Drop the PDF in the shelf it fits (or propose a new one).
2. Keep filenames readable — `Author - Title.pdf` beats `2412.00800v2.pdf`.
3. Open a PR with a line on why it earned its place.

Only material that is freely and legally distributable, please.

---

## ⚖️ License

The [MIT License](LICENSE) covers this repository's own content — the structure, the notes, the logo.

**It does not cover the PDFs.** Every paper and book here remains under its own copyright,
held by its authors and publishers. They are collected for personal study and reference.
If you hold rights to something here and would like it removed, open an issue and it will be.

<div align="center">
<br>
<img src="assets/logo.svg" alt="" width="60">
<br><br>
<sub>Built and maintained by <a href="https://github.com/sinhaparth5">Parth Sinha</a></sub>
</div>
